Mac Setup:

# Shortcuts and window management (tbd)
- setting for fast window switching
- .skhd file 
- copy from folder skhd the .skhd file into ~/.config/.skhd  
```cp ./skhd-profile/skhdrc ~/.config/skhd```

# Setup zsh (tbd)
- .zshrc
- theme

# Brew dump file 
- install brew (https://brew.sh/) 
- dump all existing brew instalations (skip this step if you already have a brewfile)  
```brew bundle dump```  
- add any tool to Brewfile - look up commands at (https://formulae.brew.sh/formula/) 
- install dev tools (run this command from within the root of this repo)  
```brew bundle --file ./brew/Brewfile```