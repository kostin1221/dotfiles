mkdir ~/.dotfiles && git clone git@github.com:DsTr/dotfiles.git ~/.dotfiles && alias hgit='git --git-dir ~/.dotfiles/.git --work-tree=$HOME' && hgit reset --hard && hgit submodule update --init --recursive
