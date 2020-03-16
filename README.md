# takeda-doc
takeda-doc

本文只说明命令行方式更改/提交文件方法，UI方式可根据个人喜好自行下载软件来搞。命令行可以用cmd，也可以用git bash，但是总之这个git.exe是要下载的。

1.选择适当文件夹，作为工作文件夹，执行命令git clone https://github.com/liliad1/takeda-doc.git复制项目到本地。

2.第一步成功后，在文件夹内会生成takeda-doc文件夹，我们要编辑的文件便在此处。

3.编辑文件（第一次不用，以后在编辑之前最好执行一遍git pull，拉取最新文件来编辑，以免有版本冲突）。

4.编辑结束后关闭文件，执行git add TAKEDA_WorkItemList-WBS.xlsx，再执行git commit -m 'updated' TAKEDA_WorkItemList-WBS.xlsx，引号中间是注释，可适当修改。

5.执行git push origin master将文件提交到远程仓库，一次修改就完了。

第一次复制项目的时候需要用到第一步，以后从3开始执行即可。
