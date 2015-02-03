# Coding House Tips & Tricks

README with tips and tricks to improve and find more efficients ways of working with our environments.

# Command Line Tips

I recommend using aliases to access your main folder faster and moving around CLI faster.

You can access aliases using:

```
vi ~/.files/.aliases
```

You can then add your alias using the following format:

```
alias NAME_OF_ALIAS="COMMAND_TO_RUN"
```
i.e.
```
alias cdhome="cd Documents/Main/"
```

To open Brackets using Command Line you can add the following alias:
```
alias brack="open -a 'Brackets'"
```
Then in Command line you can use brack to open any file
```
brack app.js
```
Here are a few aliases for listing files in a directory:
```
alias ll='ls -al'
alias la='ls -A'
alias l='ls -CF'
```
Here is a list aliases for various Git commands:
```
alias g='git'
alias ga='git add -A'
alias gb='git branch -a'
alias gc='git commit -v -m'
alias gca='git commit -a -v'
alias gco='git checkout'
alias gd='git diff'
alias gds='git diff --staged'
alias gdh='git diff HEAD'
alias gsh='git push'
alias gll='git pull'
alias gpr='git pull --rebase'
alias gst='git status -sb'
alias gap='git add -p'
alias grc='git rebase --continue'
alias gfa='git fetch --all'
alias gw='git branch -a --contains'
alias gld='git log --decorate --oneline'
```
