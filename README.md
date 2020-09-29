# dotfiles

## Visual Studio Code

### Extensions

To export extensions:  
`code --list-extensions > extensions.list`

To install all extensions:  
`cat extensions.list | grep -v '^#' | xargs -L1 code --install-extension`

### Settings file

Ubuntu -> ~/.config/Code/User/settings.json
