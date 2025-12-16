echo "# git--" >> README.md #创建
git init    #git初始化
git add README.md   #将README.md加入暂存区
git commit -m "first commit"    #将暂存区提交上去，然后会自动创建branch
git branch -M main  #将原branch该为main
git remote add origin https://github.com/CliCliWi/git--.git #将link挂载到origin
git push -u origin main #将branch “main” 提交至origin