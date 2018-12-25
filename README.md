# dotfiles
Dev setup and dotfiles 

# Steps

- Remap Caps lock to the escape key
- Configure SSH keys

Use (github guide)[https://help.github.com/articles/connecting-to-github-with-ssh/]. Generate keys with the following: 

    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
    
Configure the ssh agent to auto add items. 

- Clone and go to the (dev setup)[https://github.com/jeffpatzer/dev-setup] repo and run the following setup files. 

        $ ./.dots bootstrap 
        $ # syncs the dev-setup repo with the home repo (as in files live within the dev-setup repo but get copied into the home directory)
        $ ./.dots osxprep
        $ ./.dots brew # configures homebrew and installs most 
        $ ./.dots osx
        $ ./.dots datastores osx web
        $ brew update; brew install node

# Configure Visual Studio Code
