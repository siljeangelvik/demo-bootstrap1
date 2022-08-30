# demo-bootstrap1


---

**Terminal commands:**  
--style=compressed  
--watch

**run command:** sass --watch  
_example:_   
sass --watch app/sass/partials:public/stylesheets
sass --watch input.scss output.css
sass --watch app/sass:public/stylesheets
sass --watch scss/custom.scss:css/style.css
sass --style=compressed scss/custom.scss:css/style.css
---

## Directory Structure:

###app
index.html  
**/ sass**  
input.scss  
**/ partials**  
_buttons.scss  
_base.scss  
_colors.scss  
_reset.scss  
_mixins.scss


**public**  
**/ stylesheets**  
output.css


--
###Cheat Sheet
**check local branch names**  
`git branch`  
**check remote branch names**  
`git branch -r`  
**check local and remote branch names**  
`git branch -a`  
**check detailed information of commits**  
`git branch -vv` or `git branch -vva`  
**switch to existing branch**  
`git checkout <branch-name>` or `git switch <branch-name>`
**check status**  
`git status`  
**commit and add message to the progress**  
`git commit -m "commit message"`  
**create and navigate to new branch**  
`git checkout -b <new-branch>`  or `git switch -c <new-branch>`
**push from origin to another branch**  
`git push -u origin <branch>`  
**undo a commit**  
`git reset HEAD~`




Resources:
* https://devconnected.com/how-to-switch-branch-on-git/
* https://cli.github.com/manual/gh