#  github问题集
## 问题集2
1.	个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？  
New repository创建仓库 import repository导入仓库 新的代码 新的组织
2.	如何能将仓库中的html文件直接解析成页面？  
打开仓库，点击settings 点击GitHub Pages，source中选择master branch，然后save保存
3.	如何删除仓库  
Settings中Danger Zone选项中Delete this repository
4.	Bash是什么操作系统的命令  
大多数Linux系统以及Mac OS X
5.	Pwd是什么命令  
在Linux层次结构中，想要知道当前所处的目录，可以用pwd命令，该命令显示整个路径名。
6.	Cd是什么命令  
change directory(改变当前工作目录)
7.	Echo是什么命令  
打印输出
8.	配置git用户名的命令  
git config --global user.name “guwenjia”
9.	配置邮箱的命令  
git config --global user. email “1023478561@qq.com”
10.	命令行换行方式  
\
11.	命令行终结方式  
ctrl+c

12.	使用命令行比GUI方式有何优势  
速度快，使用便捷

13.	提交到本地仓库时为什么有暂存区  
暂存区: 我们通过$ git add ./*/*Xxx/Xxxx* 添加的修改,都是进入到暂存区了,肉眼不可见 通过 $ git status  可以看到修改的状态
修改只能在被add 到暂存区以后才能被提交

14.	新建代码仓库的命令  
git init demo
15.	git clone [url] 这个命令的作用是：  
克隆了一个仓库而不是简单的拷贝了文件下来，还保存了有关仓库的信息，基本就是克隆出了一个小的本地仓库。
16.	添加指定文件到暂存区的命令  
git add
17.	删除工作区文件，并且将这次删除放入暂存区的命令  
git rm file  // 从git版本库中删除文件
18.	改名文件，并且将这个改名文件放入暂存区的命令  
git mv [file-origin][file-renamed]

19.	提交暂存区到仓库的命令  
$ git commit -m "comment"  // 将暂存区的修改提交到仓库 后面添加上有意义的注视信息
20.	直接从工作区提交到仓库的命令  
git commit -a -m [message]
21.	显示变更信息的命令  
git status
22.	查看历史信息的命令  
git log  // 查看git的commit信息,每次提交的信息包括注视在内,从最新提交到最久提交
23.	Commit的意义是  
comiit 是将本地修改保存到本地仓库中  
24. Pull的意义是  
	取回远程仓库的变化
25. Push的意义是  
git push 将本地仓库修改推送到服务器上的仓库中

## 问题集3
1. MarkDown是什么？
Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。
2. MarkDown的特点？
兼容HTML 在线观看 平台支持 排版样式简单

- 专注你的文字内容而不是排版样式，安心写作。
- 轻松的导出 HTML、PDF 和本身的 .md 文件。
- 纯文本内容，兼容所有的文本编辑器与字处理软件。
- 随时修改你的文章版本，不必像字处理软件生成若干文件版本导致混乱。可读、直观、学习成本低。

3. MarkDown的用途？
轻松的导出 HTML、PDF 和本身的 .md 文件。
IT人士：写日志 技术文稿 记录代码片段 撰写文档

4. MarkDown的编辑工具有哪些？
Mou  Sublime Text 3  简书  Ulysses  Byword 

5. MarkDown的区块元素和区段元素分别包含哪些？

区块元素：段落和换行 标题 区块引用 列表 代码区块 分隔线

区段元素：链接 强调 代码 图片

