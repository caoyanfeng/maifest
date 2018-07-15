测试如何用Repo来下载多个git工程

参考：http://gavinliu.cn/2016/04/15/Git-%E4%BD%BF%E7%94%A8Repo%E7%AE%A1%E7%90%86%E4%BD%A0%E7%9A%84Git%E9%A1%B9%E7%9B%AE/

基本操作

初始化
1
repo init -u [url] -b [branch]
同步
1
repo sync
开始
1
2
# 所有项目都切换到某个分支
repo start [branch] --all
查看分支
1
repo branches
