# vagrant

配置端口转发

```
config.vm.network "forwarded_port", guest: 80, host: 8080
```



## MobaXterm

**Execute `vagrant ssh-config > vagrant-ssh` in directory which Vagrantfile in.**

**Start bash session in MobaXterm**

**Add scripts in "Advanced Shell settings"**

```cmd
cd /drives/D/data/VirtualBox\ VMs/Ubuntu-18_01    #  Dir Vagrantfile in.
ssh -F vagrant-ssh default
```

![img](https://gyazo.com/7a675d10bfa494dd8a6a9af3924d3e0b.png)
https://gyazo.com/7a675d10bfa494dd8a6a9af3924d3e0b





# Linux



> [Bash Reference Manual](https://www.gnu.org/software/bash/manual/html_node/index.html#SEC_Contents)



## Bash



### 6 Bash特性



#### 6.2 Bash的启动文件

启动顺序


1. `/etc/profile`
2. `~/.bash_profile`
3. `~/.bash_login`
4. `~/.profile`



bash退出时执行 `~/.bash_logout`















# 架构

![img](https://gyazo.com/767feaf02c06650976aaea638522d734.png)
https://gyazo.com/767feaf02c06650976aaea638522d734

## 什么是前端架构?

### 浏览器优化技术有哪些?

### 什么是CDN?

### 什么是动静分离, 静态资源独立部署?

### 图片服务指的是什么?

### 什么是反向代理?

### DNS是什么?



## 应用层架构

### 什么是负载均衡? 有什么用?

### 什么是session?

session是一个特定的周期, 这个周期内的信息是被保持的.

### 为什么要将动态页面静态化?

业务拆分

虚拟化服务器



## 服务层

提供基础服务的节点, 采用分布式集群部署.



### 分布式消息

异步 解耦

### 分布式服务

### 分布式缓存

### 分布式配置



## 存储层

### NoSQL

### 关系型数据库

### 分布式文件存储系统

### 数据同步



## 后台

### 数据仓库

### 搜索引擎

### 推荐系统



## 数据采集与监控

### 浏览器端

* 用户行为



### 服务端业务数据

* 用户请求
* 队列数据
* 服务状态



### 服务器性能数据

CPU 磁盘 网络 内存 文件句柄 线程数



### 系统监控

收集并分析客户端和服务器端的数据, 以图形或文本形式展现结果, 方便用户进行查看. 对系统异常进行自动处理.

* 节点健康状况
* 数据分析
* 节点自动管理



### 系统报警

通过分析系统监控数据, 当达到预设的条件时, 通过短信, 邮件, 电话等形式通知用户及时进行干预.



## 安全架构

web攻击

数据保护



## 机房架构







