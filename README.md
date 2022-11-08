# ARCO LINUX SETUP AND SHORTCUTS : 

* use `lt` to list latest modified file/folder first through terminal. 
* Your arch is in a state(w.r.t to packages version) at each time. So : 
  * `-S` : when you want to install the package that is compatible with your current state. 
  * `Syu` : Upgrade all the packages version to the latest. So if you do `-Syu chrome` , it will fetch latest version of chrome & simulatenously upgrade all the packages in your machine to the latest. 

## GENERAL ARCO SHORTCUTS : 

### GLOBAL SHORTCUTS : 

* <ins>alt+Tab</ins> : Cycle through various tabs available. To land a particular tab, just leave the buttons there.
* <ins>alt+shift+Tab</ins> : Cycle through tabs in reverse order. 
<br>

* <ins>super+tab</ins> : Cycle through various opened applications. Various instances of the applications are clubbed into one. 
<br>

* <ins>super+n</ins> : Go to Right workspace. 
* <ins>super+alt+n</ins> : Go to Left workspace. 
* <ins>super+shift+n</ins> : Move the selected window to the Right Workspace. 
* <ins>super+ctrl+shift+n</ins> : Move the selected window to the Left Workspace. 
<br>

* <ins>super+p</ins> : Rofi Launcher. 
<br>

* <ins>super+alt+c OR alt+F4</ins> : close current active application. 
<br>

* <ins>super+alt+enter</ins> : Launch Terminal
* <ins>alt+space</ins> : Toggle scratchpad. 
<br>

### TMUX SHORTCUTS : 

* ctrl + S : Modifier key, use `esc` to exit the modifier mode. 
* While in Modifier Mode :
  *  `|` : Vertical Split. 
  *  `-` : Horizontal Split. 
  *  `c`(create) : adds new tab. 
  *  `n`(next) : toggle/switch to next tab. Current active tab is shown with `*`. 
* To keep highligted text for longer use `shift` while selecting. 
  
  










## GUIDE TO NVIM
### SHORTCUTS FOR NVIM:
  * <ins>ctrl+/</ins> Open build in terminal.
  * <ins>space+n+n (sequential)</ins> Open file explorer.
  #### FIND WORDS AND FILE
  * <ins>space+f+f</ins>  Find file.
  * <ins>/<text> (in command mode)</ins> Find in file.
  * <ins> n (in command mode) </ins> GO to next match.
  #### REPLACE WORDS
 
  
  #### SELECT TEXT TO COPY
  * <ins>v (in command mode)</ins> Visual mode. Words selection.
  * <ins>shift+v (in command mode)</ins> Visual mode. Line selection.
  #### COPY THE SELECTED TEXT
  * <ins>y (in command mode)</ins> To copy after you select the text in the Visual mode.
  #### PASTE THE COPIED TEXT  
  * <ins>p (in command mode)</ins> To paste the copied content after the cursor.
  * <ins>shift+p (in command mode)</ins> To paste the copied content before the cursor.
  #### UNDO AND REDO
  * <ins>u (in command mode)</ins> To undo the changes.
  * <ins>U</ins> : To undo and restore the whole line. 
  * <ins>ctrl+r(in command mode)</ins> To redo the changes.
  #### USEFUL TIPS FOR CODERS
  * <ins>g+d (in command mode)</ins> Go to function defintion.
  * <ins>ctrl+o (in command mode)</ins> Return back.
  * <ins>space+k+c (in command mode)</ins> Compile.
  * <ins>space+k+r (in command mode)</ins> Run.
  #### SPLIT SCREEN
  * <ins>:sp (in command mode)</ins> Split screen horizontally.
  * <ins>:vsp (in command mode)</ins> Split screen vertically.
  * <ins>ctrl+v (in file explorer)</ins> Split screen vertically.
  
  
  ### Deleting Things : 
  * <ins>x</ins> : To delete the character at the cursor position. 
  * <ins>dw</ins> : To delete until the start of the next word, excluding its first character. 
  * <ins>de</ins> : To delete to the end of the current word. 
  * <ins>d$</ins> : To delete from current position to the end of the line. 
  
  ### Counting and Quantifying motion: 
  * Nw : move cursor `n` words forward. 
  * ne : take cursor to the end of `nth` word forward. 
  * 0 : take cursor to the beginning of the line. 
  
  ### Operating Lines : 
  * dd : To delete the entire line. 
  * 2dd : Delete two consecutive lines (including the current line). 
  
  
  

