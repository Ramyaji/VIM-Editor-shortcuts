# VIM-Editor-shortcuts (Used as Text Editor) Vim/Vi/nano

cat filename.txt= to read content in filename.txt
cat > filename.txt ( to create and edit as new file)
cat is only used for editing small files it not helpful if we have many lines in file here come vim to help  1000's of lines easily

To check vim installed or not 
command -v vim
/usr/bin/vim

to check instruction 
man vim

vim filename.txt
I=Insert mode
Esc= command mode/operation mode(save copy delete cut etc)

save->
:q  quit without save file
:q! forcefully quit if we wrte content
:w   save file
:wq save and quit file
:wq! save quit forcefully

copy-> yy
3yy first 3 line p to paste
copy->esc + v (use arrow to select text to copy and press yy and p paste)
if want to paste 10 times press 10p
cut-> esc + x
Delete_> esc + dd
Delete-> esc + v for visual mode +use arrow to select text + press dd to delete


H to move cursor left
L right
j down
k up
M to go middle of file
shift H top of line page
shift+ l bottom of the line of page
/word 
to filter in esc mode


esc + :set number 
to visible line numbers

to check exact line no
esc + Line no +G
10G


Here's how to copy text in Vim/Vi editor:
Move the cursor to the beginning of the text you want to copy.
Press the "v" key to enter visual mode.
Use the arrow keys to select the text you want to copy.
Once the text is selected, press the "y" key to copy the text.


Esc+:q = to quit without save
Esc+:q! = to quit without save


Options & Shortcuts of vim-:

:q       (used for quitting out of vim editor)
:w       (used for writing out the current state in vim editor)
:wq      (save and quit vim editor)
:q!      (save without making changes in vim editor)
Esc      (go back to Command Mode)
i        (go to Edit Mode)
u        (Undo)
Ctrl+r   (Redo)
x        (delete a character)
dd       (delete a line)
7dd      (delete 7 lines)
dw       (delete a word)
yy       (copy the line)
p        (paste the line)
e        (move to next word)
r        (replace a letter)
:set number (set number on every line)
/search_keyword (search specific keyword on file)
