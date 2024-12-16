Shell scripting is the language to talk directly to the Kernel in Linux/Unix

| User | - | Shell   | - | Kernel  | - | Hardware |
|------|---|---------|---|---------|---|----------|

**Types of Shell**
- sh = Bourne Shell
- csh = C shell
- tcsh = Superset of C shell
- ksh = Korn Shell
- bash = Bourne again Shell

Types of shell
1. Login      : A "login shell" is a shell that is initiated when you log into a system, requiring your username and password, and therefore reads specific configuration files like /etc/profile to set up your environment
2. Non-login  : A "non-login shell" is a shell started without logging in, usually launched from within an existing session, and typically only reads your user-specific configuration files like ~/.bashrc

To check the running shell
```bash
echo $0~
#result:  bash
echo $SHELL
#result: /bin/bash
```
**Bash Scripting Basics**
Types of variable
1. Shell variable
```bash
a=50
echo $a
```
2. Environmental variable  : It added for all shell
```bash
export a=50
echo $a
```
