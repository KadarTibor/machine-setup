Mac Setup:

# Setup ssh key
- follow the official github guide [Generate ssh key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent), [Add ssh key to github](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

# Shortcuts and window management
- setting for fast window switching
- .skhd file 
- copy from folder skhd the .skhd file into ~/.config/.skhd  
```cp ./skhd-profile/skhdrc ~/.config/skhd```
```skhd --start-service```

# Zshrc file


# Setup terminal
- ```cp ./starship-terminal/starship.toml ~/.config/starship.toml```
- add ```eval "$(starship init zsh)"``` to the .zshrc file


# Brew dump file 
- install brew (https://brew.sh/) 
- dump all existing brew instalations (skip this step if you already have a brewfile)  
```brew bundle dump```  
- add any tool to Brewfile - look up commands at (https://formulae.brew.sh/formula/) 
- install dev tools (run this command from within the root of this repo)  
```brew bundle --file ./brew/Brewfile```