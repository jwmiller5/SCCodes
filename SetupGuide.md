# Setup Guide for Windows 10
## The big three: a browser, an editor, and a terminal
### Browser
* [Google Chrome](https://www.google.com/chrome/) is an often-recommended web browser for developers due to the powerful [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/) that allow developers to inspect and debug code. Other browsers have introduced developer tools as well, but for this course, we recommend Google Chrome.
### Editor
* A major improvement to your development environment will be the use of a dedicated text editor. [Visual Studio Code](https://code.visualstudio.com/) is a free development environment with Git support built in and extensions for all of the languages covered in our courses.
### Terminal
We will install and configure a Linux terminal in Windows to ensure new developers learn the commands needed and can switch between Linux/Mac/Windows environments. This also makes maintaining the courses easier as the same commands can be used, rather than creating environment-specific instructions.
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
* Install Node
```bash
brew install node
```

## Some useful links
* [Setting up homebrew and working with WSL in Windows 10](https://medium.com/@edwardbaeg9/using-homebrew-on-windows-10-with-windows-subsystem-for-linux-wsl-c7f1792f88b3)
* [Developing in WSL](https://code.visualstudio.com/docs/remote/wsl) - explains how to install Visual Studio Code in Windows and keep all of your code and commands in WSL
* [Synthwave inspired theme for VS Code](https://marketplace.visualstudio.com/items?itemName=webrender.synthwave-x-fluoromachine)
