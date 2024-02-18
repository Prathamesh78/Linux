# User Administration in Linux

This guide provides basic instructions for user administration in Linux using command-line tools.

## Adding a New User

To add a new user, you can use the `useradd` command followed by the desired username:
```bash
sudo useradd -m newusername
```

## Setting Password for a User

You can set a password for the newly created user using the 'passwd' command:
```bash
sudo passwd newusername
```

### Modifying User Properties

To modify user properties such as the username or home directory, you can use the 'usermod' command:
```bash
sudo usermod -l newusername oldusername
```

### Deleting a User

To delete a user, you can use the 'userdel' command followed by the username:
```bash
sudo userdel username
```

### Granting sudo Privileges

To grant sudo privileges to a user, add the user to the 'sudo' group using the 'usermod' command:
```bash
sudo usermod -aG sudo newusername
```

### Viewing User Information

You can view information about users using the'id' command or 'getent' command:
```bash
id newusername
getent passwd newusername
```
