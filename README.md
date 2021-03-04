# tuya-iot-device-sdk-c-v1
This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.For more information, please check Tuya Developer Website.

一、方案标题
==
智能宠物喂食器

二、方案应用场景
==
在主人短暂外出期间，由于主人无法照顾到自己的宠物，可能会交由宠物店或者寄放在朋友家，宠物店花费较高且其他环境宠物可能适应较差导致生病等，所以制作一款宠物自动喂食器，可以在主人不在家的期间为宠物提供食物和水且主人在远端可以实时控制食物量，并且通过AI算法计算宠物每日进食量进而判断宠物日常状态（失落、无感、开心）。

三、开发计划
==
3月30前完成.
1）3月10前准备物料
  涂鸦三明治直流供电电源板、涂鸦三明治 Wi-Fi MCU 通信板（WB3S）、减速电机、NUCLEO-G071RB、红外模块
2）3月10-15日硬件搭建
  1、宠物进食器的外壳制作（猫粮通过管道输出，电机控制阀门、阀门控制食物）通过时间X体积大致计算食物量便于后期通过定时器控制食物量的多少
  2、MCU连接电机、红外（监测猫咪如果在食物口待的时间超过3s就出食物，出完食物后红外关闭，等待10min重新开启）
3）3月15-20日软硬件联调
  1、实现电机控制
  2、实现红外检测
  3、wifi连接公网
4）3月20-25日软硬件云端操作+AI
  1、将数据上传云端进行阈值控制
  2、将数据通过百度API进行处理
5）3月30日前整体调试。
