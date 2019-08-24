- **提交本地新分支到远程**   
git push origin branchName
- **撤销git add**   
git status 先看一下add 中的文件    
git reset HEAD 如果后面什么都不跟的话 就是上一次add 里面的全部撤销了    
git reset HEAD XXX/XXX 就是对某个文件(夹)进行撤销了 
- **回退版本**   
git reset commitId --hard    
提交回退：git push origin HEAD --force   
--hard是直接回退到指定版本，它以后版本的提交记录会被全部删除   
--soft则会把它以后版本的修改都放进暂存区，适合回退以后的局部修改   
- **暂存修改**   
git stash   
git stash pop   
如果有新建的文件，要先git add file   
- **oh-my-zsh提供的git命令缩写**    
ga:  git add  
gcmsg:  git commit -m   
gcam:  git commit -a -m


