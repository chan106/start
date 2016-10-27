# start
This is a getting started project for git and github learner !    这是一个git/github新手的练习项目。


# Tools
* notepad++  文本编辑器
* xmind      思维导图工具
* fiddler    http抓包分析工具
* Clover     windows上的标签式资源管理器
* wireshark  TCP/UDP抓包分析工具
* Everything windows上的全局搜索工具
* Navicat for mysql     mysql管理工具
* redis desktop manager redis管理工具（windows）
* filezilla             文件上传下载(ftp,sftp)
* chrome extension : postman  http抓包分析
* firefox plugin   ：HttpRequester, Temper data, poster , live http headers   http抓包分析

# Git getting started 
检出代码：
> git clone https://github.com/venturezebra/start

创建分支（在远程创建）：
> git checkout -b start_v0.1_yang origin/master
> 
> git push origin start_v0.1_yang

在本地编写代码，加入版本控制(如果有空文件夹需要加入，记得在空文件夹里面创建一个空的 .empty 文件，否则git add命令会忽略空文件夹)：
> git add *

提交到本地：
> git commit -m "创建新的版本分支并第一次提交以初始化"

推送到远程：
> git push origin start_v0.1_yang 
