# git-zero

# git add
>
> git add .

# to reset from staging to working dir
>
> git reset head osama.rtf

# to commit
 >
 > git commit -m "Created the main project structure"

# push from local to remote
 >
 > git push

# view all config
 >
 > git config -l
 > git config -l --show-origin

# add the mail for config
 >
 > git config --global user.name "haytham"
 > git config --global user.email "<haytham.mo7amed@gmail.com>"

# edit with gui
 >
 > git config --global --edit

# generate key
 >
 > ssh-keygen -t rsa -b 4096 -C "haytham.mo7amed@gmail"

# put the ssh key at the github and test with this command
 >
 > ssh -T <git@github.com>

# make alias
 >
 > git config --global alias.st status \
 > git config --global alias.br barnch \
 > git config --global alias.cm "commit -m"

# branches
>
> git branch \
> git branch scroll \
> git checkout scroll \
> git branch -d scroll \
> git checkout -b scroll2 \
> git branch -m scroll-rename \

# stash
>
> touch file \
> git add . \
> git stash \
> git stash list \
> git stash pop  \

# advanced stash
>
> touch osx.txt \
> git add osx.txt \
> git stash save "OSX text" \
> git stash list \
> git stash pop \
> git stash apply \
> git stash pop stash@{2} \
> git stash drop \
> git stash drop stash@{2} \
> git stash show \
> git stash clear \

# Restore And Clean
> git restore --staged new.txt \
> git clean -n \
> git clean -f \

# Resetting The Head
> git reset --hard d145454sd54  

# Ignoring Files And Directories
> touch .gitignore
> git add -f fil.txt

# Tagging And Releasing Part 1
> git tag 
# lightwight tag
> git tag v0.1 \ 
> git push origin v1.0 

# annotated Tag
> git tag -a v2.0 -m "our project => second version"

# Tagging And Releasing Part 2
> git tag -l "v1.*"

# delete tag
> git tag -d v1.0 \
> git tag -d v2.0