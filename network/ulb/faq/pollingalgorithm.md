{{indexmenu_n>20}}


# 轮询算法能否使所有服务节点请求数均衡？

负载均衡的轮询算法是针对连接的。同一个TCP连接，不会被同时负载到两台后端服务器。若同一个连接上会发送数量不确定的多个请求，则可能会导致后端服务器上统计到的请求数不同。

[[https://github.com/UCloudDocs/UCloud-document/issues/3|{{https://static.ucloud.cn/e7fec9d74c744c448d757fad04fe1bcb.png}}]
