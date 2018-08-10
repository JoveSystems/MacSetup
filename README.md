## Notes on MacOS Setup

#### Installed Apps / Tools

- [Safari](#safari)
- [Chrome](#chrome)
- [VSCode](#vscode)
- [iTerm2](#iterm2)
- [KeyBoard Maestro](#keyboard-maestro)
- [Scrivener](#scrivener)
- [f.lux](#flux)
- [Docker for Mac](#docker-for-mac)
- [Homebrew](#homebrew)
- [pyenv](#pyenv)
- [Bash](#bash)
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

#### [flux](https://justgetflux.com)

#### [Docker for Mac](https://www.docker.com/docker-mac)

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


#### [pyenv](https://github.com/pyenv/pyenv)

Need to add

```bash
eval "$(pyenv init -)" 
```
to 

`~/bashrc`

##### Python versions

- Python 3.6.5
  

#### Fonts

- [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) [OTF version]