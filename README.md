# 京东次要活动项目

#使用方法参照[JD-scripts](https://github.com/l499477004/JD-scripts)


##### 京东(必须)
| Name                    |   归属   | 说明                                                         |
| :---------------------: | :----------: | ------------------------------------------------------------ |
| `GIT_CLONE_URL`         |   GITHUB   | 填写格式：`https://github.com/自己的仓库名称/JD-Activity.git` 切记填写自己的仓库名称。|
| `JD_COOKIE`             |   京东   | 必须   | 京东cookie,多个账号的cookie使用`&`隔开或者换行。具体获取参考[浏览器获取京东cookie教程](https://github.com/l499477004/JD-scripts/blob/master/backUp/GetJdCookie.md) 或者 [插件获取京东cookie教程](https://github.com/l499477004/JD-scripts/blob/master/backUp/GetJdCookie2.md) |


##### 推送通知环境变量
| Name                    |   归属   | 属性   | 说明                                                         |
| :---------------------: | :----------: | --------- | ------------------------------------------------------------ |
| `PUSH_KEY`              |   微信server酱推送   | 非必须 | server酱的微信通知[官方文档](http://sc.ftqq.com/3.version) |
| `BARK_PUSH`             |   [BARK推送](https://apps.apple.com/us/app/bark-customed-notifications/id1403753865)   | 非必须 | IOS用户下载BARK这个APP,填写内容是app提供的`设备码`，例如：https://api.day.app/123 ，那么此处的设备码就是`123`，再不懂看 [这个图](icon/bark.jpg)（注：支持自建填完整链接即可） |
| `BARK_SOUND`            |   [BARK推送](https://apps.apple.com/us/app/bark-customed-notifications/id1403753865)   | 非必须 | bark推送声音设置，例如`choo`,具体值请在`bark`-`推送铃声`-`查看所有铃声` |
| `TG_BOT_TOKEN`          |   telegram推送   | 非必须 | tg推送(需设备可连接外网),`TG_BOT_TOKEN`和`TG_USER_ID`两者必需,填写自己申请[@BotFather](https://t.me/BotFather)的Token,如`10xxx4:AAFcqxxxxgER5uw` , [具体教程](./backUp/TG_PUSH.md) |
| `TG_USER_ID`            |   telegram推送   | 非必须 | tg推送(需设备可连接外网),`TG_BOT_TOKEN`和`TG_USER_ID`两者必需,填写[@getuseridbot](https://t.me/getuseridbot)中获取到的纯数字ID, [具体教程](./backUp/TG_PUSH.md) |
| `DD_BOT_TOKEN`          |   钉钉推送   | 非必须 | 钉钉推送(`DD_BOT_TOKEN`和`DD_BOT_SECRET`两者必需)[官方文档](https://ding-doc.dingtalk.com/doc#/serverapi2/qf2nxq) ,只需`https://oapi.dingtalk.com/robot/send?access_token=XXX` 等于`=`符号后面的XXX即可 |
| `DD_BOT_SECRET`         |   钉钉推送   | 非必须 | (`DD_BOT_TOKEN`和`DD_BOT_SECRET`两者必需) ,密钥，机器人安全设置页面，加签一栏下面显示的SEC开头的`SECXXXXXXXXXX`等字符 , 注:钉钉机器人安全设置只需勾选`加签`即可，其他选项不要勾选,再不懂看 [这个图](icon/DD_bot.png) |
| `QYWX_KEY`              |   企业微信推送   | 非必须 | 密钥，企业微信推送 webhook 后面的 key [详见官方说明文档](https://work.weixin.qq.com/api/doc/90000/90136/91770) |
| `IGOT_PUSH_KEY`         |   iGot推送   | 非必须 | iGot聚合推送，支持多方式推送，确保消息可达。 [参考文档](https://wahao.github.io/Bark-MP-helper ) |
| `TG_PROXY_HOST`         |  Telegram 代理的 IP  | 非必须 | 代理类型为 http。例子：http代理 http://127.0.0.1:1080 则填写 127.0.0.1 |
| `TG_PROXY_PORT`         |  Telegram 代理的端口  | 非必须 | 例子：http代理 http://127.0.0.1:1080 则填写 1080 |