# Introduction


gitbook 的基本用法非常简单，基本上就只有两步：

- 使用 gitbook init 初始化书籍目录

   gitbook init

README.md 和 SUMMARY.md 是两个必须文件，README.md 是对书籍的简单介绍

- 书籍目录结构创建完成以后，就可以使用 gitbook serve 来编译和预览书籍了

    gitbook serve

gitbook serve 命令实际上会首先调用 gitbook build 编译书籍，完成以后会打开一个 web 服务器，监听在本地的 4000 端口。

现在，可以用浏览器打开 http://127.0.0.1:4000 查看书籍的效果。

gitbook 为我们创建了书籍目录结构后，就可以向其中添加真正的内容了，文件的编写使用 markdown 语法，在文件修改过程中，每一次保存文件，gitbook serve 都会自动重新编译，所以可以持续通过浏览器来查看最新的书籍效果。