# 图书管理系统 java1004

## 项目概述

图书管理系统是一个基于JavaWeb技术栈的应用，主要用于实现图书馆的图书管理、用户借阅等业务需求。

## 技术栈

- **架构：** B/S、MVC
- **前端：** JSP、JSTL、Bootstrap
- **后端：** Servlet、JavaBean、DAO
- **存储：** MySQL 5.7（使用DBUtil连接）
- **开发工具：** IDEA、Navicat

## 功能模块

### 用户角色

- 登录
- 注册
- 首页
- 图书搜索
- 图书借阅
- 还书
- 历史借阅
- 修改信息
- 修改密码
- 退出

### 管理员角色

- 登录
- 首页
- 图书管理（增删改查）
- 用户管理（增删改查）
- 分类管理（增删改查）
- 用户借阅信息
- 用户归还信息
- 修改信息
- 修改密码
- 退出

## 系统角色

- 用户：可以执行借书、还书、查询等操作。
- 管理员：负责图书管理、用户管理以及分类管理。

## 运行环境

- 服务器：任何支持JavaWeb的服务器，如Tomcat
- 数据库：MySQL 5.7
- 客户端：现代浏览器

## 目录结构

```
/ -- 根目录
|-- /web -- Web内容目录
|   |-- /WEB-INF -- Web-INF目录
|   |   |-- web.xml -- 配置文件
|   |   |-- /classes -- Java类文件
|   |   |-- /lib -- 项目依赖库
|   |-- /jsp -- JSP页面
|   |-- /css -- 样式文件
|   |-- /js -- JavaScript脚本文件
|-- /db -- 数据库相关
|   |-- schema.sql -- 数据库结构文件
|   |-- data.sql -- 初始化数据文件
```

## 部署步骤

1. 安装MySQL 5.7数据库。
2. 创建数据库，导入`/db/schema.sql`与`/db/data.sql`文件。
3. 部署至JavaWeb服务器（如Tomcat）。
4. 访问系统首页进行操作。

## 核心亮点

- 结构清晰，易于维护。
- 前后端分离，基于MVC模式。
- 使用JSTL和Bootstrap，提高前端开发效率。
- 使用Servlet处理动态请求，高效稳定。
- 数据库连接采用DBUtil，简化数据库操作。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img10.360buyimg.com/ddimg/jfs/t1/337331/38/15165/16837/68d7de77F5cc2a0e1/f86d75e08bac60c3.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/241285/30/30538/60063/68d7de77Feb4843d5/42826c2c9d0d864e.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/334215/36/17761/38043/68d7de78Fa1ed8c34/f1cef029ac823e9e.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/331514/34/17641/39205/68d7de79F93b7eb92/f89abae5814e506d.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/343374/16/6618/22613/68d7de79F520d376a/f98b8e7e6c979ce8.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/241251/8/30797/49288/68d7de7aF1c11938d/3fd817bd4c193977.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/336029/22/15393/35417/68d7de7aFf0fe94e7/c5639e0313c4abab.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/341583/22/7481/56315/68d7de7bF89905d97/f8446310a746020f.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/325692/28/24835/18944/68d7de7bF27b400f8/f2b78be4c1bc02a8.jpg)

