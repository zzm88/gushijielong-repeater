# 狗尾续喵与复读机
## 简介
### 狗尾续喵
https://gushijielong.cn/ 是一个基于FairyBBS的故事接龙爱好者社区，在这里用户可以发起或参与接续故事。
### 复读机
复读机（q号：2790912541）是狗尾续喵的衍生项目，基于酷Q（酷Q之后换成了go-cqhttp）和Nonebot的一个qq机器人。主要功能是对接狗尾续喵网站，让用户可以在Q群里完成故事的发起与接续。

## 开源
复读机计划在代码整理之后开源，让有兴趣的朋友可以参与插件的开发

### go-cqhttp 和 nonebot 的使用说明（大致）
1. 根据你的操作系统下载对应的go-cqhttp版本，在config.yml中配置好测试用qq号，并运行
2. 配置好nonebot并运行
3. 若顺利的话，go-cqhttp会负责监听qq信息（相当于一个无头qq客户端），并把消息实时传送给nonebot进行处理，并调用相应的方法操作qq（发送qq消息等）。可以这么理解：go-cqhttp是qq客户端，nonebot是客户端操作员。我们主要需要做的就是为nonebot写合适的plugins

# nonebot plugins
## None官方插件
Nonebot官方自带的examples和说明都很详细，点击链接查看
## 复读机插件
整理中

# 其他
## 狗尾续喵Q群
42839328

## 复读机q号
2790912541
