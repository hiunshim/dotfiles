brew install neovim\
brew tab homebrew/cask-fonts\
brew install font-meslo-lg-nerd-font

mkdir -p ~/.config/nvim

rm -rf ~/.local/share/nvim\
rm -rf ~/.local/state/nvim\
rm -rf ~/.cachel/nvim

ln -s ~/[directory]/vimrc ~/.vimrc\
ln -s ~/[directory]/zshrc ~/.zshrc\
ln -s ~/[directory]/nvim ~/.config/nvim\
ln -s ~/[directory]/tmux.conf ~/.tmux.conf

