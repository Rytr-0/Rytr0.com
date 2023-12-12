+++
title = 'RsyncCheatSheet'
date = 2023-12-09T05:48:32-05:00
draft = false
description =' '
summary = ' ' 
+++

### Rsync cheat sheet for copy & paste

- Copy from remote host to your computer:
  - Format:
    `rsync -a username@remote_host:/home/username/dir1 place_to_sync_on_local_machine`
  - Command example:
    `rsync -a root@192.168.30.30:/var/www ~/syncedFiles`
    >
- Copy from your computer to a remote host:
  - Format:
    `rsync -a ~/dir1_place_on_host_machine username@remote_host:destination_directory`
  - Example:
    `rsync -a ~/syncedFiles root@192.168.30.30:/var/www`
      
