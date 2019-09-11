# 项目详情介绍:

[https://juejin.im/post/5cdca7595188257cf051a06a](https://juejin.im/post/5cdca7595188257cf051a06a)

# Github:

后台管理 CMS: [https://github.com/czero1995/fancy-store-admin.git](https://github.com/czero1995/fancy-store-admin.git)

# 使用说明

### 1.配置文件和启动服务

`不同系统平台(Linux,Mac,Window)安装启动MongoDB和Reids的命令都不相同，请根据自己的环境安装和启动服务。`

- MongoDB、Redis 和七牛云存储的配置文件统一放在**config**文件夹
- 安装 MongoDB 并启动服务
- 安装 Redis 并启动服务

### 2.克隆项目

    git clone https://github.com/czero1995/fancy-store-server.git

### 3.安装依赖

    npm install

### 4.启动服务

    node main.js
### 5.注册

http://192.168.31.164:9527/api/admin/register
{
 "admin": "root",
 "pwd": "123456",
 "avatar": "", // 头像
 "roles": 1  // 0超级管理员  1普通管理员
}