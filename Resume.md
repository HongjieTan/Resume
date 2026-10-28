 <center>
     <h1>谭宏劼</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             18062711141
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             hongjietan@outlook.com
         </span>
         ·
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/HongjieTan">HongjieTan</a>
         </span>
     </div>
 </center>

 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息

 - 男，1998.9
 - 求职意向：嵌入式软件，AI算法
 - 期望薪资：20k
 * 工作经历主要集中于STM32嵌入式开发，研究以小模型架构设计以及嵌入式部署为主。个人业余维护了一台个人使用的小模型训练机器，以及一台基于Debian系的个人NAS机器。

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 硕士，熊本大学大学，信息电气专业，2024.4~2026.3
- 学士，武汉工商学院，物联网工程专业，2017.9~2021.7
- 英语托业685，日语N2

## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **武汉中智讯有限公司，智联网教具研发组，嵌入式软件工程师，2021.9~2022.9**

   接手被解散团队遗留的STM32智联网教具系列6款产品的系统移植和升级维护。

- **重庆瑞普机器人研究院，嵌入式软件实习，2020.7~2021.4**

   参与了公司正在研发中的电力巡检机器人的STM32下位机开发以及后续的AGV的下位机控制系统开发。

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **边端AI本地识别皮肤病**

  *使用到的技术*
    * 平台: TensorFlow+STM32h743
    * AI: 训练及微调，模型量化，模型剪裁，架构设计
    * 嵌入式: OV5640摄像头，PCF8574总线控制，DMA，I2C，LCD屏

  硕士阶段研究方向，独立完成了课题构思、开题、开发、实验全流程。以MobileNetV3为骨架网络，替换了网络浅层部分，并重新设计了网络结构，在量化后集成嵌入式设备演示了皮肤病分类，和其他同类小模型同条件下相比精度损失低于0.5%的情况下削减了超过30%的ROM占用，并减少了运行时ram使用量。

- **智联网研用具**

  *使用到的技术*
    * 智能腕带: 指纹，非侵入式血氧监测，LCD屏...
    * 智能体温计: 嗡鸣器，红外体温仪...
    * 智能售货机: ESP32wifi/BLE，摄像头，弹簧电机，MQTT...

  将6款产品从原 uCOS系统移植到了 FreeRTOS，替换了新款指纹模块驱动，重构了部分同时含有摄像头和lcd屏产品的内存使用和分配逻辑，解决了系统移植后RAM占用过多的问题等。为系列产品撰写了使用文档，便于教学者使用。

- **机器人下位机**

  *使用到的技术*
    * 平台: STM32
    * 总线: SPI，I2C，CANopen...
    * 外围模块: 碰撞条，无线遥控的红外接收器，电机控制器...

  实现了机器人下位机的控制系统，可以接受控制系统驱动电机控制四轮机器人/两轮AGV移动，收到碰撞信号紧急制动。

## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- ★★★ C/C++
- ★★☆ Python，TensorFlow，模型量化，模型剪裁，训练及微调
- ★★☆ Linux，Shell
- ★★★ STM32，SPI，I2C
