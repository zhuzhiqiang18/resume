
# 联系方式
- 手机：15896731218
- Email：1048222543@qq.com
- QQ：1048222543
# 个人信息

 - 朱志强/男/1993 
 - 本科/周口师范学院计算机与科学技术学院
 - 工作年限：3年
 - 技术博客：https://blog.csdn.net/sinat_25926481
 - Github：https://github.com/zhuzhiqiang18
 - 期望职位：Java开发工程师
 - 期望薪资：12k-15k

# 工作经历

## 三益（郑州）贸易有限公司 （ 2017年8月 ~至今 ）

### 全民外贸 
全民外贸V1.0 主要研发后台管理系统 APP端API的开发设计。

后端管理系统使用Jfinal开源框架 主要做到急速开发，页面引擎使用beetl渲染更快速。

数据库使用mysql，数据源采用阿里开源Druid，缓存使用EHCache框架。

全民外贸V2.0 开发PC端， 使用SpringBoot重新构建API，后端管理与PC、API完全分离。为了能够更好SEO收录 PC端没有采用静动态页面分离 而是采用传统后端页面渲染，页面引擎同样采用Beetl。

项目使用git管理，目前托管到阿里云code。

V1系统和V2系统会同时操作一张表，为了保证数据统一性，使用Redis做互斥锁。PC、API使用Redis做缓存。

代理服务器使用Nginx，使用Nginx的主备做不停机维护。

系统SMS提醒使用ActiveMQ消息中间件解耦。

在本项目中本人既是Leader也是高效的执行者角色。本人独立完成了整个项目的设计工作，并参与开发与测试等环节中。

在项目中主要完成了后台管理以及PC端、API接口、以及服务器运维等。

目前流水过亿元。

项目地址：www.qmwm777.com




### StarDay中日跨境电商平台 
传统公司转型为互联网公司，带领小规模团队（IOS一名，ANDROID一名，Java后端两名）。负责整体项目的架构设计和实现，由于前期人员少，开发时间短，采用了开源社区JFinal框架作为主导架构，配合阿里开源的DRUID连接池。后台管理页面采用Jquery、Amaze UI、layer等优秀前端框架。

电商项目高并发、高响应、低延迟。根据以往开发项目经验，对图片按照一定比例进行压缩，Tomcat对静态文件不友好，使用Nginx搭建文件服务器，使动静态文件分离，加快响应减少网络延迟。

考虑前期项目资源较少，并没有引用redis而是使用Java原生的Cache框架EHCache，缓存频查少改的数据，并采用一定的算法进行淘汰。

后台管理页面，不是使用传统的jsp，而是采用开源的模板引擎Beetl加快了页面渲染速度。

API传输数据格式使用JSON,JSON的解析使用阿里开源的fastjson。

APP端：组合商品详情HTML页，并使用CSS以及JS优化页面，图片延迟加载等。

权限与操作菜单采用存储表的方式，后台分配角色以及操作菜单，根据用户角色的不同展现不同的菜单列表，并防止商家横向越权和纵向越权。

数据库采用MYSQL，对经常查询的列加索引，优化查询速度。表中存在必要的冗余，解决多表联合费时查询操作。

本项目中遇到的难点就是SKU的设计以及对接日本本土信用卡支付、便利店支付。

项目地址：www.stardaymart.com

### StarDay海外仓WMS系统 
本系统分为客户端与管理端，客户端可以上传商品、申请入库、申请出库、充值、申请移除、申请换标（多个阶段）等，管理端主要是对以上功能的审核确认以及客户信息的维护等。

本系统使用SpringBoot构建，使用Mybatis作为数据层框架，Druid作为数据连接池，redis作为缓存组件。

本系统对接钉钉机器人，有新业务进度及时推送到钉钉群。
项目地址：www.stardaymart.cn
  
## 郑州宇昶软件科技有限公司 （ 2016年10月 ~ 2017年4月 ）
### 创联工场 
二次开发项目。独立负责后台数据管理系统新功能的设计与实现，整合旧功能，服务器部署。协助前端实现微信、android、ios。优化三端兼容。打包apk、ipa。上架appStore、360、应用宝、百度等应用商店，负责系统维护升级。

本系统使用前端框架MUI，使用hbuilder打包apk、ipa。

后端使用开源框架Jfinal、Druid。

主要难题就是微信端、android、ios三端兼容问题。以及图片处理、视频拍摄等。

项目地址：http://www.chanceland.cn

[WebApp mui&H5+ 用户头像处理之选择照片并剪切（Native.js for Android）](https://blog.csdn.net/sinat_25926481/article/details/53189686)

[解决ios h5 input输入框被输入法弹出一块区域](https://blog.csdn.net/sinat_25926481/article/details/53840614)

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
#### 周口师范学院 
##### 本科|软件工程
专业描述：在校所学课程有MySQL、Android、PHP、HTML5、Java、数据结构、计算机网络、操作系统等。

毕业设计：TB医患帮
#### 郑州轻工业学院 
##### 大专|软件技术
专业描述：	在校所学课程有SqlServer、Android、Java、数据结构、计算机网络等。

毕业设计：微信公众号二次开发设计与实现（微信机器人）

# 在校情况
## 荣誉

* 	第三届河南省“互联网+”大学生创新创业大赛 三等奖（省级） 

* 	中国青年创新创业大赛河南分赛 APP类 创意组 优秀奖（省级） 

* 	国家励志奖学金（国级） 

* 	第四届中国创新创业大赛优秀团队奖（省级） 
    
# 技能清单
以下均为我熟练使用的技能

- Web开发：Java|PHP
- 框架：Spring/SpringMVC/Hibernate/Mybatis/SpringBoot/Jfinal/ThinkPHP/dubbo
- 前端框架：Bootstrap/Jquery/HTML5/layui/Amaze UI/mui
- IDE：eclipse/Myeclipse/IDEA/hbuilder
- 数据库相关：MySQL/SqlServer
- 版本管理、项目管理：Svn/Git/Maven
- 云服务器：百度云/腾讯云/AWS/阿里云
      
      
---      
# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
      
