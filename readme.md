# GeoHash的C++实现

## 简介

>实现对当前点的输入(目前支持100万个单独定位点)，使用共享内存进行存储(进程即使挂掉不影响使用，毫秒级的重启加载)。
>支持给定区域的查找（任意半径）。找到指定范围内的所有定位点。
>用于车辆和人的GPS定位点区域跟踪和查找，实现最快效率的区域命中。