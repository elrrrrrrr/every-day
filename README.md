# Everyday

> 重要的不是你想做什么，而是你做了什么。

##  日历

* -[x] [八月](#Aug)

* -[x] [九月](#Sep)

* -[ ] [十月](#Oct)

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

.31 竟然是res.end(data)快! 完善了[every-status](http://www.every-status.com)，组建库[fragment](http://f.every-status.com)也已经上线

<a  name="Sep"></a>
###  九月

.1 因为[pm2](https://github.com/Unitech/PM2)的关系，弄挂全站，没能通过新浪审核 T T ，今天陆续完善了小站，感觉一期快要告一段落。

.2 [gulp-jade2mod](https://github.com/elrrrrrrr/jade2mod)发了第一个release，不知道有没有坑，还需要抽空完善一下文档。[through2](https://www.npmjs.org/package/through2)也是个蛮好用的东西，方便调用stream和pipe。

.3 由于jade提供的runtime模块不支持cortex，重新写了一个[jade-env](https://github.com/elrrrrrrr/jade-env)，总算在浏览器端比较好的编译jade，发现蛮久没有写html标签了，感觉真不错 : ) 。

.4 写了原生的[swipeslide](https://gist.github.com/elrrrrrrr/d00b245c26b55a926a7f)组件，还在纠结怎么实现pan手势。感觉时间好不够用。

.5 阿强推荐的测试好伙伴[supertest](https://github.com/visionmedia/supertest)。

.6 facebook的新开源框架[ReactJS](http://facebook.github.io/react/)，可以结合backbone。

.7 非常好用的注释生成器[docblockr](https://github.com/spadgos/sublime-jsdocs)，终于可以开始写注释了。慢慢打算从sublime迁移到atom上，实在吃不消保存闪退的问题。项目根据开发进度，增加了deploy分之，慢慢切版本。

.8 新的开始

.9 [flexbox](http://css-tricks.com/snippets/css/a-guide-to-flexbox/)可以简单实现平铺，[webkit-box](https://gist.github.com/elrrrrrrr/d64f14b0cd68e6feefe0)可以很方便的实现多行文字，末尾替换省略号。

.10 关于css垂直居中的一些[实现](http://t.cn/RhycoGo?u=2017654444&m=3752262402525521&cu=2017654444)

.11 [cheerio](https://github.com/cheeriojs/cheerio)可以用来解析爬虫拿到的页面。 另外不知道subl有没有啥插件也支持html选择器的api去选择编辑内容。

.12 使用heredoc和[lodash](http://lodash.com)[渲染模版](https://gist.github.com/elrrrrrrr/175de2b90c430840bba6)，加上昨天的爬虫，可以很方便的实现poi信息抓取。发现了[trianglify ](http://qrohlf.com/trianglify/)，实现随机生成三角型。

.13 参加iweb上海分享，感觉[Hbuilder](http://dcloud.io/)和[Egret](http://egret-lab.org/)游戏引擎还不错。刚开始看AngularJs动物书，不过一直对Angular没什么感觉，可能和现在的业务有关系。

.14 粗粗看完了《用AngularJS开发下一代Web应用》, Angular几乎可以让你完全忘记DOM，甚至页面交互和模版渲染，可是感觉真是爱不起来。

.15 使用了[swipe](https://github.com/thebird/Swipe),看起来简单的效果实现起来还是很麻烦；发现新浪微博应用类型写错了，感觉好心酸。

.16 实现了AIR中配置文件热更新，每次都清空了require的[cache](http://stackoverflow.com/questions/1972242/auto-reload-of-files-in-node-js)

.17 拖了很久，终于把subl代码[高亮](https://gist.github.com/elrrrrrrr/4c2f5a315f8d2b9a52cc)了，可以在JSON.stringify传入space参数控制缩进。

.18 准备开始使用[spm](http://docs.spmjs.org/doc/)，[arale](http://aralejs.org/docs/about-arale.html)。在浏览器中引用npm包的插件[requirify](http://www.devspaper.com/2014/09/01/great-chrome-extension-requiring-npm-modules-in-the-browser-console/)

.19 简介的在线编辑器[demos](http://demos.berwin.me/),感觉在线编辑也是一个挺好玩的东西,例如[pen](http://sofish.github.io/pen/)。

.20 修复了线上的bug，希望应用审核能早日通过。看到了[D3](https://github.com/mbostock/d3/wiki/Gallery)的许多例子，感觉非常酷炫。看到了勾三股四的[h5slides](https://github.com/Jinjiang/h5slides)，想多加点功能 :sunny:

.21 被豆瓣授权登录坑了不少，结果是因为获取token时需要添加在body中，果然每个平台都不一样。另外由于使用了pomise，好像所有的req都必须用pomise封装起来。代码渐渐失控，找天重新写遍。发现了的[github cheat sheet](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-cn.md)

.22 修复了之前测试用例的小[bug](https://github.com/NodeLab/qin/blob/master/test/test.js#L12#L13), assert用的蛮不熟的 0.0, 不知道seajs有没有好用一些的gulp插件, 不想离开gulp ...

.23 把[jade-env](http://spmjs.io/package/jade-env)发布到了spm上，希望能尽快完成构建流程的迁移，明天瞧瞧[seajs-wrap](https://github.com/seajs/seajs-wrap)。

.24 确定使用seajs作为前端模块加载器，开发期间暂时使用seajs-wrap调试。发现了[gulp-base64&css-sprites](https://gist.github.com/elrrrrrrr/26d392093f20acd83c69)自动拼接css中的图片，解放双手 0.0 

.25 被新浪微博的应用审核折磨一整天... 明天重新抽象一下oauth代码, 再拖就要忘记了... 还要更新一下qinjs的文档

.26 新浪的审核终于通过了，不知道申请网站接入能不能获得token值，明天终于可以测试了。发现了非常酷炫的开源[Ghost Hosting](https://ghost.org/)。

.27 关于node中的ioc(依赖注入), TJ写的[node-di](https://github.com/vojtajina/node-di), 以及luin写的适用于express的[express-di](https://github.com/luin/express-di)，对于controller层依赖关系复杂的情况，可以很优雅的实现。希望有机会能尝试，虽然我现在写得最多也就两个控制器。。有空还要去尝试实现jquery的data方法，还没好好看过源码。

.28 顺手水了一个pull request, @sofish小鱼的[wechat.js](https://github.com/sofish/wechat.js), 虽然马上都被改了, 也算多多学习代码风格。发现了pm2的部署工具[tiny-dploy](https://github.com/voronianski/node-tiny-dploy)，可惜pm2和我的阿里云水土不服。

.29 报名参加了[D2大会](https://github.com/soulteary/Get-D2-2014-Ticket)，希望能通过审核呀。去除掉了恶心的新浪SDK，总算有一个可用版本。真的不太理解新浪审核的意义是什么。

.30 开始看深入浅出NodeJs，实现[wechat.js](https://github.com/sofish/wechat.js)的多模块适配。

<a  name="Oct"></a>
###  十月

.1 重新完善了一下[qinjs](https://github.com/elrrrrrrr/qinjs/issues)，添加了注释和TODO，掐指一算，剩下的时间也许真的不是很多啦，加油尽快弄出一个自己用的版本。

.2 看完了深入浅出NodeJs，添加了[qin](https://github.com/NodeLab/qin)对post请求和条件判断的支持，向下兼容。

.3 发现了浏览器端的单元测试驱动[Karma](http://karma-runner.github.io/0.12/index.html)，结合mocha，可以在真实浏览器中对浏览器脚本进行单元测试。

.4 由于[saucelabs]速度限制，放弃karma作为测试集成方案，另phatomjs无法调用**Function.prototype.bind**方法

.5 使用[mocha-phantomjs]集成单元测试，作为原型项目的测试框架，非常轻量级。期望之后国内有比较好的云浏览器平台吧 0.0

.6 最近项目写得有点乏力，到疲惫期了..

.7 增加了一些单元测试, 后端fav逻辑已经实现, 等待前端

.8 重新申请了github的education计划，这次上传了校园卡，但愿能过 0.0

.9 写了一些关于单元测试的分享，没想到能被merge成一个独立[node课程](https://github.com/alsotang/node-lessons/tree/master/lesson7)，今天入职alipay，又是一个新的开始，加油加油。

.10 自由、简单、强壮的多平台测试工具[totoro](http://totorojs.org/)。

.11 发现了不错的在线编辑平台[coding](http://coding.net)，支持代码托管、测试、服务继承、在线编辑、多人协作、私人仓库等...要是能支持yml配置就更好了。

.12 第N次想学VIM，不过还是放弃了...老乡@幕陶的[dotfile](https://github.com/xujihui1985/dotfiles/blob/master/install_vim_plugin.sh),今天看了些es6语法糖,加上NVM,可以开始玩玩了，不过感觉和coffee真的好像，尤其是不定参数，参数默认值，箭头函数；还看了下stream和pipe，cluster、console、child-process，今天收获挺多，渐入佳境 :smile:

.13 写了个scafford的小工具[pokeball](https://github.com/NodleJS/pokeball)，继续用了commanderjs，这次加上了inquirer作输入提示。顺手添加了[every-status](http://every-status.com)的首页改版，着手写spm的版本管理工具。今天收获多多 :snake:

.14 实现了简单的[spmv](https://github.com/elrrrrrrr/spmv)作spm的版本控制，还在`纠结`几个上线用的业务系统，好想打代码 ...

.15 类似`es5-shim`的[es6-shim](https://github.com/paulmillr/es6-shim)，es6[入门教程](http://es6.ruanyifeng.com/)期待新的好像HTML5的标准快出了，期望ES6也能早日标准化...

.16 参加了proparty的组内分享，@炫明师兄分享eventloop相关内容，感觉好有趣，哈哈。[every-status](http://every-status.com)更新了favcion

.17 完善了[spmv](https://github.com/elrrrrrrr/spmv)，基本可以满足简单需求，完善好文档和测试用例，基本就可以开源啦。另外发现了一个很好玩的把文字转成字符串图案的[小站](http://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20)

.18 热烈欢迎前端同学@qinnnnnnn加入！开始动手实现点赞功能,都页面兼容性可以用[pageres](https://www.npmjs.org/package/pageres)保存快照。

.19 quick & dirty 实现了点赞的借口, 另外准备使用[marked](https://www.npmjs.org/package/marked)添加新功能。

.20 添加markdown支持，但是样式还需要继续调整，不知道别的站点是不是有markdown的样式库。剩下分享功能一期基本就要完成了 ^ ^ 

.21 实现微博分享功能，一些chrome开发者工具的小[tips](http://devtoolstips.com/)