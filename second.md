# Github-第二讲
### 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？

1. 新存储库（创建一个新库）
2. 导入存储库（将项目从其他版本控制系统导入所有文件，包括修订历史纪录）
3. 新要点
4. 新组织（注册自己的团队）

### 2.如何能将仓库中的html文件直接解析成页面？

直接在github上预览html网页效果的方法是：

新建一个gh-pages分支，然后就可以在 yourname.github.com/repo 地址查看gh-pages的页面了。

仓库->setting->master branch

### 3.如何删除仓库

到个人中心，点击个人账号->点击repositories仓库，选择要删除的项目->code这一行导航栏最后一个setting->下拉页面到最下面，点击detele this repositoy按钮进行删除

### 4.bash是什么操作系统的命令
linux系统

### 5.pwd是什么命令
linux 查看当前工作目录的完整路径（打印当前工作目录）

### 6.cd是什么命令
linux 改变目录；cp copy

### 7.echo是什么命令
linux dos 打印，输出

### 8.配置git用户名的命令
$ git config[--global]user.name"[name]"

### 9.配置邮箱的命令
$ git config[--global]user.email"[email address]"

### 10.命令行换行方式
/
### 11.命令行终结方式
ctrl+c
### 12.使用命令行比gui方式有何优势
1. 文件管理
2. 列出文件和属性
3. 使用crontab调度作业
4. 安装软件包
5. 图形界面工具功能不完整
### 13.提交到本地仓库时为什么有暂存区

### 14.新建代码仓库的命令
$ git init
### 15.git clone [url] 这个命令的作用是
下载一个项目和它的整个代码历史
### 16.添加指定文件到暂存区的命令
$ git add [file1][file2]...
### 17.删除工作区文件，并且将这次删除放入暂存区的命令
$ git rm [file1][file2]...
### 18.改名文件，并且将这个改名文件放入暂存区的命令
$ git mv[file-oriainal][file-renamed]
### 19.提交暂存区到仓库的命令
$ git commit -m[message]
### 20.直接从工作区提交到仓库的命令
$ git commit -a -m[message]
### 21.显示变更信息的命令
$ git status
### 22.查看历史信息的命令
$ git log
### 23.Commit的意义是
提交
### 24.Pull的意义是
往上
### 25.Push的意义是
往下