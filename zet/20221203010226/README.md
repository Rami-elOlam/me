# Linux Basic

## Basic command used

* man - show manual information about command 
* sudo - super user do: do it as rrot
* apt - use interactively / only use apt-get in script
* sudo apt-get update - update all the source for packages
* sudo apt-get upgrade - upgrade all packages to latest version
* ls - list the files in current directory
* ls -la - list all files including hiddent files in long form
* hostname - show the name of the host of the computer
* pwd - print working directory
* cd - change current directory ! Cannot used in script
* `cd ~` or `cd `to go to the home directory
* `cd -` change to previous directory
* `cd /` change to the root directoy 

## How to install stuff on linux
* `sudo apt search neo` search all packages with neo in name
* `apt search ^neo` search for all package starting with neo
* `sudo apt install packagename` to install a package
* `sudo apt remove packagename` to remove stuff - but this will not remove all the dependencies attached to it
* `sudo apt autoremove` to remove all the stuff that no longer has dependencies
How do I know that `apt` are safe ?