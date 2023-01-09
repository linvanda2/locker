Redis Locker
----
基于redis实现的分布式锁，主要基于 `setnx` 实现

注意：该锁只是分布式锁的一个简化版实现，能满足绝大部分业务场景需求。Redis 分布式锁的完整实现原理请参见本人博客：

[循序渐进 Redis 分布式锁（以及何时不用它）](https://www.cnblogs.com/linvanda/p/16393316.html)

参考文章：
[Redis 官网文档](https://redis.io/topics/distlock)

