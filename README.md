# lute

demo录像在lutedemo.mp4

项目截图：

![图片15](https://user-images.githubusercontent.com/71310491/143442691-bf5062a9-de1c-4571-81a5-46bfafc21ea0.png)

<img width="912" alt="图片16" src="https://user-images.githubusercontent.com/71310491/143443757-c36ec42d-1458-4b70-b611-d1f2ac375cb1.png">


市面上的虚拟乐器软件，基本上有两个特点：提供的乐器种类多为西洋乐器，如钢琴、吉他等。交互方式单一，如：鼠标，键盘输入。

这个demo是针对这两个问题提出的基于压力传感器和手戴式陀螺仪的虚拟乐器，选取的是中国民乐器琵琶。

琵琶演奏时竖抱，左手按弦，右手弹奏，音域涵盖3个八度，每个八度有7个全音和5个半音。

音源素材：

真实乐器录音。利用手机自带录音软件，并用Au降噪。

左手【压力传感器】用来确定音调。

比起手柄的好处：

1、用手柄光标来确定音位不如按压的方式来得直接，并且更符合现实的情况。

2、用手柄更容易造成误差。

3、在教学层面上，使用压力传感器更有利于用户养成肌肉记忆，而使用手柄没有这种作用。

![image](https://user-images.githubusercontent.com/71310491/143443129-809ba2fb-3f5e-4be5-b0b2-3dcd7dca85f0.png)

![image](https://user-images.githubusercontent.com/71310491/143443116-1484a7f7-c8ea-47af-8e2c-82cb796583d8.png)

![image](https://user-images.githubusercontent.com/71310491/143443122-fff6930b-57ce-4a55-9b43-b49d9c8e3a34.png)


操作：食指到小拇指的传感器控制音高，大拇指控制升半度。软件里面设置低音和高音的切换。


右手【陀螺仪】用来弹出声响。

比起kinect的好处：

1、更精确。kinect对于手势识别没有手戴式陀螺仪来的精确。陀螺仪可以识别三维空间中的平移、旋转、甚至是手腕的加速度等。

2、更不怕被遮挡。本项目是通过蓝牙信号传输的，而kinect红外摄像被遮挡就无法识别。

![image](https://user-images.githubusercontent.com/71310491/143443154-64100da6-855b-4fb0-9c64-59402622c9ef.png)

![image](https://user-images.githubusercontent.com/71310491/143443158-fbe2058a-d7e0-4e76-a501-c63f73d2ad05.png)

操作：

弹：手心由面向身体旋转为朝向地面

扫弦：在一定的时间内迅速位移大于一定长度

