# Create symbolic link of homebrew python@3.9
## Check the content of /usr/local/bin
```
shahazzat@Mohammads-MacBook-Pro ~ % ls -la /usr/local                                                         
total 0
drwxr-xr-x   3 root  wheel   96 May 19 10:07 .
drwxr-xr-x@ 11 root  wheel  352 Jan  1  2020 ..
drwxr-xr-x   2 root  wheel   64 May 19 23:50 bin
shahazzat@Mohammads-MacBook-Pro ~ % ls -la /usr/local/bin 
total 0
drwxr-xr-x  2 root  wheel  64 May 19 23:50 .
drwxr-xr-x  3 root  wheel  96 May 19 10:07 ..
```
## Create symbolic link
```
shahazzat@Mohammads-MacBook-Pro ~ % sudo ln -s /opt/homebrew/Cellar/python@3.9/3.9.5/bin/python3 /usr/local/bin/python3.9
shahazzat@Mohammads-MacBook-Pro ~ % ls -la /usr/local/bin
total 0
drwxr-xr-x  3 root  wheel  96 May 20 01:08 .
drwxr-xr-x  3 root  wheel  96 May 19 10:07 ..
lrwxr-xr-x  1 root  wheel  49 May 20 01:08 python3.9 -> /opt/homebrew/Cellar/python@3.9/3.9.5/bin/python3
## Check python version
shahazzat@Mohammads-MacBook-Pro ~ % python3.9
Python 3.9.5 (default, May  3 2021, 19:12:05) 
[Clang 12.0.5 (clang-1205.0.22.9)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> exit()
```
# Create virtual environment
```
shahazzat@Mohammads-MacBook-Pro ~ % virtualenv --version
zsh: command not found: virtualenv
shahazzat@Mohammads-MacBook-Pro ~ %

shahazzat@Mohammads-MacBook-Pro workspace % python3.9 -m venv tutorial-env
shahazzat@Mohammads-MacBook-Pro workspace % ls
tutorial-env
```
## Activate virtual environment
```
shahazzat@Mohammads-MacBook-Pro workspace % . tutorial-env/bin/activate
(tutorial-env) shahazzat@Mohammads-MacBook-Pro workspace % python
Python 3.9.5 (default, May  3 2021, 19:12:05) 
[Clang 12.0.5 (clang-1205.0.22.9)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> exit()
(tutorial-env) shahazzat@Mohammads-MacBook-Pro workspace %
```
