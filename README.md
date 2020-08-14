# DayWork

1.新建repository

2.进入github repository 项目

3.在本地项目根目录打开git Bash（也可以先进入git bash在使用找到项目），接下来就是输入命令了

4.touch README.md //新建说明文件

5.git init //在当前项目目录中生成本地git管理,并建立一个隐藏.git目录

6.git add . //添加当前目录中的所有文件到索引

7.git commit -m "first commit" //提交到本地源码库，并附加提交注释

8.git remote add origin https://github.com/chape/test.git（GitHub中仓库的ssh地址） //添加到远程项目，别名为origin

9.git push -u origin master //把本地源码库push到github 别名为origin的远程项目中，确认提交
