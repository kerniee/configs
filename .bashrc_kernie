# Include this in ~/.bashrc
# if [ -f ~/.bashrc_kernie ]; then
#     . ~/.bashrc_kernie
# fi

PS1="\[\e]0;\h: \w\a\]${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\h\[\033[00m\]: \[\033[01;34m\]\w\[\033[00m\] $ "

# Causes bash to append to history instead of overwriting it so if you start a new terminal, you have old session history
shopt -s histappend
PROMPT_COMMAND='history -a'

# Alias's to modified commands
alias apt-get='sudo apt-get'

# Change directory aliases
alias home='cd ~' 
alias cd..='cd ..'
alias ..='cd ..'
alias ...='cd ../..'
alias ....='cd ../../..'
alias .....='cd ../../../..'

# If set, minor errors in the spelling of a directory component in a cd command will be corrected. 
# The errors checked for are transposed characters, a missing character, and one character too many. 
# If a correction is found, the corrected file name is printed, and the command proceeds. 
# This option is only used by interactive shells.
shopt -s cdspell
