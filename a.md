1.设置用户名，邮箱
git config --global user.name "yourname"
git config --glocal user.name "blackironman@163.com"
2.pwd 查看当前的工作路径
3.cd ..  返回上级
4.cd c:\ github返回C盘目录
5.mkdir test 创建文件夹test
6.cd test 进入文件夹test
7.git init 创建仓库
8.ls 查看当前目录下的文件
9.git status 查看当前状态
10.git add readme.txt
11.git commit -m "提示信息"
12.git diff 查看修改的信息
13.git reflog 查看所有的版本信息
14.git reset --hard HEAD^ 回退到上一个版本

http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137628548491051ccfaef0ccb470894c858999603fedf000

生成ssh-key 
ssh-keygen -t rsa -C "youremail@example.com"

添加远端仓库(用origion 代替 后面的地址)
git remote add origion git@github.com:blackironman/gitstudy.git
推送到远端
git push -u origion master
下载github上的文件
git clone 地址(github上的SSH地址)：git@github.com:blackironman/study.git
