# windows-terminal-profile
To store my personal windows terminal setup with some custom styles and profile values. This solution is based on another from [Scott Hanselman](https://github.com/shanselman). 


## How to setup

Here some steps and notes to perfom the actual configuration that is available of each shell type.

### Shells
1. [Install Powershell Core (7)](https://github.com/PowerShell/PowerShell/releases/)
2. [Enable Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
3. [Install windows terminal from windows store](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab)
4. [Install cascadia-font](https://github.com/microsoft/cascadia-code/releases)

### Utilities

1. [nodejs](https://nodejs.org/en/download/)
2. [git for windows](https://git-scm.com/download/win)
3. [chocolatey](https://chocolatey.org/install)
4. [AzureCLI](https://aka.ms/installazurecliwindows)

## Resources Index


|File   |Shell   |Description   |
|---|---|---|
| <a href="settings.json">settings.json</a>  | Windows Terminal  | Contains the main configuration profile for windows terminal app behaviour
| <a href="$PROFILE.ps1">$PROFILE.ps1</a>  | PowerShell Core  | Contains the import modules to configure the shell and the initial path route  |
| <a href="bashrc.sh">bashrc.sh</a>  | WSL  | Contains the import modules to configure the shell run: **code ~/.bashrc**  |

## Credits

These configurations are based on [Scott Hanselman](https://github.com/shanselman) blog post of [How to make a pretty prompt in Windows Terminal with Powerline, Nerd Fonts, Cascadia Code, WSL, and oh-my-posh](https://www.hanselman.com/blog/how-to-make-a-pretty-prompt-in-windows-terminal-with-powerline-nerd-fonts-cascadia-code-wsl-and-ohmyposh). A big thank you for the tips and tricks.

![Windows Terminal](https://media.giphy.com/media/qSVPjP7P3SbJXW7mmH/giphy.gif)
