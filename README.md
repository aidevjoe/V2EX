# 声明

由于开源软件被二次分发到App Store，即日起该仓库正式闭源。
起初对于开源协议没有过多的了解就直接选择了MIT协议，直到发现该开源软化被二次分发到App Store，才了解该协议并没有规定不允许商用，所以我无法追究责任，只能选择闭源。
开源的目的是用于学习和交流，但是没有想到被他人用于商用，这是我万万没有想到的事情，也是我自己的错失而导致。
这是第一次开源，也是最后一次。

# V2EX


## 介绍

可能是体验最好的掌上 V2EX 客户端，苦于在 iPhone 上一直没有找到一款 **好用的** V2EX 客户端，于是这个项目诞生了，该项目借鉴很多开源的 V2EX 客户端，在此表示感谢开源社区。由于目前开发周期较短，很多地方还不够完善，存在着很多问题和不合理的设计，如果你有任何意见或功能要求欢迎打开 **Issue** 或 **PR**，最后希望能得到您的喜欢，感谢 😊

[![App Store](http://apprcn.b0.upaiyun.com/badge_appstore-lrg.svg)](https://itunes.apple.com/us/app/v2er/id1308118507?l=zh&ls=1&mt=8)

## 截图

<img src="https://github.com/Joe0708/V2EX/raw/master/Screenshot/home.png" width="210"><img src="https://github.com/Joe0708/V2EX/raw/master/Screenshot/node.png" width="210"> <img src="https://github.com/Joe0708/V2EX/raw/master/Screenshot/message.png" width="210"><img src="https://github.com/Joe0708/V2EX/raw/master/Screenshot/more.png" width="210">
<img src="https://github.com/Joe0708/V2EX/raw/master/Screenshot/search.png" width="210"><img src="https://github.com/Joe0708/V2EX/raw/master/Screenshot/topicDetail.png" width="210"> <img src="https://github.com/Joe0708/V2EX/raw/master/Screenshot/createTopic.png" width="210"><img src="https://github.com/Joe0708/V2EX/raw/master/Screenshot/login.png" width="210">


## 功能

### 首页
1. 浏览热门主题、最新主题等主题列表。。
2. 上拉加载更多(仅 *全部* Tab)
3. 主题搜索（按权重 or 时间排序）

### 主题详情
1. 复制链接、从 Safari 打开、系统分享
2. 主题(主题回复) 收藏、感谢、忽略 操作
3. 查看对话上下文
4. 主题回复（支持贴图）、@单个或多个用户
5. 回复列表如果是图片链接直接解析成图片
6. 只看楼主

### 节点
1. 导航节点、所有节点
2. 节点搜索

### 消息
1. 查看所有消息
2. 消息提醒
3. 删除消息
4. 快捷回复

### 更多
1. 创作新主题（支持 Markdown 编辑、预览、上传图片）
2. 查看我的
- 节点收藏
- 主题收藏
- 我的主题
- 我的回复
3. 修改头像
4. 两步验证
5. 每日奖励自动领取

### 其他
1. 支持 横竖屏（横屏目前优化不是特别好）
2. 支持 iPad
3. 支持 夜间模式
4. 支持 密码管理工具（1Password、LastPass...)
5. 支持 Google 账号登录
6. 验证码自动识别
7. 首页节点排序

## 要求

- iOS 9.0
- Swift Version 5.0
- Xcode 10.2 or later


## 运行

1. 克隆项目

```
git clone https://github.com/Joe0708/V2EX.git
```

2. 在项目根目录安装依赖库

```
pod install
```
3. 打开 `V2EX.xcworkspace` 运行


## 感谢
- 强大的开源社区
- [SM.MS](https://sm.ms/doc/) 图片上传 API
- [SOV2EX](https://github.com/bynil/sov2ex/blob/master/API.md) 搜索 API
- [Iconfont](http://www.iconfont.cn/) 图标库

## 声明

此项目仅供学习参考，请勿用于其他任何恶意用途，如有侵犯到您的权益，请联系我及时删除 joesir7@foxmail.com

## License

V2EX is available under the MIT license. See the [LICENSE file](https://github.com/Joe0708/V2EX/blob/master/LICENSE) for more info.

