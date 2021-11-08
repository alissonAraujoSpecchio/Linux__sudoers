# Linux__sudoers
How to create sudoers

Edit this file:
```
vim /etc/sudoers
```

Add this line:
```
user_name ALL=(ALL)
```

If you want to execute sudo commands without requiring a password, use NOPASSWD parameter:

```
user_name ALL=(ALL) NOPASSWD:ALL
```
