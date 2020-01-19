## **使用说明**
###步骤
####1.安装好docker软件

####2.进入docker目录
`cd docker`

####3.启动
启动前注意80等端口是否被其他软件占用<br/>
`docker-compose -p indexlin up`

####4.本地host文件添加解析
127.0.0.1 php724.demo.com<br/>
127.0.0.1 php5532.demo.com<br/>
127.0.0.1 php724.demo.com<br/>

####5.访问
php724.demo.com<br/>
php5532.demo.com<br/>
php724.demo.com<br/>

####6.添加其他项目
仿照已有的项目。<br/>
在server目录下添加项目。<br/>
在docker/nginx/conf.d目录添加nginx配置。<br/>
重启docker服务
<br/>`docker-compose -p indexlin down && docker-compose -p indexlin up`
host文件添加好相应的解析




