# WordPress版微信小程序 2.0 重构版

作者：叶赫先生 Wechat ID: ryan_yuu


# 重构功能清单：

1.重构首页内容列表的显示方式，分为：右图模式、大图模式、双图模式；

2.调整首页轮播图大小以及显示样式；

3.重构文章详情页页头部分，增加了thumhub_img图片，并优化了标题部分的显示样式；

4.重构专题页的列表显示排序样式，采用大图模式，并修复了缩略图的裁剪方式；

5.重头了readlog页面的list显示方式，去除正序列表，改成有序列表；

6.个人版本无法使用赞赏功能，所以去除了pay文件夹；


# 功能清单：

1.缩略图的方式显示文章列表，包括显示文章分类和发布时间，加载分页。

2.在首页用轮播方式显示置顶文章。

3.显示文章分类（专题），包括显示分类的封面图片（新版本更新：专题列表重新优化显示方式）。

4.显示文章内容页，包括文章站内链接跳转，站外链接复制到剪切板，显示猜你喜欢的相关文章。

5.显示文章评论，提交评论和回复评论，加载评论分页，显示微信用户评论者的头像。

6.显示文章排行

7.显示wordpress“页面”类文字（关于页面）。

8.对文章内容的全文搜索。

9.文章页面的分享、转发，复制。

10.WordPress 插件的配套功能。

11.文章浏览数显示及更新。

12.文章微信用户点赞及点赞的微信用户头像显示。

13.通过微信支付对文章赞赏。

14.赞赏后发送模版消息。

15.web-view内嵌网页跳转。

16.回复评论发送模板消息。

17.专题订阅。

18.文章海报（分享微信朋友圈的卡片）。

# 原作者开源地址

https://github.com/iamxjb/winxin-app-watch-life.net


# 技术支持网站：https://www.yeehee.cn


# 小程序配套wordpress插件：

本小程序完整使用需要配合原作者（imxjb）编写的wordpress插件wp-rest-api-for-app，才能完整使用，插件下载地址： https://github.com/iamxjb/wp-rest-api-for-app

# 小程序配套赞赏（微信支付）功能服务端程序：

本小程序赞赏功能需要配合原作者（imxjb）编写微信支付服务端php程序，才能使用，程序下载地址： https://github.com/iamxjb/weixin-app-wxpay

# 开源协议：MIT

# 技术支持微信：ryan_yuu


# 安装使用说明文档

<a href="https://www.watch-life.net/wordpress/weixin-app-install.html" target="_blank" rel="noopener">WordPress版微信小程序安装使用说明</a>


# 讨论微信群：

由于微信群超过100人，无法再扫描二维码加入。如果你想加入，请先加我的微信：ryan_yuu ，我拉你入群。



# 开源声明：

1、本程序html转wxml的解析采用的是https://github.com/icindy/wxParse

2.本程序有关es6-promise 部分代码参考 开源程序：https://github.com/cinoliu/-es6-promise


在此对上述提供开源及创意表示致谢。


# 捐赠赞赏：请微信扫描以下二维码。感谢您对我的支持，您的支持是我前进的动力

![weixinpay](https://www.yeehee.cn/wp-content/uploads/2018/07/2018072012153896.jpg) 

# WordPress微信小程序知识星球(小密圈)

考虑到微信群里交流过于庞杂和碎片化，无法提供更专业的技术服务和知识分享，很多好的知识不能很好沉淀和积累，无法提供更好的分享价值，同时我也有意和兴趣相投人一起，创建一个wordpress和微信小程序的知识社区。基于此，我在“知识星球”里创建了一个“Wordpress微信小程序”的圈子，欢迎有兴趣的朋友和我一起创建一个有活力、创造力、有趣、有深度的知识社群。

![zhishixingqiu](https://www.yeehee.cn/wp-content/uploads/2018/07/2018072013244459.jpg)
 


# 更新历史：

## 2018年2月15日

1.增加文章海报（分享微信朋友圈的卡片）功能。

2.兼容个人主体小程序的功能完善

3.文章分享加题图。

4.首页导航，提供三种方式的跳转

## 2017年12月15日

1.增加赞赏后发送模板消息。

2.增加回复评论发送模板消息。

3.调整评论和回复的显示方式及提交评论、回复发送方式。

## 2017年11月1日

1.调整“热点”板块为“排行”板块，显示按评论数、浏览数、点攒数、赞赏数的文章排行。

2.增加“我的”板块，显示我浏览、评论、点赞、赞赏过的文章。

3、加入内链的web-view嵌入网页跳转。

4、在关于中显示“赞赏”或“捐赠”人的头像，并致谢。


## 2017年9月16日
1.增加点赞功能

2.增加赞赏功能（微信支付）


## 2017年8月17日
1.增加站内链接。

2.增加猜你喜欢功能。

3.增加热点文章功能。

4、取消浏览记录功能。

## 2017年7月29日

1.完善文章的评论，按评论时间对一级评论按时间先后显示，最新发表的显示在最上面。

2.以嵌套的方式显示评论和回复，最多显示5层嵌套。

3.增加评论的回复功能，可以针对4级评论（回复）进行回复。

4.文章内容页加入一直没有引入的wxParse.wxss文件（弥补愚蠢的错误）。

## 2017年7月15日

1.完善首页列表的缩略。调整为150*150的小图，需要配合wp-rest-api-for-app插件.

2.去除侧滑菜单。增加专题分类，并完善搜索。

3.完善评论及显示。

4.优化程序性能，整理wxss，让程序代码更易懂和美观.

5.修复获取微信头像bug，当头像如果是https地址的话，不强制转换成https。

6.修复没有置顶文章，下拉刷新不显示列表的bug。

7.为评论增加分页，提供分页刷新的功能。


## 日期：2017年6月6日

内容：

1.调整列表页的显示方式。

2.增加搜索。

3.首页增加轮播图片和缩略图。

4.增加文章评论

5.增加小程序分享


## 日期：2017年5月15日

内容：

1.在主页面，加入浮动按钮，用来打开侧滑导航菜单。

2.增加侧滑导航菜单，菜单上包括页面及文章分类.侧滑菜单代码参考WechatSmallApps（https://github.com/jkgeekJack/WechatSmallApps）的代码修改。

3.优化下拉刷新数据（分页）的性能。

4.文章列表页添加发布时间。

5.升级最新的微信小程序富文本解析组件wxParse（https://github.com/icindy/wxParse）


"# WordPressMiniProgram" 
