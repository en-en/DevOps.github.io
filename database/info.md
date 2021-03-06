## 高可用
高可用是指通过设计减少系统不能提供服务的时间。
如果系统一直能不间断提供服务，我们可以说系统的可用性是100%；
如果系统在时间单位内有1%的时间不能提供服务，我们可以说系统的可用性是99%.

保证系统高可用，架构设计的核心准则是：冗余。

有了冗余之后，还不够，每次出现故障需要人工介入恢复势必会增加系统的不可服务时间。所以，又往往是通过“自动故障转移”来实现系统的高可用。

所以，在方法论上，高可用是通过冗余+自动故障转移来实现的。

整个互联网分层系统架构的高可用，又是通过每一层的冗余+自动故障转移来综合实现的

总结：

1、高可用是指通过设计减少系统不能提供服务的时间；

2、在方法论上，高可用是通过冗余+自动故障转移来实现的。