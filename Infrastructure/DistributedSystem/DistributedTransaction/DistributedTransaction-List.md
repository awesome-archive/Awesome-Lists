[![返回目录](https://user-images.githubusercontent.com/5803001/38079637-ff0abcf0-3371-11e8-9b76-ad651620afc7.jpg)](https://github.com/wx-chevalier/Awesome-Lists)

# Distributed Transaction List

- [Why you should pick strong consistency, whenever possible](https://parg.co/U8P)

* [Distributed transactions and why you should care](https://towardsdatascience.com/distributed-transactions-and-why-you-should-care-116b6da8d72): If my product succeeds will this eventual-consistency thing come back to haunt me?

- [使用 Redis 实现分布式锁](http://blog.jobbole.com/95211/)

* [关于分布式事务、两阶段提交协议、三阶提交协议](http://www.hollischuang.com/archives/681)

* [深入理解分布式系统的 2PC 和 3PC](http://www.hollischuang.com/archives/1580)

* [分布式系统事务一致性解决方案](http://www.infoq.com/cn/articles/solution-of-distributed-system-transaction-consistency)

* [分布式系统的事务处理 ](http://mp.weixin.qq.com/s?__biz=MzA4NDc2MDQ1Nw==&mid=2650238031&idx=1&sn=d7ba7844f15d587c83906aedd073748a&scene=0#wechat_redirect)

* [分布式事务 2PC && 3PC](http://int64.me/2016/%E5%88%86%E5%B8%83%E5%BC%8F%E4%BA%8B%E5%8A%A12PC%20&&%203PC.html)

# 多阶段提交

- [分布式协议之两阶段提交协议(2PC)和改进三阶段提交协议(3PC)](http://www.mamicode.com/info-detail-890945.html)

- [关于分布式事务、两阶段提交、一阶段提交、Best Efforts 1PC 模式和事务补偿机制的研究](http://blog.csdn.net/bluishglc/article/details/7612811)

- [两阶段提交协议与三阶段提交协议](http://www.tuicool.com/articles/mARV3u)

# 分布式锁

- [高并发下本地锁+分布式锁](https://adamswanglin.github.io/wllock/)

- [基于 Consul 的分布式锁实现](http://blog.didispace.com/spring-cloud-consul-lock-and-semphore/)：  我们在构建分布式系统的时候，经常需要控制对共享资源的互斥访问。这个时候我们就涉及到分布式锁(也称为全局锁)的实现，基于目前的各种工具，我们已经有了大量的实现方式，比如：基于 Redis 的实现、基于 Zookeeper 的实现。本文将介绍一种基于 Consul 的 Key/Value 存储来实现分布式锁以及信号量的方法。
