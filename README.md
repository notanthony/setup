###git config --global alias.pushfwl "push --force-with-lease"
###git config --global alias.co checkout



fpath=(~/.zsh $fpath)



# Quickly update dotfiles

alias zu="source ~/.zshrc"

alias zedit="vim ~/.zshrc"

alias vedit="vim ~/.vimrc"



# Dev shortcuts

alias gits="git status"

alias gitb="git branch"

alias gitde="gitb -d"

alias gitd="git diff"

alias gitm="git co main; git pull"

alias gitr="git rebase -i main"

alias gitur="gitm; git co -; gitr"

alias capy="bundle exec cucumber -p mac-rc -p chrome"



alias v="vim"

alias vi="vim"

alias g="grep -ri"



# Easier backtracking

alias ..="cd .."

alias ...="cd ../.."

alias ....="cd ../../.."

alias .....="cd ../../../.."
