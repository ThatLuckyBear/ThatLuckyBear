## Git & Linux Help Doc
Tips and notes for using git through Linux to work offline.

### Goals: 
- simplify commands and make shortcuts where possible 

## To-Do
- figure out what the process is to automate uploading to GitHub when internet arrives (I saw this but I can't find the reference I saw it in before and don't know enough terminology looks like an addon...)
- set up shortcut test for directories and URLS so you can type less (check "git -help tutorial" under collaboration)  

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
- If you forget to -m you can get out by pressing ESC > SHIFT+ZZ. Escape closes the typing to enable shortcuts and shift+ZZ saves and exits.
- always pull before pushing "-git pull" and then "-git push"

### Commands (Working)
ensure you're in the correct directory if there's an issue.

> git commit -a -m "blurb": saves the changes you've made locally so they can be uploaded. -a expands where commit looks for changes to all files. -m "blurb" let's you skip the dialogue box that requests your commit message. 
> git pull: gets all changes from GitHub
> git push: pushes all changes that have been committed to GitHub
> git clone github@github.com/USER/REPO: clone with SSH, https will prompt for password but it doesn't work because it's not set up

### Shortcuts Guide
to create shortcut:
> alias custom_command='original_command'

If you want to not load the alias every time go to your home directory, view hidden files, and edit .bashrc and append:
alias custom_command='original_command'
