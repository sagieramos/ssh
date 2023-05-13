### ssh-keygen to Generate a New SSH Key

- ```ssh-keygen -t rsa -b 4096```
- ```ssh-keygen -t dsa```
- ```ssh-keygen -t ecdsa -b 521```
- ```ssh-keygen -t ed25519```

#### Specifying the File Name
Normally, the tool prompts for the file in which to store the key. However, it can also be specified on the command line using the -f <filename> option.

```ssh-keygen -f ~/tatu-key-ecdsa -t ecdsa -b 521```

[source](https://www.ssh.com/academy/ssh/keygen)