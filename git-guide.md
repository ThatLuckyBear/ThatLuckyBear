## Git & Linux Help Doc
Tips and notes for using git through Linux to work offline.

### Goals:
- access and update GitHub files offline with Chromebook 
- sync local with github version with as little overhead as possible

## To-Do
- set up remote to allow pushes from Chromebook
- figure out what the process is to automate uploading to GitHub when internet arrives (I saw this but I can't find the reference I saw it in before and don't know enough terminology)
- set up shortcut test for directories and URLS so you can type less (check "git -help tutorial" under collaboration) 
- test push commands like "git push origin" 


### Linux Tips:
- use "-cd ~/[directory]" to get into the right folder before using git commands
- When in an input / document field
     - i let's you type, esc exits typing to allow other keyboard commands 
     - shift + ZZ will save and exit commit message window
     - hjkl navigate like arrows if you need it 
     - ctrl+shift+c/v for copy paste access

### Git tips 
- use "-commit -a -m "[type message here]" to skip adding items to index and skip the message input window
- use "git -diff" to see if your changes are being detected before you commit
- always pull before pushing "-git pull" and then "-git push"
