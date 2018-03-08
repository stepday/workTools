# workTools
工作种日常使用的一些东西整理和搜集

``` 
svn常用操作指令
1、强制切换某个目录的svn仓库地址
   svn switch --relocate 旧仓库svn地址  新仓库svn地址
2、签出仓库的时候如何切换用户名
   很多时候当我们服务器上签出仓库的是回提示无权限，是因为默认的svn用户不是自己，很简单的做法就是带上自己的svn用户名，如下所示：
   svn --username=yourname checkout svn_path  local_path
```
