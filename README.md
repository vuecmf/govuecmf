# govuecmf

#### 介绍
govuecmf命令行工具

## 环境要求
* MySQL >= 5.7
* Go >= 1.19

## 安装govuecmf命令行工具

~~~
go install github.com/vuecmf/govuecmf@latest
~~~

注意：**以下操作均在命令行中执行**

## 安装

创建新项目

~~~
mkdir myproject
cd myproject
govuecmf init myproject
~~~


## 初始化数据

修改config/database.yaml文件中数据库连接配置

然后执行如下操作，进行数据初始化

```
govuecmf migrate init
```
更多命令操作，可执行如下，查看帮助
```
govuecmf -h
```