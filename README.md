# SelectMaster
个人实践项目：

1、通过代码实践分布式网络选主的过程

2、若果第一步实现，实现分布式锁工具（中心）

3、若果前两步实现，处理脑裂现象

4、若果前三步实现，处理分布式网络中消息传递的性能问题

假如...
2018-04-20:

1、处理socket连接，单机的网络时延比我想象的要低很多，但是这是一个不断测试的值；

2、下一步要处理【quorum】法定机器数量的问题，quorum的证明暂时还不会，但是能理解它的原理，保
证无论以哪种方式确定quorum，两个quorum之间总有共享机器；


2018-04-21:

1、还是没有完全理解，逻辑时钟漂移依然存在，网络时延到底怎么判断

2、代码在求全后，已经可以在两个机器之间进行选主

明天的工作：

处理quorum的问题，解决网络时延的问题

2018-04-22:

1、处理n(n>=3)台主机选主的问题

