# RenrenAlbumDownloader 2015

### 更新

1. 重写了登录、获取相册链接、获取照片链接的部分以适应人人v7版本
2. 新增获取“被圈照片”功能
3. 正确地跳过加密相册

### 功能

自动下载全部人人好友的相册

### usage

1、在目录下建立user.txt，填入以下内容（该文件不会已加入gitignore)

username='用户名'  
password='密码'  
cookie='可选，自己抓包获取cookie'  

2、（确保安装了Python解释器）运行/RenrenDownloader.py，保持网络通畅，然后泡一杯咖啡

3、在当前目录下的albums目录里可以看到所有好友的相册都被下载完成，并且自动按照姓名归档了。

