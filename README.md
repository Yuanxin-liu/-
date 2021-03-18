# 皮肤管家
#### 1.项目介绍

这是一个护肤小程序，因此我们的界面设计的主基色是浅粉色调的，其他插图和图标等，也均采用了马卡龙色系，让使用者在进入小程序的第一刻就感受到轻柔温暖的“少女感”，来契合我们小程序的功能取向以及受众群体。在图标的设计、界面图片、界面设计上，我们也选择了简洁、卡通、有活力的的图片和图案，使得它变得更日常，迎合了这个小程序受众群体的审美。这种干净、轻柔的画风，也代表着一个桥梁，连接起我们前端设计与后端功能，护肤的目的是让我们的皮肤变得健康、白皙、柔嫩，而这也是我们前端画风设计的主要出发点。我们希望可以通过最直接的浅色画面设计和简洁功能设计，来吸引使用者，来增加体验者长期使用的可能性。

**1.1** **关键技术**

（1）微信云开发的使用。在“皮肤管家”这个小程序的记录页面中，为了更直观的让用户看到自己皮肤的变化，在每一个记录条中用户可上传图片。对于图片的存储与管理，使用的是微信小程序本身自带的云开发数据库。用户通过点击上传图片可将图片添加至数据库并显示出来，后端数据库部分记录内容如下。

![](https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/1.jpg)

（2）调用wx.request实现天气状况实时更新。通过微信小程序官方提供的API可以将天气网站的信息实时爬取下来。将紫外线指数和提示显示在页面上，提醒用户注意防晒。

#### **2.使用说明**（包括操作说明或测试数据等）

小程序分为两大功能块，第一大功能块是肤质测试，这也是进入小程序时的首页，在这个界面上，我们向使用者简单介绍了我们的测试方法，并简洁明了地罗列出了四大测试。

​                                                                   <img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/2.png" style="zoom: 33%;" />

 每完成一项测试，在结束的时候会跳出下一个测试的连接入口，以此来方便使用者一步到位的测试。

​                                                               <img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/3-1.png" style="zoom: 33%;" />

​                                                               <img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/3.png" style="zoom: 33%;" />

 

​                                                               <img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/3-3.png" style="zoom: 33%;" />

​                                                               <img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/3-4.png" style="zoom: 33%;" />

 

 完成四大测试之后可以查看自己的肤质报告。（若是未完成测试就点击查看报告，会显示错误，并提醒完成测试）

<img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/4.png" style="zoom: 33%;" />

完成测试所得到的报告：

<img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/5.png" style="zoom: 33%;" />

<img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/6.png" style="zoom: 33%;" />

<img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/7.png" style="zoom: 33%;" />

点击分享，可以生成二维码，把图片保存至相册，就能与他人分享。

<img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/8.png" style="zoom: 33%;" />

<img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/9.png" style="zoom: 33%;" />



第二大功能块可以实现记录与分享肤质的功能，点击进入我的记录，会显示当天的紫外线强度以及护肤小建议。

<img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/10.png" style="zoom: 33%;" />



点击加号，即可添加护肤记录，记录包括文字与图片两部分，图片可以从图库选择也可以实时拍摄。 

​                                                                 <img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/11.png" style="zoom: 33%;" />

填写记录完成，显示，可以对肤质或者产品打星。

<img src="https://media-yuanxin.oss-cn-hangzhou.aliyuncs.com/skinPic/pic/12.png" style="zoom: 33%;" />