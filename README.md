## Notes on MacOS Setup

#### Installed Apps / Tools

- [Notes on MacOS Setup](#notes-on-macos-setup)
    - [Installed Apps / Tools](#installed-apps--tools)
    - [Safari](#safari)
    - [Chrome](#chrome)
    - [VSCode](#vscode)
    - [iTerm2](#iterm2)
    - [KeyBoard Maestro](#keyboard-maestro)
    - [Scrivener 2.9](#scrivener-29)
    - [Scrivener 3.0](#scrivener-30)
    - [MasterKey](#masterkey)
    - [Kindle for Mac](#kindle-for-mac)
    - [Sublime Merge](#sublime-merge)
    - [VirtualBox](#virtualbox)
    - [Firefox](#firefox)
    - [flux](#flux)
    - [Docker for Mac](#docker-for-mac)
    - [HazeOver](#hazeover)
    - [kitty](#kitty)
    - [iina](#iina)
    - [TheUnarchiver](#theunarchiver)
    - [Brave](#brave)
    - [Magnet](#magnet)
    - [Bear](#bear)
    - [1Password](#1password)
    - [Bash](#bash)
    - [Homebrew](#homebrew)
    - [pyenv](#pyenv)
      - [Python versions](#python-versions)
    - [Zero-to-Jupyterhub](#zero-to-jupyterhub)
    - [Fonts](#fonts)

#### Safari

- [Pocket Extension](https://safari-extensions.apple.com/details/?id=com.ideashower.pocket.safari-ET279A6R5N)

#### [Chrome](https://www.google.com/chrome/)
- [Pocket Extension](https://chrome.google.com/webstore/detail/save-to-pocket/niloccemoadcdkdjlinkgdfekeahmflj?hl=en)

#### [VSCode](https://code.visualstudio.com)

- [MS Python Extension](https://github.com/Microsoft/vscode-python)
- [Base 16 Themes](https://marketplace.visualstudio.com/items?itemName=AndrsDC.base16-themes)
- [Markdown all in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- Use settings in vscode/settings file

#### [iTerm2](https://www.iterm2.com)
- [Revised Icon](https://dribbble.com/shots/1682322-iTerm-Redesign-Replacement-icns)
- Theme: [Base 16 Oceanic Next]()
- Font: Source Code Variable Medium 14pt

#### [KeyBoard Maestro](https://www.keyboardmaestro.com/main/)

- Install macros etc in keyboard-maestro subdirectory

#### [Scrivener 2.9](https://www.literatureandlatte.com/scrivener.php)

- [Revised Icon](https://dribbble.com/shots/978125-Scrivener-Icon-Replacement)

#### [Scrivener 3.0](https://www.literatureandlatte.com/scrivener.php)

#### [MasterKey](http://macinmind.com/?area=app&app=masterkey&pg=info)

- [Revised Icon](http://icons-for-free.com/icon/apple_command_key_keyboard_modifier_icon_1891024.html)

#### [Kindle for Mac](https://itunes.apple.com/gb/app/kindle/id405399194?mt=12)

#### [Sublime Merge](https://www.sublimemerge.com)

#### [VirtualBox](https://www.virtualbox.org)

#### [Firefox](https://www.mozilla.org/en-GB/firefox/new/)

#### [flux](https://justgetflux.com)

#### [Docker for Mac](https://www.docker.com/docker-mac)

#### [HazeOver](https://hazeover.com/)

#### [kitty](https://sw.kovidgoyal.net/kitty/)

#### [iina](https://iina.io/)

#### [TheUnarchiver](https://theunarchiver.com/)

#### [Brave](https://brave.com/)

#### [Magnet](http://magnet.crowdcafe.com/)

#### [Bear](https://bear.app)

#### [1Password](https://1password.com)

#### Bash

Consolidate all Bash sartup scripts into .bashrc by including

```bash
if [ -f $HOME/.bashrc ]; then
        source $HOME/.bashrc
fi
```

in

`~/.bash_profile`

#### [Homebrew](https://brew.sh)

Note that Homebrew will install Apple's command line tools which are needed by pyenv to compile Python

- git
- pyenv
- ruby
'''brew install rbenv ruby-build

# Add rbenv to bash so that it loads every time you open a terminal
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
source ~/.bash_profile

# Install Ruby
rbenv install 2.6.1
rbenv global 2.6.1
ruby -v
'''


#### [pyenv](https://github.com/pyenv/pyenv)

Need to add

```bash
eval "$(pyenv init -)" 
```
to 

`~/bashrc`

##### Python versions

- Python 3.6.5

#### Zero-to-Jupyterhub

- [Guide to using JupyterHub on Minikube](https://github.com/jupyterhub/zero-to-jupyterhub-k8s/blob/b5393da84e2e539fe2711bd3ea8ef6b1613d210b/CONTRIBUTING.md)
- [Minikube](https://kubernetes.io/docs/setup/minikube/)

Note first need to install XCode developer tools as per:
```bash
xcode-select --install
```
  

#### Fonts

- [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) [OTF version]