# 微信小程序demo 

去年小程序刚发布时特别火，赶潮流做了个demo。感觉小程序开发还是比较简单的，主要是官方文档写得比较好，遗憾的是很多API需要微信认证才能使用。

![demoImg1](http://ooqymz3vm.bkt.clouddn.com/demo1.png)
![demoImg2](http://ooqymz3vm.bkt.clouddn.com/demo2.png)

由于小程序包大小限制在1M以内，所以商品图片等资源放在了云上，另外用Nodejs+Express写了个简单的API服务器，数据较少所以没有用数据库。
感兴趣的可以下载代码跑一下，服务器代码在server分支。

### 如何使用
下载小程序源码及服务器源码，启动服务器后，在微信web开发者工具中选择“添加项目”，然后选择项目目录为下载的源码路径，打开即可看到效果。

### 演示：

(第一张GIF图有点大，请耐心等待)

![demoGif1](http://ooqymz3vm.bkt.clouddn.com/demo1.gif)

![demoGif2](http://ooqymz3vm.bkt.clouddn.com/demo2.gif)

![demoGif3](http://ooqymz3vm.bkt.clouddn.com/demo3.gif)
