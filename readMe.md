The main plugin manager used is "vundle"
"git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim"
Running this git command setup the vundle plugin manage that then able to manage the other plugins

Only following steps are required :
1. create ~/.vimrc and copy the vimConfiguration script to it 
2. open vim and go to command mode then run ":PluginInstall"
Everything will be working now
## Plug_ins: 
list of plugins you can add more here in the same place and the source this file and run plugInstall command to get more

keyMapping:
this section maps various functionality to each key you can add your own key mapping in this section

Colorscheme:
section for various color and more can be added

this site is the source for this setup
https://dane-bulat.medium.com/vim-setting-up-a-build-system-and-code-completion-for-c-and-c-eb263c0a19a1

for YCM(YouCompleteMe) Installation:
Replace `sudo apt install build-essential python3-dev llvm-defaults` with 
```
sudo apt update
sudo apt install build-essential python3-dev llvm clang
```
