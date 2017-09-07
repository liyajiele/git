关于git（版本控制协同开发工具）
-------
1.git是一款免费、开源的分布式版本控制系统，用于敏捷高校的处理任何或小或大的项目。
  git是Linus Tovralds为了帮助管理Linux内核开发而开发的一个开放源码的版本控制软件。<br>
2.GitHub是一个面向开源及私有软件项目的托管平台，因为只支持Git作为唯一的版本库格式进行托管。<br>
3.git指令<br>
  git init：初始化，让git接管<br>
  git status:监控状态<br>
  git add .:接管文件，.表所有<br>
  git diff:进行了什么修改（监控，对比）<br>
  git commit -m "111":形成版本，不会消失，一定要输入注释<br>
  git log:输出之前所有版本<br>
  git reset --hard xxxxx:之前的版本<br>
  git push origin master：上传库，主分支<br>
  git clone 地址：克隆到本地<br>
  git romote add origin http://:添加一个远程地址<br>
  git pull origin master:获取更新<br>
详细命令见廖雪峰的网站https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137621280731812dec22ecc9b44f4b2ca1c680f181a5b000<br>
4.问题解决<br>
  a.如上传时提醒没有邮箱地址及用户名，则输入<br>
        $  git config --global user.name "输入你的用户名"
        $  git config --global user.email "输入你的邮箱"<br>
  b.另一种上传方式：文件上传（可多个）<br>
5.遗留问题<br>
  a.对于上传时遇到的origin报错问题没有解决，所以采用文件上传。<br>
6.注意事项：<br>
  a.先建立仓库，把仓库克隆下来，文件放进去，再进行上传。<br>
7.Git 与 SVN 区别<br>
  GIT不仅仅是个版本控制系统，它也是个内容管理系统(CMS),工作管理系统等。<br>
  如果你是一个具有使用SVN背景的人，你需要做一定的思想转换，来适应GIT提供的一些概念和特征。<br>
   Git 与 SVN 区别点：<br>
        1、GIT是分布式的，SVN不是：这是GIT和其它非分布式的版本控制系统，例如SVN，CVS等，最核心的区别。<br>
        2、GIT把内容按元数据方式存储，而SVN是按文件：所有的资源控制系统都是把文件的元信息隐藏在一个类似.svn,.cvs等的文件夹里。<br>
        3、GIT分支和SVN的分支不同：分支在SVN中一点不特别，就是版本库中的另外的一个目录。<br>
        4、GIT没有一个全局的版本号，而SVN有：目前为止这是跟SVN相比GIT缺少的最大的一个特征。<br>
        5、GIT的内容完整性要优于SVN：GIT的内容存储使用的是SHA-1哈希算法。这能确保代码内容的完整性，确保在遇到磁盘故障和网络问题时降低对版本库的破坏。
