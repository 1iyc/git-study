# setting global user name and email

$ git config --global user.name "yiyc-kr"
$ git config --global user.email "yiyc.kr@gmail.com"

# setting for specific repository (in repo)

$ git config user.name "yiyc-kr"
$ git config user.email "yiyc.kr@gmail.com"

# git lg

$ git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
