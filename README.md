# Everyday

> 重要的不是你想做什么，而是你做了什么。

##  日历

* [八月](#Aug)

<a  name="Aug"></a>
###  八月

.7  刷面试题，顺手建了这个repo，瞧见了substack大神的[browserify](http://browserify.org/)

.8  总算开始在[stackoverflow](http://www.stackoverflow.com)问问题，折腾了一下[Heroku](https://dashboard.heroku.com/apps),云平台,和期望不太相符

.9  还是买了[阿里云](http://121.40.137.124:8999/)，开始尝试写[Gist](https://gist.github.com/elrrrrrrr/f411471f8c674f793eb3)

.10 买下了[every-status](http://www.every-status.com)，项目正式启动；选了[Mocha](http://visionmedia.github.io/mocha/)作为单元测试库；正式开始写[jade](http://jade-lang.com/)

.11 服务器部署[mongodb](http://docs.mongodb.org/manual/)，node选用[mongoose](http://mongoosejs.com/)作为驱动

.12 初步选用[coffeescript](http://coffeescript.org)，文件组织方式待定，翻译的[编码指南](https://github.com/elrrrrrrr/coffeescript-style-guide/blob/master/README-ZH.md)

.13 发现了一个很好用的类curl工具[httpid](https://github.com/jakubroztocil/httpie)

.14 觉得很累，休息一天。

.15 处理模块引入异常，新建model层。

.16 看了一天七龙珠，真好看。

.17 锻炼身体。

.18 看完了《编写可维护的JavaScript》，更新若干[gist](https://gist.github.com/elrrrrrrr)。多文件html线上平台[JSFiddle](http://jsfiddle.net/),单文件[compile online](http://www.compileonline.com/try_html5_online.php)

.19 实现mongoose[自增id](https://gist.github.com/elrrrrrrr/792a275f8506e9562852)，定义url，从单切片进行开发 :）踩进了mocha[异步](http://stackoverflow.com/questions/25379309/how-to-use-mongoose-in-mocha-unit-test/25379775?noredirect=1#comment39594584_25379775)的坑。

.20 终于实现了生产环境的自动部署，用了[dploy](http://dploy.io/)。更新了下github的TODO，- [ ] 自动会转义成checkbox。

.21 小试nginx，实现[端口转发](https://gist.github.com/elrrrrrrr/27577929edf0fb67e40f)。不过还是没空去备份域名。

.22 发现了声势很大的[duojs](http://duojs.org),还有一个基于JSON的数据库[LowDB](https://github.com/typicode/lowdb),没想到真的有人这么去做 :)

.23 发现了阿里的[mongoskin](https://github.com/kissjs/node-mongoskin)，mongoose无法删除DB，还没找到问题，有空要研究一下链接池的控制。顺手发现[cnpm](https://github.com/cnpm/cnpm/issues/42)的权限问题，希望没有得罪别人 0.0 。一期结束之后一定要迁移到[koaJs](https://github.com/koajs/koa)。

.24 争取下周对于嵌套回调使用[Q](https://github.com/kriskowal/q)解决回调问题，今天完善了用户逻辑，开发者模式。最近睡眠都不太好，希望今天能睡个好觉。

.25 修改了页面很多细节，包括动态化列表页数据，准备开始接入第三方登陆功能，用户对象需要继续扩展。域名也已经开始备案，希望一起顺利 :) 发现一个好玩的JS库[cupertinojs](https://github.com/jerrymarino/cupertinojs?utm_content=buffer23702&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)；还有个非常小清新的[twentyjs](http://twentyjs.com/)，期待！

.26 折腾了微博第三方登录，还是无法彻底解决异步回调，暂时直接抛出Promise对象。新浪微博的Oauth感觉很奇怪，暴力使用 ^ ^ 。站点完全采用第三方登录。

.27 完善了登录逻辑，就等着域名下来写到配置里去了。休息一天:)

.28 [every-status.com](every-status.com)终于批下来了，终于削平了登录逻辑里的意大利面条，感谢[callback hell](http://callbackhell.com/)，今天记录了一下之前遇到的低版本浏览器相关Array的[fix](https://gist.github.com/elrrrrrrr/369c651e9a81e0eeb7f6)。

.29 今天继续完善了登录逻辑，还需要优化异常提示，不久应该就能上线了。今天刚开始看《深入浅出nodejs》，早点看到就好了:）。

.30 res.write(data);res.end() 和 res.end(data) [哪个快](https://github.com/joyent/node/blob/master/lib/_http_outgoing.js#L486)？