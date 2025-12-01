初始化Git
```
git init
```

把所有文件加入 Git
```
git add .
```
查看状态
```
git status
```
提交（Commit）
```
git commit -m "first commit"
```
链接远程仓库
```
git remote add origin https://github.com/Max-GPT/IT-Notes.git
```
检查是否成功
```
git remote -v
```
上传到Github
```
git push -u origin main
```
`-u` = --set-upstream 

意思是以后这个本地分支（main）默认对应那个远程分支（origin/main）

`origin`远程仓库的名字

`main`要推送的分支名。