# mall

[![Build Status](https://travis-ci.org/totalo/mall.svg?branch=master)](https://travis-ci.org/totalo/mall) [![codecov](https://codecov.io/gh/totalo/mall/branch/master/graph/badge.svg)](https://codecov.io/gh/totalo/mall)

### 项目简介

为开源项目，对所学技术进行总结和实践

### 选用技术

- Spring Boot
- Spring Cloud Alibaba
- Mybatis
- MySQL

### 功能特性

- #### [用户中心](documents/user_center/user.md)

  根据用户权限分为：系统管理员、普通用户、游客

- #### [后台系统](documents/system/system.md)
  
  根据用户权限，开放相应的后台权限，代码生成仅针对开发人员开放

  - 代码、模板自动生成
  - 用户内容管理
  - 数据中心

- #### [Today](documents/system/system.md)

  UI参考IOS系统App Store中的Today页面，注册用户通过提供的模板发布内容，其他用户仅可浏览已关注的用户发布的内容。
  
  可选内容模板

  - 小视频
    视频可选高宽比例：21:9、16:9、4:3
  - 文章
    使用markdown格式语法，参考简书、GitHub
  - 商品橱窗
    展示商品详情，提供收藏、分享、加入购物车、购买等选项
  - 商品链接
    可选商品图文链接、视频链接

### Change Log

- #### v0.0.1 (2020/8/31 21:23 +00:00)
  
  项目发布，编写ReadMe文件，对项目进行构思

- [更多更新日志](documents/change_log/change_log.md)