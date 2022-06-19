# Python2_Spawn_Shell
python2 pty spawn shell

```
user@user $ python

Python 2.7.16 (default, Sep  6 2021, 07:39:44) 
[GCC Apple LLVM 12.0.5 (clang-1205.0.19.59.6) [+internal-os, ptrauth-isa=deploy on darwin
Type "help", "copyright", "credits" or "license" for more information.

>>> 2+2
4
>>> import pty
>>> pty.spawn("/bin/bash")

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.

bash-3.2$ <enter command>

```
