ZSHA_BASE=$HOME/.zsh-antigen
source $ZSHA_BASE/antigen/antigen.zsh
alias pacman="sudo pacman"
alias napisy="napi-bash"
alias tmux="tmux -2"
export PATH=$PATH:/usr/local/sbin:/usr/local/bin:/usr/bin:/usr/bin/core_perl
LS_COLORS='di=1;31' ; export LS_COLORS

PATH=$PATH:$HOME/.rvm/bin # Add RVM to PATH for scripting
[[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm"

antigen-use oh-my-zsh
antigen-bundle git
antigen-bundle rvm
antigen-bundle archlinux
antigen-bundle ruby
antigen-bundle rails
antigen-bundle bundler
antigen-bundle zsh-users/zsh-syntax-highlighting
antigen-bundle command-not-found


#antigen theme robbyrussell/oh-my-zsh themes/robbyrussell 
#antigen theme $HOME/G-zsh-theme-2/granze2.zsh-theme
antigen theme tolhaje/G-zsh-theme-2 granze2

antigen-apply
