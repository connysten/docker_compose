# Fixa runner så att pipelines funkar

For my case, gitlab was behind a proxy other than the built-in traefik proxy. I believe this caused the necessity of using this setting. After registering your runner, edit the config.toml and and add the clone_URL

[[runners]]
  url = "https://gitlab.example.com"
  clone_url = "https://gitlab.example.com"
This solved the issue for me.
