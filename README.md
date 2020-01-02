# git_learn
方式一：添加远程仓库
1.建立本地仓库
在文件夹下运行：git init
2.创建远程github仓库
直接在github网站上面创建
3.将本地仓库和远程仓库关联
本地运行：git remote add origin git@github.com:liruilingup/git_learn.git
本地内容推送：git push -u origin master #-u表示第一次推送，
本地commit后：git push origin master

方式二：从远程库克隆
一、创建远程github仓库
直接在github网站上面创建
二、克隆一个本地库
在本地文件夹运行：
git clone git@github.com:liruilingup/git_learn.git
三、进入git_learn文件夹
配置用户名
git config --global user.name "liruilingup"
git config --global user.email "1349932557@qq.com"
git add filename.txt #或者是 git add * 所有文件都放上去
git commit -m "add a file"


pycharm使用git：https://www.cnblogs.com/xiao-apple36/p/9084985.html

origin是默认的远程仓库名称

查看远程仓库信息:git remote -v

创建分支:git branch branchname

查看分支:git branch

把本地的某个 branch push 到远程仓库:git push origin <branch name>

获取远程修改到本地:git pull

本地创建并切换到远程分支对应的分支

当我们在github中创建了一个新的分支originbranch后，本地创建并切换到远程分支对应的分支时我们会输入以下命令：
git remote update
git fetch
git checkout -b originbranch origin/originbranch_name

git使用笔记：https://www.cnblogs.com/lpit/p/4913629.html
