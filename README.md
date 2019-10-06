# git常用操作指令

### 远程仓库链接方式有两种：

#### HTTP方式：

```
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/tianshun66/tsGit.git
git push -u origin master
```

#### SSH方式：

```
git remote set-url origin git@github.com:tianshun66/tsGit.git
git push -u origin master
#后期提交时
git push origin master
```

#### 克隆远程仓库：

```
 git clone git@github.com:tianshun66/tsGit.git
```

### 拉取远程仓库：
```
 #方式一:
 git fetch origin
 git merge origin/master
 
 #方式二:
 git pull origin master
```
