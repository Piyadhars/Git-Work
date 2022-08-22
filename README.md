Am going to teach you how below command works better for OUR (developer) comfort

git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit

and then,
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"

and then

git lg instead of 'git log --oneline'

if(:)) {console.log("");}
else {AVOID IT( :( );} 

Vidly
API Documentation : https://documenter.getpostman.com/view/21337972/Uz5JJGEp