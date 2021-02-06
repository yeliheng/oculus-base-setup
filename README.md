# oculus-base-setup

# 0X01 这个仓库有什么用？ #

通过这个仓库你可以在unity快速配置Oculus的开发环境。并且这个仓库中包含了Oculus quest/quest2的基本交互。如：控制器按钮交互、手部模型交互、贝塞尔曲线指针、传送。并且可在原来的基础上简单地进行攀爬，抓取等动作拓展。

# 0X02 参数说明 #

1. 运行环境：Unity 2019.x

2. 测试设备：Oculus Quest/Quest2、Oculus Rift（上述设备已通过测试，其他型号的设备请自行测试）

3. 依赖说明：本项目用到以下包(Packages)，按照从属关系列出：

   > Malimbe
   >
   > >Zinnia
   > >
   > >> VRTK

   以及最基本的Oculus Integration(在Unity的Asset Store下载)

   下文会给出Packages的下载地址。

#  0X03 开始使用 #

1. 克隆本仓库

   `git clone https://github.com/yeliheng/oculus-base-setup.git`

2. 用Unity打开本项目

3. 添加依赖。

   3.1.在Unity Asset Store下载Oculus Integration库，按照提示Upgrade和Restart。

   3.2.按照0X02的依赖说明依次导入所需的Package。顺序依次是：Malimbe->Zinnia->VRTK

   （导入包在Unity的操作：点击Window->Package Manager->+->Add package from disk->选择package.json文件即可）

   依赖包下载地址：

   链接：https://pan.baidu.com/s/11QO8DMKYVvK2jJB8IS2tlA 
   提取码：lw1i 

4. 进入play mode 体验。Enjoy yourself!

0X04 项目截图

![手模](https://cdn.yeliheng.com/%E6%89%8B%E6%A8%A1.png)

![传送和指针](https://cdn.yeliheng.com/%E4%BC%A0%E9%80%81%E5%92%8C%E6%8C%87%E9%92%88.png)



0X05 [Yeliheng的技术小站](https://www.yeliheng.com)





