# 联系方式

- 手机：15896731218
- Email：1048222543@qq.com
- QQ：1048222543

# 个人信息

- 朱志强/男/1993 
- 本科/周口师范学院计算机科学与技术学院
- 工作年限：2年
- 技术博客：https://blog.csdn.net/sinat_25926481
- Github：https://github.com/zhuzhiqiang18
- 期望职位：Java开发工程师

# 工作经历

## 三益（郑州）贸易有限公司 （ 2017年8月 ~至今 ）

### 全民外贸 

全民外贸是一个跨境电商出口代购平台，用户购买的商品到周期后归还付款金额和利润。
系统分为用户管理，订单管理，商品管理，回款管理，提现管理，数据报表等模块。有APP端（Android，Ios）和PC端。

系统使用软件框架以及插件：Jfinal、Spring Boot、Mybatis、Beetl、druid、Redis、EhCache、ActiveMQ、POI、Tomcat、Nginx等。

第一版系统（下文简称V1）急速开发，使用国内优秀开源框架Jfinal作为主框架，第一版只有APP端和管理后台。

第二版系统（下文简称V2），PC端和APP接口使用SpringBoot开发，API是restful风格，PC为了更好的SEO，页面在服务端渲染，使用Beetl。

支付、提现渠道：支付宝。

我做了什么：后端架构整体设计开发到部署运维维护。

解决什么难题：

1、V1和V2共享一个数据库，会导致数据不一致。解决方案：redis分布式锁。

2、维护升级需要停机，重新打Jar包部署。解决方案：使用Nginx主备。[Nginx 主备 实现 后端不停机维护](https://blog.csdn.net/sinat_25926481/article/details/82224583)

3.报表慢查询。解决方案：使用EXPLAIN分析select语句进行分析加索引，12s优化到0.2s。

项目地址：www.qmwm777.com

### StarDay中日跨境电商平台 

跨境电商B2C平台，主要有客户管理，订单管理，权限管理，地区设置，商品管理，轮播图管理，数据报表，评论管理、运费管理，活动等模块。

系统使用软件框架以及插件：Jfinal、Beetl、druid、Redis、EhCache、POI、ActiveMQ、Tomcat、Nginx等。

我做了什么：后端架构整体设计开发到部署运维维护。

解决什么难题：

1、商品SKU的设计。解决方案：商品属性自由设置，然后使用排列算法列出SKU表格。[SKU排列算法
](https://blog.csdn.net/sinat_25926481/article/details/88874165)

2、对接日本本土线上支付，GMO。

项目地址：www.stardaymart.com

### StarDay海外仓WMS系统 

本系统分为客户端与管理端，客户端可以上传商品、申请入库、申请出库、充值、申请移除、申请换标（多个阶段）等，管理端主要是对以上功能的审核确认以及客户信息的维护等。

本系统使用SpringBoot构建，使用Mybatis作为数据层框架，Druid作为数据连接池，redis作为缓存组件。
本系统对接钉钉机器人，有新业务进度及时推送到钉钉群。
项目地址：www.stardaymart.cn

## 周口师范学院实验室 （ 2016年3月 ~ 2017年4月 ）

### 创联工场 

二次开发项目。独立负责后台数据管理系统新功能的设计与实现，整合旧功能，服务器部署。协助前端实现微信、android、ios。优化三端兼容。打包apk、ipa。上架appStore、360、应用宝、百度等应用商店，负责系统维护升级。

本系统使用前端框架MUI，使用hbuilder打包apk、ipa。

后端使用开源框架Jfinal、Druid。

主要难题就是微信端、android、ios三端兼容问题。以及图片处理、视频拍摄等。
项目地址：http://www.chanceland.cn

[WebApp mui&H5+ 用户头像处理之选择照片并剪切（Native.js for Android）](https://blog.csdn.net/sinat_25926481/article/details/53189686)

[解决ios h5 input输入框被输入法弹出一块区域](https://blog.csdn.net/sinat_25926481/article/details/53840614)

## 郑州宇昶软件科技有限公司 （ 2016年4月 ~ 2017年4月 ）

### 高校精品课程及教务管理系统 

高校的精品课程网站、教务系统，页面采用Html ,CSS, JQuery等技术，后台使用Hibernate, Struts2 ,Spring3 的MVC架构，主要应用为hibernate的ORM，struts2 的OGNL, 标签库，拦截器，Spring的AOP等。

研发精品课程前后端、负责文件服务器的设计、开发教务系统考试系统，题目的导入导出，在线遍题、随机出卷、评卷等功能。

使用POI导入导出试卷。

### 深圳医疗管理系统兼APP 

系统是针对肺结核患者管理来开发的，系统分电脑管理端和手机客户端APP。

本系统以患者关爱为主导思想，通过手机 APP督导患者服药、提醒查痰、提醒复查、提醒超时未服药等；方便患者就诊取药；记录患者服药过程；实现对药品管理、对患者管理、统计患者分布区域；为管理提供数据支撑。

页面采用Html ,CSS, JQuery等技术，后台使用Hibernate, Struts2 ,Spring3 的MVC架构，主要应用为hibernate的ORM，struts2 的OGNL, 标签库，拦截器，Spring的AOP等。

APP使用H5制作，使用hbuilder打包apk。

负责架构设计、数据库原型设计、部分功能实现。独立开发H5 APP医生端，APP接口。项目的部署、维护。

### 易幼堂管理系统 

易幼堂管理系统以一个以ERP与电商集一体的幼儿保健管理系统，具有总店系统、分店端系统、技师WebAPP、会员WebAPP。

页面采用Html ,CSS, JQuery等技术，后台使用Hibernate, Struts2 ,Spring3 的MVC架构，主要应用为hibernate的ORM，struts2 的OGNL, 标签库，拦截器，Spring的AOP等。

独立设计开发易幼堂分店管理系统、WebApp端所有接口，协助开发易幼堂分店管理系统。独立负责系统后期的全部维护、升级、部署。

## 郑州轻工业软件学院实验室 （ 2015年4月 ~ 2016年4月 ）

### 郑州轻工业软件学院Oracle数据库在线视频学习网站 

本项目是郑州轻工业软件学院Oracle数据库在线视频学习，类似于慕课。

页面采用Html ,CSS, JQuery,bootstrap等技术。

后台使用Hibernate, Struts2 ,Spring3 的MVC架构。

服务器使用Tomcat。

本系统是内网系统，文件流使用FTP传输，未使用ffmpeg对视频进行TS切片

负责项目中的管理员的设计、权限控制、视频的上传播放与检索、论坛的设计与实现。

# 教育经历

#### 周口师范学院 2016/9-2018/7 

##### 本科|软件工程

专业描述：在校所学课程有MySQL、Android、PHP、HTML5、Java、数据结构、计算机网络、操作系统等。

毕业设计：TB医患帮

#### 郑州轻工业学院 2014/9-2016/7

##### 大专|软件技术

专业描述：	在校所学课程有SqlServer、Android、Java、数据结构、计算机网络等。

毕业设计：微信公众号二次开发设计与实现（微信机器人），已开源：[WeChat-robot](https://github.com/zhuzhiqiang18/WeChat-robot)

# 在校情况

## 荣誉

- 2017/11	第三届河南省“互联网+”大学生创新创业大赛 三等奖（省级） 
- 2017/9	中国青年创新创业大赛河南分赛 APP类 创意组 优秀奖（省级） 
- 2017/6	国家励志奖学金（国级） 
- 2015/11	第四届中国创新创业大赛优秀团队奖（省级） 

# 技能清单

以下均为我熟练使用的技能

- Web开发：Java|PHP
- 框架：Spring/SpringMVC/Hibernate/Mybatis/SpringBoot/Jfinal/ThinkPHP
- 前端框架：Bootstrap/Jquery/HTML5/layui/Amaze UI/mui
- IDE：eclipse/Myeclipse/IDEA/hbuilder
- 数据库相关：MySQL/SqlServer
- 版本管理、项目管理：Svn/Git/Maven
- 云服务器：百度云/腾讯云/AWS/阿里云
      
      

------

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
      
