# 和缓医疗对接资料
通用版

## 一、对接流程
#### 1.服务端对接
* 注册用户：提交用户基本信息，获取用户uuid。
* 添加套餐：为用户添加产品套餐。
* 获取小程序码：获取用户唯一的小程序码。（小程序对接专用）

#### 2.小程序对接
* H5页面显示二维码，提示用户长按识别二维码，即可调用小程序，图文咨询医助，视频咨询医生。可参考下方示意图：
![sample](https://imgs.hh-medic.com/icon/wmp/sample.jpg?x-oss-process=image/resize,m_fixed,w_300)
***

## 二、API地址
https://api.hh-medic.com

***

## 三、API帐号
和缓分配，请向您的和缓接口人索取。

***

## 四、服务端API
#### 通用规则
https://api.hh-medic.com/project/44/interface/api/1349
#### 注册用户
https://api.hh-medic.com/project/47/interface/api/1367
#### 添加套餐
https://api.hh-medic.com/project/47/interface/api/1568
#### 获取小程序码（小程序对接专用）
https://api.hh-medic.com/project/47/interface/api/1624

***

## 五、SDK
如果您的后台开发语言是Java或.Net，可参考如下Demo程序，使用我们提供的SDK，快速实现上述API功能。
#### Java版
https://github.com/HHMedic/HHDoctorSDK_demo_server_java

#### .Net版
https://github.com/HHMedic/HHDoctorSDK_demo_server_dotnet

***

## 六、开发帐号
和缓分配，请向您的和缓接口人索取。

***

## 七、其他说明
如需数据抄送功能，可参考API：https://api.hh-medic.com/project/47/interface/api/1592
