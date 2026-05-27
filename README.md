# ubuntu-dotfiles-v2

Bash customizations for Ubuntu / WSL — modular prompt, aliases, and functions.

## Layout

```
.config/bash/
├── .prompt     # multi-line PS1 with git branch and exit status
├── .aliases    # reload, cd shortcuts
└── .functions  # sw()
```

## Install

Add to `~/.bashrc` (after the default Ubuntu blocks, before NVM):

```bash
DOTFILES_V2="${HOME}/ubuntu-dotfiles-v2"
source "${DOTFILES_V2}/.config/bash/.prompt"
source "${DOTFILES_V2}/.config/bash/.aliases"
source "${DOTFILES_V2}/.config/bash/.functions"
```

Then run `source ~/.bashrc` or open a new terminal.

## Prompt preview

```
jasond · ~/srv/www/v3-experiment · master
  ▸
```
