# Vim for Advanced User

Simple:

  Basic:

- ^E scroll the window down.
- ^Y scroll the window up.
- ^F scroll down one page.
- ^B scroll up one page.
- H move cursor to the top 0f the window.
- M move cursor to the middle of the window.
- L move cursor to the bottom of the window.
- h moves the cursor one character to the left.
- j moves the cursor down one line.
- k moves the cursor up one line.
- l moves the cursor one character to the right.
- 0 moves the cursor to the beginning of the line.
- $ moves the cursor to the end of the line.
- w move forward one word.
- b move backward one word.
- G move to the end of the file.
- gg move to the beginning of the file.
- `. move to the last edit.


  Editing Vim:

- d starts the delete operation.
- dw will delete a word.
- d0 will delete to the beginning of a line.
- d$ will delete to the end of a line.
- dgg will delete to the beginning of the file.
- dG will delete to the end of the file.
- u will undo the last operation.
- Ctrl-r will redo the last undo.


  Searching and Replacing:

- /text search for text in the document, going forward.
- n move the cursor to the next instance of the text from the last search. This will wrap to the beginning of the document.
- N move the cursor to the previous instance of the text from the last search.
- ?text search for text in the document, going backwards.
- :%s/text/replacement text/g search through the entire document for text and replace it with replacement text.
- :%s/text/replacement text/gc search through the entire document and confirm before replacing text.


  Copying and Pasting:

- v highlight one character at a time.
- V highlight one line at a time.
- Ctrl-v highlight by columns.
- p paste text after the current line.
- P paste text on the current line.
- y yank text into the copy buffer.


  Save and Quit:

- `:w` to write the file.
- ZZ to quit vim. (as `:q!`)


### further

**text objects and motions**

w - words

s - sentences

p - paragraphs

t -tags

a - all

i - in

t - 'til

f - find forward

F - find backward

**Commands**

d - delete (also cut)

c - change (delete, then place in insert mode )

y - yank (copy)

v - visually select

Usages : [Commands] [text objects]

example:

`diw` delete in word

`caw` change all word

`yi)` yank all text in parentheses

`di[` delete in bracket

`dt ` delete until space

or `dt.` delete until dot

`va'` select inside ''

`.` repeat last Command

More Commands:

- dd/yy - delete/yank the current line.
- D/C - delete/change until end of the line.
- ^/$ - move to the beginning/end of the line.
- I/A - move to the beginning/end of the line and insert.
- o/O - insert new line above/below current line and insert.
- p/P - paste below/above the line.
- `:earlier 2m` will be your file as 2 min before.


**Macro**

- q{register} (e.g. qw)
- (do things)
- q

play a Macro

- @{register} (e.g. @W)
- @@ play last macro

view a Macro

- `:registers` - view macros
-   reg

appending a macro

- q{register}...q 



**marker**

- m{register} to mark the position.
- `{register} to go to the mark.

**delete a mark**

- `:delmarks a` - delete selected mark
- `:delmarks !` - delete all marks (lowercase)


