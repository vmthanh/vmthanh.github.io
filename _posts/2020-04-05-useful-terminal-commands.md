---
title: Useful Terminal Commands
layout: post
excerpt: "Useful Terminal Commands" 
tags:
- terminal
- commands
- linux

---

In a daily life of **Data Scientist** or **General developer**, you definely will have to work with server quite often. Here are the list of terminal commands, I found it usefuly to me (subjectively) in many cases. The new one is updated frequently. 

- #### Tunnel ssh connection
```bash
ssh -N -f -L localhost:$1\:localhost:$1 ld-vmthanh@$2
```
```bash
ssh -L 5601:localhost:5601 FACE
```

- #### Remove process with PID 
```bash
kill -9 PID
```

- #### Match an exact string in file 
```bash
cat <file_name> | grep <string_pattern>
```

- #### Remove all running process binding with port
```bash
sudo kill $(sudo lsof -t -i:PORT_NO)
```

- #### Remove .git recursively
```bash
find . | grep .git | xargs rm -rf
```

- #### Check NVIDIA Driver without NVIDIA-SMI
```bash
lspci | grep -i nvidia
```

- #### Create symbolic link 
```bash
# Creation 
ln -s {/path/to/file-name} {link-name}
# Update 
ln -sfn {/path/to/file-name} {link-name}
```

- #### Get the lines from 15th to 20th
```bash
find . | head -20 | tail -5
```

- #### Count number of line in a file 
```bash
wc -l <file_name>
```

- #### Count number of files in a folder 
```bash
ls <folder> | wc -l 
```

- #### Resync with delete old file 
```bash
rsync -azP --delete-before SRC DST
```

- #### Create env on conda
```bash
conda create --name <name_env>
```

- #### Remove env in conda 
```bash
conda remove --name <name_env> --all
```

- #### Chec how long a process is running in LInux

```bash
ps -eo pid,lstart,etime | grep PID
```

