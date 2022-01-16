# 说明

由于之前一直使用VS Code中自带的Git管理工具，导致自己不会使用相关的命来行工具，遂写下次教程，相当于记录以下平时常用的git命令

# 本地仓库

## 初始化仓库

此操作会初始化一个空的 Git 仓库

```bash
git init
```

## 向仓库中添加文件

此操作将把当前目录中所有文件添加到仓库中

```bash
git add .
```

## 将文件提交到仓库

```bash
git commit -m "<提交说明>"
```

# 远程仓库

## 配置SSH访问Github

```bash
ssh-keygen
```

将生成的id_rsa.pub文件中的内容添加到github中，setting --> SSH and GPG keys --> New SSH Keys

## 添加远程仓库

```bash
git remote add origin git@github.com:yaaannn/git-test.git
```

## 向远程仓库提交文件

```bash
git push -u origin master
```

