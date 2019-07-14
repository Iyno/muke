现在总结一下今天学的两点内容：
初始化一个Git仓库，使用git init命令。
添加文件到Git仓库，分两步：

使用命令git add <file>，注意，可反复多次使用，添加多个文件；
使用命令git commit -m <message>，完成。




小结
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令git push -u origin master第一次推送master分支的所有内容；
此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；


从现在起，只要本地作了提交，就可以通过命令：

$ git push origin master


add--commit--push--增加、提交、最后推送到远端
➜  muke git:(master) ✗ git add index.html
➜  muke git:(master) ✗ git commit -m "index.html"
➜  muke git:(master) ✗ git push origin master