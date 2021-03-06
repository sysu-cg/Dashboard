# 雪人快跑

## 运行程序

点击【Running_Snowman.exe】运行程序。



## 游戏玩法

雪人快跑是一款沙盒生存游戏。在阳光的照射下，雪人会不断融化损失雪量，当雪量见底时游戏结束。雪量如下

![snow](https://github.com/sysu-cg/Dashboard/raw/master/FinalProject_v0/bin/image/snow.png)

玩家操控雪人探索场景，通过收集冰晶来回复自身的雪量。冰晶如下

![ice](https://github.com/sysu-cg/Dashboard/raw/master/FinalProject_v0/bin/image/ice.png)

随着昼夜变换，雪人存活三天后将迎来极夜，玩家获得游戏胜利。



## 操作说明

鼠标移动进行视角变换，键盘按键【W】【S】【A】【D】控制雪人前后左右移动，空格键为跳跃。雪人遇到物体会被阻碍，吃到冰晶可以回复雪量，跳跃可以爬到台阶或者石头上。游戏中的菜单栏如下

![menu](https://github.com/sysu-cg/Dashboard/raw/master/FinalProject_v0/bin/image/menu.png)

菜单栏可以设置六个属性，其中前五个属性可以通过键盘按键【1】【2】【3】【4】【5】切换设置，最后一个属性需要鼠标拖动设置。六个属性的功能如下

+ Camera：是否进行视角移动。Freeze冻结视角，显示鼠标；Move移动视角，隐藏鼠标。只有冻结视角并显示鼠标时，玩家才能拖动设置最后一个属性。
+ Shadow：是否渲染阴影。Disable关闭阴影渲染；Enable开启阴影渲染。渲染阴影计算量大，玩家在画面卡顿时可以选择关闭阴影渲染。
+ Particle System：是否下雪。Disable关闭雪花粒子系统；Enable开启雪花粒子系统。雪花可能遮挡视线，玩家可以选择关闭下雪特效。
+ Stencil Test：是否透视冰晶。Disable关闭冰晶透视模板测试；Enable开启冰晶透视模板测试。冰晶可能被物体遮挡，玩家可以选择开启冰晶透视来确定大致方位。（外挂一）
+ Blood Locking：是否锁血。Disable关闭锁血状态；Enable开启锁血状态。雪量可能难以支持雪人的行动，玩家可以选择锁血来探索更多场景。（外挂二）
+ Time Rate：时间速率。玩家可以调节游戏的时间速率，加速游戏进程，感受昼夜变换的阴影变化。