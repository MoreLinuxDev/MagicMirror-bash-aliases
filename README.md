# MagicMirror-bash-aliases
Collection of useful bash aliases to be used with MagicMirror2

With this bash aliases collection, the configuration, module installation and CSS layout changes should become easier.

Using ssh to connecting to the Raspberry PI running MagicMirror2 is fine, but from within bash you have to jump between the directories:
```
~/MagicMirror         => The MagicMirror root directory
~/MagicMirror/config  => The MagicMirror configuration directory
~/MagicMirror/modules => The MagicMirror modules root directory
~/MagicMirror/css     => The MagicMirror CSS directory
```

In bash it is possible to setup personal alias in the file .bash_aliases. This file is located in your home directory and loaded during login. In this file you can name all your personal aliases without worrying that a Linux patch or update will remove them.

The structure is as follows:
```
alias <alias name>='<command to execute'  # A comment that explains the purpose
```

### Download the .bash_aliases file to you users home directory using the following command:
```
wget https://raw.githubusercontent.com/MoreLinuxDev/MagicMirror-bash-aliases/Development/.bash_aliases 
```
