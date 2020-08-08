## 网络协同编辑小例子

主要使用nodejs+websocket实现，可以实现不同房间共同编辑，代码比较粗糙，主要是为了实现[XYNotes](https://github.com/xygengcn/XYNotes)部分功能实现的小例子。


## 运行

```cmd

#1、先安装模块

npm i

#2、运行

npm start

#3、打开index.html文件即可，默认001房间

修改ws地址192.168.123.42:8090为127.0.0.1:8090即可

修改为本地ip可实现局域网设备编辑


#4、更改房间

index.html?1101 //表示1101房间

```