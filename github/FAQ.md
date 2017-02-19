GitHub使用FAQ

# 如何不同步本地某些文件

编辑和管理本地的.gitignore文件，增加需要忽略的内容，例如增加以下内容来忽略.Archive文件夹下及其所有内容
>.Archive/*

日期：2017-02-19 11:30:31

# 如何删除 github 上已有文件或文件夹

在本地的github软件中操作，对指定的repo进行命令行操作

1. git rm --cached filenameordirname
1. git commit -m "注释说明"
1. git push origin

原理：需要删除github上的 **.DS\_Dtore** 存储的信息
参考：[如何删除github上的文件](http://www.jianshu.com/p/06c32daefe0f)

日期：2017-02-19 11:28:46

