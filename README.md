**基于`YuQ-Mirai`的没有菜单的而且也不好用的机器人**
* [YuQ](https://github.com/YuQWorks/YuQ)
* [YuQ-Mirai](https://github.com/YuQWorks/YuQ-Mirai)
* [YuQ-Mirai-Demo](https://github.com/YuQWorks/YuQ-Mirai-Demo)
* [YuQ-Mirai-SuperDemo](https://github.com/YuQWorks/YuQ-SuperDemo)
* [Mirai](https://github.com/mamoe/mirai)

## 功能
* QQ一键签到
* 超级萌宠一键养成
* 微博监控
* 自动修改步数
* 网易云音乐打卡和每日300首听歌量
* 一些小工具

指令：[https://u.iheit.com/kuku/bot/menu.html](https://u.iheit.com/kuku/bot/menu.html)

安装教程：[https://blog.kuku.me/index.php/archives/3/](https://blog.kuku.me/index.php/archives/3/)

## 配置文件
```properties
# 运行模式，该模式会影响配置文件读取，或某些模块的行为。默认为 dev
# yu.config.runMode = dev

# 扫描包路径
yu.scanPackages=me.kuku.yuq

# 机器人登录的协议，可为 Watch （手表）、Android （安卓），默认为Ipad
YuQ.Mirai.protocol=

# 机器人名，可不配置。
# YuQ.bot.name = Yu

# 自定义 Ehcache 配置文件
yu.cache.ehcache.config=ehcache-YuQ-Mirai.xml

# 登录的 QQ 号
YuQ.Mirai.user.qq=
# 登录的 QQ 号的密码
YuQ.Mirai.user.pwd=
# 机器人主人
YuQ.Mirai.bot.master=734669014
# pixiv的cookie，需在登录的情况下抓取cookie的PHPSESSID
YuQ.Mirai.bot.pCookie=
# api
YuQ.Mirai.bot.myApi=api.kuku.me
# ai.qq.com/v1的app_id，需赋予图片鉴黄、智能闲聊、通用OCR能力
YuQ.Mirai.bot.ai.appId=
# ai.qq.com/v1的app_key，需赋予图片鉴黄、智能闲聊、通用OCR能力
YuQ.Mirai.bot.ai.appKey=
```

## 说明
* 机器人使用之前必须发送`机器人 开`才能开启机器人
* 数据库使用h2，目录`db`下
* 发送的图片保存在`images`目录下
* 步数修改使用lexin运动的接口
* 本程序仅供内部学习和交流使用，并倡导富强、民主、文明、和谐,倡导、平等、公正、法治,倡导爱、敬业、信、友善,积极培育和践行社会主义核心价值观。
