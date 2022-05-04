# zaojia
github操作步骤
建一个本地仓库
git init
克隆项目
git clone git@github.com:jiashudong/zaojia.git
添加文件
git add README.md
添加提交信息
git commit -m "first commit"
将当前分支改为main
git branch -M main
关联远程仓库
git remote add origin git@github.com:jiashudong/zaojia.git
推送至远程仓库
git push -u origin main


配置本地账户信息
查看配置信息：git config -l
添加邮箱：git config --global user.email "jiashudong"
添加用户名：git config --global user.email "907425467@qq.com"
