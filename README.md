# 使用说明


# 更新说明



## 依赖库：

```sh
go get -u gopkg.in/ini.v1

go get github.com/kataras/iris/v12@latest

go get -u github.com/jinzhu/gorm 

go get -u github.com/unknwon/com

go get -u github.com/streadway/amqp
```

# 秒杀系统性能提升

- [x] 单机系统：不加锁超卖现象
- [x] 单机系统：使用互斥锁解决超卖现象
- [x] 单机系统：使用悲观锁解决超卖现象
- [x] 单机系统：使用乐观锁限制超卖现象
- [ ]  利用MQ进行流量削峰
- [ ]  其他限流策略
- [ ]  Nginx负载均衡
- [ ]  读写分离与分表分库
- [ ]  CDN内容分发网络
- [ ]  流量防刷和反爬虫