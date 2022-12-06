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
* `cd ~` or `cd `to go to the home directoryj
* `cd -` change to previous directory
* `cd /` change to the root directoy 
* `| more` or `| less` to see scrolled output in terminal
* `<Ctrl>-d` send 'end of data/files'
* `vboxmanage startvm $<vmname> --type headless` start vm headless
* `vboxmanage list runningvms` list runing vms
* `vboxmanage list vms` list all vms
* `vboxmanage controlvm $<vmname> poweroff` poweroff headless vm

## How to install stuff on linux
* `sudo apt search neo` search all packages with neo in name
* `apt search ^neo` search for all package starting with neo
* `sudo apt install packagename` to install a package
* `sudo apt remove packagename` to remove stuff - but this will not remove all the dependencies attached to it
* `sudo apt autoremove` to remove all the stuff that no longer has dependencies
How do I know that `apt` are safe ?

## SSH

- The first thing we need to do is to verify that everything is on the same network as all of our computer system
- NAT (Network Access Translation) vs Bridged
- How to connect to our VM ?
- What is an IP address ? 
- How can you test ssh to localhost ?
- Why can't I use the 126 adresses ?
- What is the connect `ssh` connection address ?

### Commands

* `ip a` sholl all IP adresses
* `which ssh` display full path of the ssh program
* `type ssh` display what type of thing it is
* `who`display who is logged in and how
* `users` display a short name of all logged in users
* `id` display users and group name and id for self
* `w` display longer version of who is logged in 
* `last` display summary of the last user logged in
* `exit` exit the current program or login or shell
