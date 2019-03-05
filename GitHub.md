#将Gitbook电子书部署到GitHub上





[该电子书的地址](https://wangzilong1997.github.io/make-a-gitbook/)





<font color="red">仅供参考出错请查链接插件配置<font>

##gh-pages 分支保存书籍编译后的 HTML 文件 

master 分支保存书籍的源码
###创建一个仓库

创不创建都随你

###进入你的gitbook文件夹
####1.git init
####2.git remote add origin https://github.com/wangzilong1997/make-a-gitbook.git
####3.git add .
####4.git commit -m -a "sixsixsix"
####5.git push -u origin master

##gh-pages 分支保存书籍编译后的 HTML 文件 
####1.进入你gitbook自动编译完成的一个文件夹_book
####2.初始化 git init
####3.创建一个新的分支 git checkout -b gh-pages
####4.git remote add origin https://github.com/wangzilong1997/make-a-gitbook.git
####5.git add .
####6.git commit -a -m ""
####7.git push -u origin gh-pages


完成GitHub上面的部署，可以在setting中找到该电子书的地址（该伟大的电子书的地址在上面）
