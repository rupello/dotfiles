# dotfiles management

### setup the repo
`git clone git@github.com:rupello/dotfiles.git ~/dotfiles`

### install a package to the parent (ie home dir)
`cd ~/dotfiles && stow foo`
This will create links such as `.bar -> dotfiles/foo/.bar` in your home dir

### uninstall links:
`cd ~/dotfiles && stow -D foo`







