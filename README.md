# Dotfiles Repository

This repository contains dotfiles managed with GNU Stow,
allowing you to easily symlink configuration files to your home directory.

## Installation

### Clone this repository

```bash
git clone --recursive https://github.com/ForAeons/.dotfiles.git
```

### Install Stow

- **macOS**: Use Homebrew to install Stow.

  ```sh
  brew install stow
  ```

- **Arch Linux**: Use Pacman or any AUR helper to install Stow.

  ```sh
  pacman -S stow
  ```

- **Debian-Based Systems**: Use apt to install Stow.

  ```sh
  sudo apt install stow
  ```

### Configuration

1. **Using Stow:**

   Use Stow to create symbolic links in your home directory. For example,
   to symlink your git configuration, navigate to the repository's root and run:

   ```sh
   cd ~/.dotfiles # cd to the directory where you cloned your dotfiles
   stow --adopt .
   ```

This will create the necessary symbolic links in your home directory to the
files managed within this dotfiles repository.
