# Use the htpasswd command to generate this file. Replace your_username with the desired username:

```shell
htpasswd -c ./htpasswd your_username
```

# To add more users to the existing .htpasswd file, use the following command:

```shell
htpasswd ./htpasswd another_username
```
