# myjs
————————————————

在目录下初始化本地仓库
$ git init

##添加要push到远程仓库的文件或文件夹到本地仓库
$ git add test_project.txt

#-m 添加注释
$ git commit -m ‘first commit’

##testlink 本地仓库的自定义名称 连接为gihub上仓库地址
$ git remote add testlink https://github.com/NerlCheng/demotest.git

同步本地仓库push到远程仓库
git push -u testlink master

后续更新步骤
git init 将文件夹设置为本地仓库
git remote add origin git@github.com:yangxionghua/temaiApp.git  将本地仓库与github仓库进行关联
git pull origin master  将GitHub上仓库的内容pull到本地仓库
git add xxx文件名字 添加文件到本地库
git commit -m “写注释” 提交文件到本地库
git push origin master 上传文件
