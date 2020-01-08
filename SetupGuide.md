# Setup Guide for Windows
## The Big 3
### Browser
* [Google Chrome](https://www.google.com/chrome/)
### Editor
* Instructions for [installing Visual Studio Code](https://code.visualstudio.com/)
### Terminal
* Instructions for [installing Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10) on Windows 10 
  * I chose Ubuntu 16.04 for my linux distro
* Install zsh and Oh My Zsh

```bash
sudo apt-get update
sudo apt-get install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
* Install homebrew

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/Linuxbrew/install/master/install.sh)"
sudo apt-get install build-essential
echo 'eval $(/home/linuxbrew/.linuxbrew/bin/brew shellenv)' >>~/.zprofile
eval $(/home/linuxbrew/.linuxbrew/bin/brew shellenv)
```


* https://medium.com/@edwardbaeg9/using-homebrew-on-windows-10-with-windows-subsystem-for-linux-wsl-c7f1792f88b3
