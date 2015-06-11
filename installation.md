# SmartHosts使用教程 #
## Windows ##

**您可以使用
[客户端](https://smarthosts.googlecode.com/svn/trunk/clients/smarthosts_win.exe)
来更新hosts文件。**

如果客户端不能使用，您可以使用以下方法手动更新：

1.在hosts文件一栏中对应的链接右键，选择“链接另存为……”

2.保存hosts文件，覆盖
```
%windir%\system32\drivers\etc\hosts
```

3.完成

## Linux ##

您可以添加源
""
或使用客户端
""
来更新您的hosts文件，
或直接执行如下命令（脚本下载）
```
sudo cp /etc/hosts /etc/hosts.bak
sudo wget https://smarthosts.googlecode.com/svn/trunk/hosts -O /etc/hosts
```

## Mac OS X ##
您可以使用客户端
""
来更新您的hosts文件，或直接执行此脚本：
""