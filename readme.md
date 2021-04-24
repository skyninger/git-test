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
