# Xvs视频服务器API调用示例

>  此测试页需要和Xvs视频服务器配合使用, 并且只兼容chrome和firefox浏览器

本仓库中的index.html演示了如何通过Javascript来调用xvs服务器提供的api, 演示页面调用的api有如下:

  - 获取任务列表
  - 获取在线用户列表
  - 播放直播视频
  - 发送文本消息
  - 发送语音消息(打开控制界面可见)
  - 创建拉流任务
  - 终止一个任务

### 使用方法

+ 将下载的目录解压到xvs的webroot目录下
+ 在浏览器中打开相应地址，此页面会列出当前所有正在进行的(不论是通过手机推上的流还是通过API接口创建的拉流)任务，以及每个直播对应的输出，可选对相应的输出流进行播放。
+ 如果要对直播进行控制，则在演示url后加上`?console=true`

[访问直播云网站](http://www.zhiboyun.com)
