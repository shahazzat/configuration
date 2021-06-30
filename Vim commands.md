# Basic Vim commands
* Install Vim ```yum install vim```
* It has two modes which are given below:
1. Insert mode (Press i for insert mode)
2. Command mode (Press ESC for command mode)
```
:wq (to save and exit)
:q! (to trash all changes)
:<Line number> (jump to any specific line)
```
## Permanent settings for showing line number
```
[root@localhost ~] vim ~/.vimrc
# Add following line into that file and save it.
:set number
```
