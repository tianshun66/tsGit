# git常用操作指令
## 关联远程仓库HTTP方式

```
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/tianshun66/tsGit.git
git push -u origin master
```

### 关联远程仓库SSH方式

```
git remote set-url origin git@github.com:tianshun66/tsGit.git
```

