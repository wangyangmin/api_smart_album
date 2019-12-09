## 智能毕业相册产品需求文档

| 发布日期 | 2019.12.2    |
| -------- | ------------ |
| 产品名称 | 青葱记忆相册 |
| 文档状态 | 进行中       |
| 文件主人 | 何俊鹏       |
| 设计者   | 何俊鹏       |
| 开发者   | 何俊鹏       |
| 测试者   | 何俊鹏       |



### （一）加值宣言：

目前市面上的毕业相册一般以纸质版或光盘刻录，这样的毕业相册能够满足基本的照片留念的功能，但随着人们对智能产品的需求的增长，纸质版或光盘的相册都满足不了。

在相册保存相片，写下寄语的基础之上，智能毕业相册利用图像识别API可以为你的相册里面的人物做筛选，点击一张图片里面的某个人物就可以迅速的调用图像识别API为你找到相册里同样有这人物的其他照片。

在毕业时刻，在毕业相册上写下的地址，会通过地图API形成联系网，即使天各一方依旧能够看到彼此的联系，同时在点击某个地址的时候就可以即时的通过地图API形成导航。

智能相册同一个班级的同学可以通过各自的身份识别，进入编辑自己在他人相册中的存档，在甜美的回忆中讲述着关于秘密的话题。

### （二）核心价值：（最小可行性产品）

智能毕业相册APP为人们提供了海量相片的储存问题，同时在存储的基础上提供了分类筛选功能，让用户更加方便快捷的查找珍贵的回忆；联系方式的存储，让用户轻点照片便可以联系某个好久不见的好友，同时如果需要的话也可以瞬间导航到其家中。

### （三）背景：

中国拥有全世界最大的学生群体，随着智能应用的普及，在很多生活的方面也得到了升级，但是在毕业留言相册上还是坚持着传统的纸质版和光盘刻录的方式保存照片，虽然也有了手机的图片库功能，但是由于手机照片数量的庞杂，毕业的回忆很难留存。智能毕业相册专门为毕业的学生留下各自的祝福寄语和青春回忆而制作。

### （四）目的：

智能毕业相册：让回忆动起来，让青春悦动吧！

### （五）目标：

 前期目标：

1.点击人像即可查看相关的照片。

2.可以做到实时联系，同时实时导航。

3.做到身份认证，写下对其他同学的寄语。

 后期目标：（目前不做）

1.学生的求学历程图（记录幼儿园开始的读书历程。）

2.班级圈的生活分享

### （六）用户：

毕业学生，记录孩子生活的宝妈

### （七）用户画像（痛点分析）：

 ①大学生小李每次回家想要找自己高中同学聚会的时候总是忘了同学家的地址。

 ②职场白领艾米在毕业后就常常会想起学生时代的生活，但是每次搬家的时候都会将相册忘了，或者是相册留在了家里 ，自己想看的时候相册就不在身边，很是苦恼。

③毕业时候总是匆匆忙忙的，小菊也是如此，在大学毕业之际也未能与心爱的男生说一句：“我爱你!”，如果简单的微信发信息的话也会很生硬，如果能够借助美好的记忆情节留下这美好的告白就好了。

### （八）用户需求:（使用的人工智能要反映到需求列表中）

| 用户案例                   | 对应功能 | 重要程度 |
| -------------------------- | -------- | -------- |
| 在照片（储存）中留下寄语   | 云储存   | 重要     |
| 通过头像进行人物筛选，分类 | 图像识别 | 重要     |
| 同学家路线导航             | 地图导航 | 一般     |


### （九）使用者交互与设计（axure产品原型）

![输入图片说明](https://images.gitee.com/uploads/images/2019/1202/203606_75049729_1829884.png "图片6.png")

![输入图片说明](https://images.gitee.com/uploads/images/2019/1202/203626_7db87a12_1829884.png "图片5.png")

![输入图片说明](https://images.gitee.com/uploads/images/2019/1202/203726_275a5a54_1829884.png "图片4.png")

![输入图片说明](https://images.gitee.com/uploads/images/2019/1202/203742_8ffab7ab_1829884.png "图片3.png")

![输入图片说明](https://images.gitee.com/uploads/images/2019/1202/203756_058af77f_1829884.png "图片2.png")

### （十）产品结构图

![输入图片说明](https://images.gitee.com/uploads/images/2019/1202/203805_627afade_1829884.png "图片1.png")

### （十一）API的运用：

1.图像识别：人物筛选

2.地图导航：家庭地址导航

3.云储存：照片以及留言信息存储
