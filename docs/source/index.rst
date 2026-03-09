什么是SlimeVR？
----------------

SlimeVR 是一套开源硬件传感器和软件，旨在实现虚拟现实中的全身追踪 (FBT)。该项目的设计理念是打造一个可定制、可修改且可根据用户需求进行调整的系统。

SlimeVR 是一款低成本的虚拟现实全身追踪解决方案。它采用前向运动学，通过计算每个追踪器基于其旋转的位置来构建人体模型。唯一的固定点是您的头显，它作为主要参考位置。

由于头显是唯一的固定数据点，SlimeVR 不需要像灯塔这样的额外追踪设备。它依靠惯性测量单元 (IMU) 来追踪每个设备的旋转。使用的 IMU设备 越多，可用于追踪身体的点就越多。

正向运动学是根据骨骼角度计算身体部位（例如脚或手臂）位置的过程。给定关节（例如膝盖或肘关节）的位置，正向运动学可以告诉你脚或手臂在空间中的位置。这就像计算当你以某种方式弯曲腿时，你的脚会去哪里一样。

店铺信息
--------

1 - SlimeVR BNO085 全身追踪 VR动捕 VrChat 支持Qi无线充电 WIFI版：

https://item.taobao.com/item.htm?abbucket=18&id=897037905781&mi_id=00002nJM-nT4SrzJvCX-DXNCWgIYdZR5nogZDtkklmH-1nA&ns=1&priceTId=215042d717730709261307375e1923&skuId=5947624629920&spm=a21n57.1.hoverItem.1&utparam=%7B%22aplus_abtest%22%3A%22255e5ac3401564486a3023590ac344fa%22%7D&xxc=taobaoSearch

2 - Smol Tracker SlimeVR Butterfly Trackers 长续航 非WIFI

https://item.taobao.com/item.htm?id=984021203465&mi_id=0000KXQnUvNbCbbFXQon9z7e703rEPor-f_2vUaJ2fKkJ10&spm=a21xtw.29178619.0.0&xxc=shop&skuId=5947631261930


联系方式
--------

如果有需要交流可以加微信: 

.. figure:: ./_static/images/wechat_bitdeck.jpg
   :align: center
   :alt: 个人二维码
   :figclass: align-center
   :scale: 50%

.. toctree::
   :maxdepth: 6

   SlimeVR/SlimVR_introduction
   SlimeVR/Software_installation
   SlimeVR/SlimVR_add_imu_log

