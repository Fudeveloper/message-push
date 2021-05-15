# message-push

<br />消息推送-渠道整合<br />

# messagePush适用哪些场景？
> 可能的场景如：
> 批量发送奖励、活动、等各类通知
> 批量发放消费码、券等
> 批量发送各类服务通知
> 微信服务号各种模板消息
> 

> 发送短信验证码
> 发送邮件验证码



# 渠道支持计划
## 短信


- [ ] 阿里云短信推送
- [ ] 阿里云短信
- [ ] 阿里大于模板短信
- [ ] 腾讯云短信
- [ ] 华为云短信
- [ ] 百度云短信
- [ ] 又拍云短信
- [ ] 七牛云短信
- [ ] 云片网短信



## 微信类


- [ ] 模板消息-公众号
- [ ] 模板消息-小程序
- [ ] 订阅消息-小程序
- [ ] 微信客服消息
- [ ] 微信企业号/企业微信消息
- [ ] 小程序统一服务消息
## 其他


- [ ] 邮件推送
- [ ] 钉钉
- [ ] WebHook



# 其他功能性支持

- [ ] 细粒度定时推送
# 功能
对常用的通知渠道进行整合，并对外提供rest API，方便其他应用调用。<br />同时也可通过部署前端项目，来直接通过web界面操作、体验。<br />

# 预览

<br />请参考此前端项目：<br />

# 使用到的技术

- 核心框架：Spring Boot 2.4
- 认证框架：Apache Shiro 1.4
- 视图框架：Spring MVC 5.0
- 持久层框架：MyBatis-Plus 3.4.2
- 定时器：Quartz 2.3
- 数据库连接池：Druid 1.0
- 日志管理：SLF4J 、LogBack
# 鸣谢
[WePush](https://gitee.com/zhoubochina/WePush)  本项目大部分参考WePush，只是根据自己的需求，将使用Swing技术的项目改造为前后端分离的Web项目<br />[renren-fast](https://gitee.com/renrenio/renren-fast)<br />[WxJava](https://gitee.com/binary/weixin-java-tools)<br />[Hutool](http://hutool.cn/)<br />

