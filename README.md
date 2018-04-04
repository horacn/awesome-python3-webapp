# awesome-python3-webapp

## 基于Python3.5开发的一个博客网站。

### 搭建开发环境
<br/>

首先，确认系统安装的Python版本是3.5.x：

···
$ python3 --version
Python 3.5.1
···

然后，用pip安装开发Web App需要的第三方库：

异步框架aiohttp：

```
$pip3 install aiohttp
```

前端模板引擎jinja2：

```
$ pip3 install jinja2
```

MySQL 5.x数据库，从官方网站下载并安装，安装完毕后，请务必牢记root口令。为避免遗忘口令，建议直接把root口令设置为password；

MySQL的Python异步驱动程序aiomysql：

```
$ pip3 install aiomysql
```

<br/>

### 项目结构

选择一个工作目录，然后，我们建立如下的目录结构：

```
awesome-python3-webapp/  <-- 根目录
|
+- backup/               <-- 备份目录
|
+- conf/                 <-- 配置文件
|
+- dist/                 <-- 打包目录
|
+- www/                  <-- Web目录，存放.py文件
|  |
|  +- static/            <-- 存放静态文件
|  |
|  +- templates/         <-- 存放模板文件
|
+- ios/                  <-- 存放iOS App工程
|
+- LICENSE               <-- 代码LICENSE
```
