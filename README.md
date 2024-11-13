# git-zero

# git add
> git add .

# to reset from staging to working dir
> git reset head osama.rtf

# to commit
 > git commit -m "Created the main project structure"

# push from local to remote
 > git push

#view all config
 > git config -l
 > git config -l --show-origin

# add the mail for config
 > git config --global user.name "haytham"                  
 > git config --global user.email "haytham.mo7amed@gmail.com"

# edit with gui
 > git config --global --edit 

# generate key
 > ssh-keygen -t rsa -b 4096 -C "haytham.mo7amed@gmail"

 # put the ssh key at the github and test with this command
 > ssh -T git@github.com

 # make alias 
 > git config --global alias.st status \
 > git config --global alias.br barnch \
 > git config --global alias.cm "commit -m"

# branches
> git branch \
> git branch scroll \
> git checkout scroll \
> git branch -d scroll \
> git checkout -b scroll2 \
> git branch -m scroll-rename \
