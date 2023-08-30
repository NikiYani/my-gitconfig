# My .gitconfig

[user] </br>
  &nbsp; email = YanchenkovNS@?????.ru </br>
  &nbsp; name = Yanchenkov Nikita Sergeevich </br>
  &nbsp; username = YanchenkovNS </br>
  
[init] </br>
  &nbsp; defaultBranch = master </br>
  
[credential] </br>
  &nbsp; helper = cache </br>
  
[alias] </br>
  &nbsp; s = status </br>
  &nbsp; co = checkout </br>
  &nbsp; cob = checkout -b </br>
  &nbsp; del = branch -d </br>
  &nbsp; delf = branch -D    
  &nbsp; save = add -A && git commit -m </br>
  &nbsp; undo = reset HEAD~1 --mixed </br>
  &nbsp; res = reset --hard </br> 
  &nbsp; done = push origin HEAD </br>
  &nbsp; lg = log --pretty=format:\"%C(magenta)%h%Creset -%C(red)%d%Creset %s %C(dim green)(%cr) [%an]\" --abbrev-commit -8 --graph </br>
  &nbsp; br = branch --sort=-committerdate --format='%(color:reset)%(HEAD) %(color:green)%(objectname:short) %(color:yellow)%(refname:short)%(color:reset) - %(contents:subject) %(color:green)(%(committerdate:relative)) %(color:green)[%(authorname)]' </br>
  
[core] </br>
  &nbsp; excludesFile = ~/.gitignore </br>
