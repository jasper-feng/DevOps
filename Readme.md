# Github 教程



#设置登录github的用户名和邮箱

git config --global user.name "asper-feng" 

git config --global user.email "jasper.feng@dyxnet.com"



#克隆项目

git clone https://github.com/jasper-feng/DevOps.git



#进入克隆到本地的文件夹 

cd DevOps

 

#创建一个 Readme.md文件

explorer .

#右键新建一个 文本文档，随便输入一些文字后保存，文件名改为 Readme.md



#添加待提交文件，点 代表目录下所有文件

git add .



#填写待提交文件的注释

git commit "add Readme.md file"

 

#提交代码到 远程地址（默认名称为origin） 的远程分支（master）

git push -u origin master

 ![result](https://github.com/jasper-feng/DevOps/blob/master/jpg_resource/result.jpg)

