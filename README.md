<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="144px" height="144px"/>

#### beep theme
> A Powerline-style, Git-aware theme for [Oh My Fish][omf-link]. Originally based on [es](https://github.com/oh-my-fish/theme-es)

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE) [![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](http://fishshell.com) [![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square)](https://www.github.com/oh-my-fish/oh-my-fish)

<br/>

## Install
Install using [fisher][fisherman-link] or [Oh My Fish][omf-link]:

### For Oh My Fish
```fish
$ omf ins
```

### For Fisherman
```fish
$ fisher dkowis/theme-beep
```

## Requirements
* Latest fish version with a builtin `string` function (above `2.2.0`, so please get the latest version from  `HEAD`)
* A [Nerd-Fonts][nerd-fonts-link] patched font

## Features

* Git-aware theme with detailed __Git status__ in the left prompt (added, removed, modified, renamed, unstaged, stashed)
* __Node/Python/Ruby@gemset/Java__ current version inside a git folder in the right prompt if respective virtual environment manager is installed (nvm, nodenv, pyenv, rbenv, jenv)
* __Error status__ and __duration of last command__ in the right prompt
* Mac-notifications on completion of long commands (10+&nbsp;seconds by default) if terminal (iTerm and Terminal) is out of focus
* Limits path to __two last folders__ for better visibility, with `$HOME` directory abbreviated to `~`
* Shows hostname on the right prompt when SSH'd

## Screenshot

TODO: make screenshots!

# License

[MIT][mit] © [eugenesvk][author] for original es and [David Kowis][beep-author] for modifications


[mit]:              https://opensource.org/licenses/MIT
[author]:           https://github.com/eugenesvk
[beep-author]:      https://github.com/dkowis
[omf-link]:         https://www.github.com/oh-my-fish/oh-my-fish
[fisherman-link]:   https://github.com/fisherman/fisherman
[nerd-fonts-link]:  https://nerdfonts.com

[license-badge]:    https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
