<h1 align="center">~/dotfiles</h1>

<p align='center'><sub>~~ All the small things ~~</sub></p>

### ⚠️ Requirements

#### Commands

- [chezmoi](https://www.chezmoi.io/)

#### Fonts

Must be installed prior to utilizing the dotfiles:

- [nerd-fonts](https://www.nerdfonts.com)
- [ttf-nerds-fonts-symbol](https://www.archlinux.org/packages/community/x86_64/ttf-nerd-fonts-symbols/)
- [jetbrains-mono](https://www.jetbrains.com/lp/mono/)

### 🚀 Installation

- Install chezmoi with `yay chezmoi`.

### ✨ Daily Operations

- `chezmoi add $FILE` - adds $FILEfrom your home directory to the source directory.

- `chezmoi edit $FILE` - opens your editor with the file in the source directory that corresponds to $FILE.

- `chezmoi status` - gives a quick summary of what files would change if you ran chezmoi apply.

- `chezmoi diff` - shows the changes that chezmoi apply would make to your home directory.

- `chezmoi apply` - updates your dotfiles from the source directory.

- `chezmoi edit --apply $FILE` - is like chezmoi edit $FILE but also runs chezmoi apply $FILE afterwards.

- `chezmoi cd` - opens a subshell in the source directory (`~/.local/share/chezmoi`).

### Syncing Machines

- `chezmoi init $GITHUB_USERNAME` - clones your dotfiles from GitHub into the source directory.

- `chezmoi init --apply $GITHUB_USERNAME` - clones your dotfiles from GitHub into the source directory and runs chezmoi apply.

- `chezmoi update` - pulls the latest changes from your remote repo and runs chezmoi apply.

> NOTE: Use normal git commands to add, commit, and push changes to your remote repo.


### 🖥️ Software

- OS: Linux
- Distro: EndeavourOS
- Desktop: KDE Plasma
- Terminal: foot

### 🙏 Credits

- @twpayne's [chezmoi](https://github.com/twpayne/chezmoi)
