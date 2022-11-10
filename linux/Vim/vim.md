#git@github.com:opentable/service-ot-frontdoor-config.git Shorcuts
## Move between vim windows
ctrl w l and ctrl w h to move back and forward
ctrl w v : split vertically
ctrl w s : split horizontally

# Links for review
* https://www.freecodecamp.org/news/vimrc-configuration-guide-customize-your-vim-editor/

#Link for the first vimrc with lua 
https://github.com/ThePrimeagen/.dotfiles/blob/master/nvim/.config/nvim/lua/theprimeagen/init.lua

Open multiple files in tabs with vim
vim -p files
vim -o files also open several files but hidden

S for change the hole line

shift v will select the whole line, and if you yank it will create a new line

# Motions
_ goes to the first not empty character
$ goes to the last character

f + character goes to that forward character
T + character goes to that backward character
t + character goes one character previous that one
if you press , or ; after move with f you can repeat back and forward the motion

## Check how to use this motions with other commands like delete, yank or visual

:reg for see things that you have in your register
Also you can set a specific register value git " + number

to change between open files in buffer use b + number also bn = next file and bp = previous
:b + tab its like alt tab or ctrl tab

check :h motion and registers

For completion you can use control n
C-xC-f File paths
C-xC-d Definition
C-xC-j Tags
C-xC-i Keywords
C-xC-l Lines

With key - s the blame git plugin sets the git commit text

 
 Check how store vim sessions to save state

 Check this repo with the configs of nvim
 https://github.com/nexxeln/nvim

 Ctrl v to enter in block mode
 Check this repo from the vim+tmux video
 https://github.com/nicknisi/dotfiles

# To format json with JQ
 - :%!jq . 

# Copy thins from outside vim using registers
"<Letter>y
And for paste just do "<Letter>p


In visual mode with a couple of things selected you can use something like this to edit several lines
: '<.'>norm I<text to insert at the begining of the line> '>
This is related to :norm commands

# Go to file or go to URL
1. gf go to the file if you are in a relative or absolute path in your file system
2. gx go to URL in browser

# Playing primagean vim game
docker run -it --rm brandoncc/vim-be-good:latest
