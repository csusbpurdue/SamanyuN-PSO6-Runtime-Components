# Runtime Components

My personal configuration files (dotfiles) for bash, zsh, vim, git, and gdb,
along with a script to install them automatically on a new machine.

## Contents

- `.bashrc` — bash shell configuration
- `.zshrc` — zsh shell configuration
- `.vimrc` — vim editor configuration
- `.gdbinit` — gdb debugger configuration
- `.gitconfig` — git configuration
- `install.sh` — copies these files into place in your home directory

## Usage

Clone this repo, then run:

\`\`\`bash
./install.sh
\`\`\`

This copies each rc file to your home directory (e.g. `.vimrc` → `~/.vimrc`).
