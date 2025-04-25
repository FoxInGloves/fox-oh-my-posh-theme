﻿# <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Fox.png" alt="Fox" width="25" height="25" /> Fox theme for Oh My Posh

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Artist%20Palette.png" alt="Artist Palette" width="25" height="25" /> Preview :
![clear prompt](https://github.com/FoxInGloves/Fox-Oh-my-posh-theme/blob/master/src/clear-prompt.png)
![prompt with git](https://github.com/FoxInGloves/Fox-Oh-my-posh-theme/blob/master/src/prompt-with-git.png)
![prompt with dotnet](https://github.com/FoxInGloves/Fox-Oh-my-posh-theme/blob/master/src/prompt-with-dotnet.png)

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Party%20Popper.png" alt="Party Popper" width="25" height="25" /> Usage :
- Install [Oh My Posh](https://ohmyposh.dev/) (read the docs)
- Install a [Nerd Font](https://www.nerdfonts.com/font-downloads) (I'm using JetBrainsMono Nerd Font)
- Set Nerd Font as the default in your terminal
- Add theme in the themes folder (for powershell defaults to %LOCALAPPDATA%\Programs\oh-my-posh\themes)
- Set a theme for your terminal.
  For example, for powershell, edit your profile script ($PROFILE notepad) and add this:
```powershell
oh-my-posh init pwsh --config 'C:\Users\User\AppData\Local\Programs\oh-my-posh\themes\Fox.omp.json' | Invoke-Expression
```
To set a different theme, you need to change the name and configuration path.

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" alt="Gear" width="25" height="25" /> Properties :
- Included segments :
  - user
  - path
  - error code
  - git
  - docker
  - dotnet
  - java
  - execution time
- Time shows seconds and milliseconds
- Git shows :
  - Upstream icon
  - Active branch name
  - The current branch context
  - Changes in the worktree ("x" - unmerged, "-" - deleted, "+" - added, "~" - modified, "?" - untracked)
  - Files ready to commit (symbols as in the previous paragraph)
- Path shows the current disk, the intermediate folder icon, and the name of the current folder

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Handshake.png" alt="Handshake" width="25" height="25" /> Aknowledges :
This theme was inspired by [di4am0nd's](https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/di4am0nd.omp.json) theme
