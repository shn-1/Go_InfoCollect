# Go_InfoCollect

收集信息主要用到的是gopsutil库和直接调用linux命令两种方法

gopsutil库是python中的psutil库在Golang上的移植版，主要用于收集主机的各种信息，包括网络信息，进程信息，硬件信息等
具体的使用方法可以查看官方文档，这里不再赘述

调用linux的命令，然后通过管道回显得到结果

输出形式均为JSON文件


