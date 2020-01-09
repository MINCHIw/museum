# 博物馆

### **一、PRD 价值主张设计**

#### **PRD1.加值宣言 3%**

- 危险行为识别API：实现对博物馆参观者中的多动症患者的行为监控，识别其是否会有如摇晃、搬动、破坏文物等危险行为，从而保护文物不受毁坏。

- 手势识别API：辅助失语者使用用语音才能进行互动的科技展品，通过识别失语者摆动的手势，可以开启、命令、关闭展品，从而使失语者也能参与到与展品互动过程中。

- 语音识别 API：辅助身障者（双手不便），通过语音识别对科技展品发出指令，进行对展品的操控。

- 语音合成 API：辅助失语者，通过语音合成可以扫描展物的文字信息生成语音播放给失语者听，以听的方式来获取信息。

#### **PRD2.核心价值 3%**

- 通过app的提示警告，可以提前知道参观者的危险行为从而有效进行对文物的保护工作。通过手势的识别，失语者也能通过摆动手势来参与到展品的互动之中。身障者可以通过语音识别科技展品发出指令操控。

#### **PRD3.核心价值与用户痛点 3%**
- 展馆工作人员希望能有措施来预防多动症患者对文物的毁坏行为。
- 身障者想要不借助他人的帮助来与展品进行互动活动。

#### **PRD4.人工智能概率性与用户痛点 3%**
- 手势识别仅支持24种常见手势的识别，但是不限手势的类型。
- 危险行为识别目前仅支持单人、双人场景，且仅针对5秒内内的监控片段视频。
- 使用语音识别API，中文普通话识别的准确率达98%，仍有小概率识别出错误文本的情况存在。

#### **PRD5.需求列表与人工智能API加值 3%**
|功能|用户案例|重要程度|
|:-|:-:|-:|
|监测多动症者对文物的预毁坏行为|展馆工作人员想能够提前知道多动症患者对文物的毁坏行为，从而更好地进行对文物的保护行为。|很重要|
|帮助失语者与展物互动|失语者想要与科技展品互动，但展品只能语音操控，而自己却无法说话。|很重要|
|帮助双手不便者与展物互动|双手不便者想要与展品互动，但是展品仅能用手操作、触碰屏幕，而自己却无法做到。|很重要|

### **二、原型**
#### **（一）原型源文件**的下载地址:[https://gitee.com/NFUNM093/museum_prototype](https://gitee.com/NFUNM093/museum_prototype)


#### **（二）**[Axure原型](http://nfunm093.gitee.io/museum_prototype)


#### **（三）产品原型图**
#### **1. 首页**
- **首页界面**

![首页](https://upload-images.jianshu.io/upload_images/9776460-132dd6a08e4efb02.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
---
#### **2. 导览**
- **导览界面**

![导览](https://upload-images.jianshu.io/upload_images/9776460-bd8667cef91a4f62.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---
#### **3. 展物识别**
- **识别界面**

![展物识别](https://upload-images.jianshu.io/upload_images/9776460-819a19505f177648.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- **识别结果界面**

![识别结果](https://upload-images.jianshu.io/upload_images/9776460-2039111f60c6c08f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---
#### **4. 展物互动**
- **扫描二维码界面**

![扫描二维码](https://upload-images.jianshu.io/upload_images/9776460-11bbdff03cdfb6bb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- **手势互动界面**

![手势互动](https://upload-images.jianshu.io/upload_images/9776460-2adc9b953aeffa02.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---

**用到的API有：**
- 语音合成
- 手势识别
- 语音识别
- 危险行为识别
