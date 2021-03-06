好邻业主圈小程序
=============
##### 一套模块化设计的基于邻里间互动关系开发的微信小程序社区系统(包含全部前后端源码)
##### 开发者：[大帅(ezshine)](https://www.zhihu.com/people/ezshine) 

![封面图](https://github.com/ezshine/community-mini-program/blob/master/thumb.jpg)

### 说明
##### 因为参与到业委会的组织和建立，于2017年6月份左右策划，本人独立设计并开发完成上线第一版社区，后边陆陆续续有新增，修改，完善。得到了本小区业主们和广大网友的好评和支持。		

![缩略图](https://github.com/ezshine/community-mini-program/blob/master/thumbs.jpg)
### 功能介绍

#### --> 公告
##### 除了小程序内的提示外，可通过小程序模板消息向全体用户发送通知。

#### --> 天气
##### 获取某个地区5日内的天气预报，空气情况等，由于作者生活在北京，所以加入了北京地区的限号情况。

#### --> 电话黄页
##### 物业、维修、外卖、等各类服务电话一键拨打

#### --> 积分中心
##### 签到、回帖、发帖后可获得积分，在市集中可以使用积分获得商品购买的优惠（优惠由商家发布商品时设置）。

#### --> 车位路况
##### 获得好评最多的一个版块，通过部署在业主家室外的监控探头实时查看本小区的地面停车位和周边道路交通状况。

#### --> 微信步数排行
##### 邻居间的微信运动打榜

#### --> 论坛模块
##### 所有论坛板块都做了基本的敏感词过滤，并具备点赞，评论，回复。帖子有新的回复或点赞时有微信模板消息通知。

#### --> 友邻市集
##### 【论坛模块中的特殊板块】所有业主都可以在这个版块内发布带价格的商品或者服务，但这里并没有完成支付，需要面对面交易。

#### --> 民意投票
##### 【论坛模块中的特殊板块】业主们可以发布支持或不支持的二选一投票

#### --> 匿名板块
##### 【论坛模块中的特殊板块】业主们可以在这里匿名发布内容，非常火爆的一个【负能量板块】，所有论坛板块都做了基本的敏感词过滤。


	微信小程序的审核非常严格，如果没有互联网增值业务许可证，你是无法上架一个社区小程序的。
	作者本人也没有这个证，但在源码中贴心的设计了绕过审核的开关，但依旧不保证能过审
	如果你在审核中遇到了一些问题，也可以咨询我。		

如果你觉得这份源码对您有些帮助，可以通过以下方式请作者吃顿饭，抽包烟，喝杯咖啡等。
![捐助](https://github.com/ezshine/community-mini-program/blob/master/donate.jpg)


### 部署说明
* 在API文件夹中的mysql.php中配置自己的数据库地址，用户名，微信小程序appid，secret等
* 将“数据库表.sql”导入到自己的数据库中
* src/app.js中更改相关的URL路径

