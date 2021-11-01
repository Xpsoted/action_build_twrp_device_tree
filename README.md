# TWRP Device Tree生成工具
- 这个工具怎么用？
- 1.首先你要搞到你的设备任意一个可以开机系统的
- boot.img AB分区 
- recovery.img 除了AB分区以外的所有分区 

-----

- 2.将这个仓库fork到你的用户名下

-----

- 3.将recovery.img或boot.img上传至一个可以提供直链下载的位置，这里我推荐直接将img文件上传至这个仓库，然后点进去点view raw，来获取直链

-----

- 4.点击actions － make twrp device － run workflow，然后在那个链接框里面输入你刚刚获取的直链

-----

 - 5、填写完成后点击 'Run workflow' 开始运行

-----
## 编译结果
- 可以在 [Release](../../releases) 下载

## 看不懂想要图文教程?
- 看看隔壁那个用github编译twrp教程，与这个大同小异端
- https://github.com/Xpsoted/Action-Recovery-builder/blob/main/README.md
