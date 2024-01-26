# zypptools
Missing commands for the openSUSE's zypper package manager.

### Available commands: 

`zypptools userinstalled` - list all packages that were manually installed by the user

`zypptools autoremove` - find and remove unneeded dependencies

`zypptools why <package>` - list all installed packages that require or recommend the specified package

`zypptools ban <package>` - uninstall the package including its dependencies and prevent reinstallation (as a dependency of another package or pattern)

### How to install

`curl -s -o ~/bin/zypptools https://raw.githubusercontent.com/eylenburg/zypptools/main/zypptools && chmod +x ~/bin/zypptools`

Now you can run `zypptools` in your terminal.

