[![QQ](http://pub.idqqimg.com/wpa/images/group.png)](https://jq.qq.com/?_wv=1027&k=5HWgxBZ)

## 项目简介

OpenSumslack支持的接口Demo程序

- 整合weex-ui（官方weex）；
- OpenSumslack扩展的js接口，包含网络，地理坐标，存储，电话，聊天，注册登录，多媒体等众多API；
- 一些实例；

### 运行项目

```weex src --entry src/index.vue```

最新版本的weex应该运行:

```weex preview src --entry src/index.vue```


### 打包项目

```
weex compile src/*.vue dist
weex compile src/** dist
```

### 效果图

<img src='http://wxapps.sumslack.com/demo2/preview.png' alt='我的'/>

### 手机端调试

OpenSumslack安卓版下载：

![OpenSumslack安卓版下载](http://wxapps.sumslack.com/opensumslack/dl_opensumslack.jpg)
> 注：如果无法下载，直接在浏览器输入(http://wxapps.sumslack.com/opensumslack/openSumslack.apk)

OpenSumslack iOS版下载：

![OpenSumslack iOS版下载 - 扫一扫](http://h5.sumslack.com/pindazi.png)


### 常见问题

- sass报错
```npm rebuild node-sass --force```

- 端口被占用：

```
netstat -aon | findstr 8082  
taskkill /f -pid xxx
```

- 安装weex时报C++编译错误

```
npm install --global --production windows-build-tools
```
