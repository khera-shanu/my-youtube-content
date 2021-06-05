## Content covered in this session

### `*nix commands every programmer must know`

#### File system related commands
 - `pwd`
 - `ls`
 - `tree`
 - `cd`
 - `cp`
 - `rm`
 - `rmdir`
 - `mv`
 - `mkdir`
 - `cat`
 - `wc`
 - `less`
 - `more`
 - `head`
 - `tail`
 - `echo`
 - `ln`
 - `df`
 - `du`

#### Date related commands 
 - `cal`
 - `date` (Not time, it is for something else, find below)

#### User related
 - `whoami`
 - `passwd`
 - `su`
 - `sudo`
 - `usermod`
 - `adduser`
 - `userdel`
 - `chmod`
 - `chown`

#### Finding stuff and metadata
 - `man`
 - `find`
 - `grep`
 - `whereis`
 - `which`
 - `type`
 - `locate` (I don't like this one, due to its dependency on local db for indexing purpose)

#### Useful utilities (including network related commands)
 - `alias`
 - `export`
 - `env`
 - `sort`
 - `diff`
 - `uniq`
 - `cut`
 - `time` - time taken by a command to run
 - `watch`
 - `history` and "bang"
 - `openssl`
 - `iptables` 
 - `ssh`
 - `scp`
 - `rsync`
 - `tar`, `gzip`, `unzip`, etc.
 - `nc`
 - `telnet`
 - `ipconfig`, `ifconfig`, `iwconfig`
 - `nmap`
 - `lsof`
 - `tcpdump`
 - `ping`
 - `traceroute`
 - `whois`
 - `arp`
 - `netstat`
 - `dig`
 - `nslookup`
 - `host`
 - `curl`, `wget`

#### Some special characters
 - `/` - Root directory
 - `.` - Current working directory
 - `..` - Parent working directory
 - `~` - Home directory

#### Some regex-like characters
 - `*` - wildcard for 0 or more characters
 - `?` - wildcard for 1 or more characters
 - `[]` - Range

#### Some important files
 - `~/.bashrc` or `~/.bash_profile`
 - `~/.vimrc`
 - `/etc/hosts`
 - `~/.ssh`
 - `~/.aws`

#### Some important envs
 - `PATH`
 - `SHELL`
 - `PS1`
 - `PWD`
 - `OLDPWD`

#### Some important folders (under `/` and/or under `/usr/`)
 - `etc` - config files
 - `bin` - binary/executables
 - `lib` - shared libraries
 - `tmp` - temporary files (deleted by OS)
 - `var` - variable data files, such as logs, db data, etc.

#### Some gotchas and fundas
 - `everything is a file in Linux` - Including hardware(logically) - see `/dev` - `This is because of a consistent API design`
 - `Linux is case-sensitive, Mac is not`
 - `Learn about inode in linux`
 - `Learn to write code in emacs or vi editor`
 - `Learn about stream and standard streams - stdout, stdin, stderr`
 - "Learn about stream redirection"
 - "Piping"
 - "Signals using CTRL+<KEY>"
