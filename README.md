# dotfiles

Instalando Zsh - https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH

FiraCode - https://github.com/tonsky/FiraCode/wiki/Linux-instructions#installing-with-a-package-manager

Java - https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-18-04

Android Studio - https://developer.android.com/studio/archive

How to install Android Studio on Ubuntu - https://askubuntu.com/questions/634082/how-to-install-android-studio-on-ubuntu

NVM and NODE - https://linuxize.com/post/how-to-install-node-js-on-ubuntu-18.04/#installing-nodejs-and-npm-using-nvm

More about dotfiles - https://github.com/webpro/awesome-dotfiles

.gitconfig = 


```gitignore
# This is Git's per-user configuration file.
[user]
	name = velosobr
	email = linoc.veloso@gmail.com
[core]
	editor = code --wait

[alias]
c = !git ad -all && git commit -m
s = !git status -s
l = !git log --pretty=format:'%C(blue)%h%C(red)%d  %C(white)%s - %C(cyan)%cn, %C(green)%cr'
t = !sh -c 'git tag -a $1 -m $1'
amend = !git add --all && git commit --amend --no-edit
```
