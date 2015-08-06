# Bash

**Usefull aliases** 

```
alias root='cd /'
alias me='cd ~'
alias sublime='cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User'
alias aliaschange='vim ~/.bash_profile'
alias aliasrun='. ~/.bash_profile'
```


**After new commands are added run...**

```
 . ~/.bash_profile
```

**Add scripts**

1. Add [filename].sh in ~/bin
2. Add the code
3. Run the code . ~/[filename]

**Useful script**

````
#! ~/bin/bash

echo "$(tput setaf 3)Setting up [project name]... $(tput sgr 0)"
cd ~/[directory]
echo "$(tput setaf 3)Git status... $(tput sgr 0)"
git status
echo "$(tput setaf 3)Open localhost... $(tput sgr 0)"
open -a "/Applications/Google Chrome.app" 'http://localhost:3000'
echo "$(tput setaf 3)Open sublime [project name]...$(tput sgr 0)"
sublime 
echo "$(tput setaf 3)Starting rails server...$(tput sgr 0)" 
rails s
```
