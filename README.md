# dotfiles

Dev setup and dotfiles

# Steps

- Remap Caps lock to the escape key
- Install [Homebrew](https://brew.sh)

  ```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```

  ```bash
  brew install gh
  brew install thefuck
  brew install autoenv
  brew install fzf
  brew install zoxide
  ```

- Install [oh-my-zsh](https://ohmyz.sh/#install)

  ```bash
  sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  ```

  Use the `.zshrc` file.

- Install [nvm](https://github.com/nvm-sh/nvm#install--update-script)

  ```bash
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
  ```

- Install [yarn](https://yarnpkg.com/)

  ```bash
  npm install -g yarn
  ```

- Install the following
  - [Fonts](https://github.com/tonsky/FiraCode/wiki/Installing)
  - Brave `brew install brave-browser`
  - Visual studio code `brew install visual-studio-code`

## Visual Studio

- Sync via Github for settings.

## Git

Turn on gpg signing
`git config --global commit.gpgsign true`
