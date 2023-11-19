# Windows下Ubuntu20.04双系统安装指南
本文档是Ubuntu双系统的操作指南。在电脑存在Windows情况下安装Ubuntu20.04作为第二操作系统     
本文参考"从零制作自主空中机器人"课程     
github链接: https://github.com/ZJU-FAST-Lab/Fast-Drone-250     
B站视频链接: https://www.bilibili.com/video/BV1WZ4y167me
## Step0: 前期准备
- 在电脑磁盘中清理出80G以上存储空间、准备一个8G以上空U盘
## Step1: 在Windows下载Ubuntu20.04镜像
- 镜像站地址：`http://mirrors.aliyun.com/ubuntu-releases/20.04/` 
- 下载 `ubuntu-20.04.4-desktop-amd64.iso`
## Step2: 下载镜像烧录软件UltraISO
- UltraISO官网：`https://cn.ultraiso.net/`
## Step3: 格式化U盘并制作Ubuntu启动盘
- U盘格式化

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/8baec5d3-9f08-482a-92e5-ea0b766539fb" width="25%">
- 打开UltraISO,选免费版继续试用

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/6b73505c-15c4-4655-ad5a-bc30f677e38a" width="25%">
  
- 打开下载的镜像

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/6850b18d-a1eb-4351-904a-c575317ee8d7" width="25%">    
  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/6027cc4e-4582-4b2e-beb2-8817be12cfd3" width="40%">   
- 写入硬盘镜像
  
  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/73ffea14-5cef-4ad2-bbe7-56efcfd19da6" width="25%">
- 选择U盘，等待写入  

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/b027080d-b434-494d-9b17-5de1086984c1" width="25%">
## Step3: 释放磁盘空间
- 以管理员权限进入进入控制面板-系统和安全-创建并格式化硬盘分区

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/ac7c0c0f-0d70-495d-8226-2b50b0c937c8" width="75%">
  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/82828ae2-a215-471c-9e9c-08c7239459e6" width="75%">
- 选择你要分割的分区（有80G以上空闲的分区），右键，选择压缩卷

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/d7ec9268-7d6a-4a03-b27f-87be3fb2391f" width="50%">
- 输入要压缩的空间量（单位为MB），该大小为你希望分给Ubuntu系统的大小（图中用2000MB示意）

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/7cbfe86b-2b96-4c04-bdf2-50ea2ab4a065" width="50%">
- 此时，在你压缩的磁盘后将会出现一块未分配的磁盘分区，大小为你输入的压缩空间量

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/b38fc73d-8788-4e83-ac7d-63b7a9efbdd4" width="50%">
## Step3: 重启电脑进入BIOS界面
- 首先查询你的电脑进入BIOS界面的方式

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/131d8996-4b39-4fd8-b8d3-e811553a48b9" width="50%">
- 重启电脑，开机同时连续按F2（你的电脑进入BIOS界面的方式），当电脑品牌徽标出现后，电脑会进入BIOS界面/UEFI界面

  <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/9a4c365c-c46b-4404-b77e-61809acf0b6f" width="50%">
- 进入Advance模式下，找到安全启动，关闭安全启动项     
  `Security（安全）`—`Secure Boot（安全启动）`—`Disabled（关闭）`     
    <img src="https://github.com/qtjdyx/ZJUS/assets/116424162/d1cca790-5420-4763-bd86-e193eec5acfc" width="50%">
  
## Step4: 插入Ubuntu启动盘并用U盘启动
- 
## Step5: 安装Ubuntu操作系统
