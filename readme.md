### 1、初始化本地Git存储库
```Bash
git init
```

### 2、创建远程存储库的本地副本
```Bash
git clone ssh://git@github.com/[username]/[repository-name].git
```

### 3、检查状态
```Bash
git status
```

### 4、将文件添加到暂存区
```Bash
git add [file-name.txt]
```

### 5、将所有新文件和更改过的文件添加到登台区域
```Bash
git add -A
```

### 6、提交更改
```Bash
git commit -m "[commit message]"
```

### 7、删除文件（或文件夹）
```Bash
git rm -r [file-name.txt]
```

### 8、列出分支（星号表示当前分支）
```Bash
git branch
```

### 9、创建一个新分支
```Bash
git branch [branch name]
```

### 10、删除分支
```Bash
git branch -d [branch name]
```

### 11、创建一个新分支并切换到该分支
```Bash
git checkout -b [branch name]
```

### 12、克隆一个远程分支并切换到该分支
```Bash
git checkout -b [branch name] origin/[branch name]
```

### 13、重命名本地分支
```Bash
git branch -m [old branch name] [new branch name]
```

### 14、切换到分支
```Bash
git checkout [branch name]
```

### 15、将一个分支合并到活动分支中
```Bash
git merge [branch name]
```

### 16、将一个分支合并到一个目标分支
```Bash
git merge [source branch] [target branch]
```

### 17、将更改存储在不合适的工作目录中
```Bash
git stash
```

### 18、删除所有隐藏的条目
```Bash
git stash clear
```

### 19、将分支推送到你的远程存储库
```Bash
git push origin [branch name]
```

### 20、将更改推送到远程存储库
```Bash
git push
```

### 21、将本地存储库更新为最新的提交
```Bash
git pull
```

### 22、从远程存储库中提取更改
```Bash
git pull origin [branch name]
```

### 23、添加一个远程存储库
```Bash
git remote add origin ssh://git@github.com/[username]/[repository-name].git
```

### 24、查看更改
```Bash
git log
```

### 25、合并前预览更改
```Bash
git diff [source branch] [target branch]
```

### 26、查看历史版本
```Bash
git reflog
```

### 27、版本前进后退
```Bash
git reset [--hard|--soft] 版本号
git reset [--hard|--soft] HEAD^ （后退一次）
```
