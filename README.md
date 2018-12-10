# androidStudio


*********提交github仓库操作********
步骤：
1.cd 到你要提交代码所在的文件夹
2.git init
3.git add .
4.git commit -m "description"
这个时候自己去github上创建自己的Repository。
重点来了，将本地的仓库关联到github上
5.git remote add origin "git链接"		//将仓库命名为origin         
6.git push -u origin master		//同效于 git push -u 仓库网址

【添加远程仓库的方法】
要添加一个新的远程仓库，可以指定一个简单的名字，
以便将来引用，运行 git remote add [shortname] [url]

【下载代码的方法】
cd到你想放代码的文件夹，然后直接在git上使用命令git clone "url"
这个时候就能在本地文件夹上看到下载的代码

如果遇到下面这个错误说明你更改过github网站修改过README.md文件，要先更新服务器上的变化才能提交。
 ! [rejected]        master -> master (fetch first)
 解决方法：先git pull再git push就行
