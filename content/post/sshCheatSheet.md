+++
title = 'SshCheatSheet'
date = 2023-12-09T04:59:39-05:00
draft = false
description =' Copy SSH commands and take what you need'
summary = ' > SSH commands for a quick copy & paste' 
+++

### SSH Commands to copy & paste

Ever forgotten commands only to find a huge article with 90% fulff?

well, here you can just search, copy & paste them.


- Creating SSH directory & settiong it up with correct permissions:

`mkdir -p $HOME/.ssh`

`chmod 0700 $HOME/.ssh`


- SSH keys creation:

`ssh-keygen -t rsa`

1. `$HOME/.ssh/id_rsa` – contains your private key.
2. `$HOME/.ssh/id_rsa.pub` – contain your public key.

- SSH file for storing public keys *on the server you want to enter*:

`.ssh/authorized_keys`

- SSH confing file:

`/etc/ssh/sshd_config`

- SSH keygen removal for when asked *"Someone is doing something nasty"*:

`ssh-keygen -R 1.1.1.1`
