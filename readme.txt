第一次学习git软件；git是一个版本控制开源的软件
是免费的。特别畅销的

1、安装git  window 下一步 下一步 即可；Ubuntu  ： sudo apt-get install git
2、创建目录    mkdir gitRepository 
3、查看目录    pwd  查看路径    ll -ah  可以查看隐藏目录
4、初始化git仓库
5、添加文件	   git add  file
6、添加备注    git commit -m "备注信息"
7、查看状态    git status 查看文件状态
8、查看文件修改内容   git diff
9、查看修改历史日志  git log
10、查看修改全部历史日志  git reflog
11、回退git reset --hard 版本号   git reset --hard HEAD^ 上一个版本号   git reset --hard HEAD^ 上上一个版本号   往上100个版本号  git reset --hard HEAD~100
12、工作区添加的目录就是工作区 、版本库 .git目录  暂存区 HEAD 指向master的指针
13、git commit只负责把暂存区的修改提交了，也就是第一次的修改被提交了，第二次的修改不会被提交。
14、
