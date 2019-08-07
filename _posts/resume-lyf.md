# 联系方式

- 手机：13133150962

- Email：yifeng20161123@163.com

- 微信号：lyf1776538456

- QQ号: 895391664

# 个人信息

- 刘一峰/男/1995

- 学校：长治学院(山西省)/电子信息科学与技术专业

- 工作年限：大学四年级(还没有实际的工作经验)

- Github：[@lxhlyf](https://github.com/lxhlyf)  CSDN: [@lyfxh1314](https://blog.csdn.net/lyfxh1314)

- 期望职位：android开发

# 技能清单

- 良好的java基础，熟悉掌握面向对象思想，了解和能够应用反射，注解
- 良好kotlin基础，能够实现kotlin和java的混合开发
- 熟悉掌握Android应用UI设计、使用常用布局、自定义控件开发
- 了解MVC,MVP,MVVM架构
- 了解掌握Android数据存储(文件、SQLite、SharedPreferences等)
- 了解View的绘制流程，View的事件分发,Activity的启动流程，系统注册服务的流程
- 阅读过Handler的源码，AsyncTask的源码，属性动画的源码
- 使用并阅读过源码的第三方库：ButterKnife(AOP), OkHttp3(interceptor),Rxjava(观察者模式)，Retrofit，EventBus,Glide,XUtils
- 了解常用的设置模式，并作 出过尝试运用设计模式分装代码
- 能够阅读和编写H5，JavaScript,css代码，能够实现Android和JS的互相调用
- 了解JNI的开发流程，能够使用Androidfile.mk或者CMake进行NDK的开发(学习还不算太深入)
- 了解flutter开发，能够依靠官方文档进行开发，阅读过携程App的flutter源代码，也能够自己实现一些效果。
- 了解数组，链，队列，栈，树等数据结构
- 了解排序，分治，贪心等算法
- 了解Python基础，能够阅读python的爬虫代码。

# 学习经历

## 第一个App(2017年)

- **项目：[belongmusic](https://github.com/lxhlyf/belongmusic)** 

- **简介：** belongmusic是一个音乐播放器，音乐内容来自网络

- **技术点**

    * 项目使用MVC模式作架构

    * 通过HttpUrlConnection获取json,然后通过Android包org.json下的json解析器进行解析成bean

    * 使用ListView进行展示数据，图片一个线程去从网络获取，获取后使用SoftReference持有，经过bitmap的压缩之后在data/data和sdcard下都存储一份实现了三级缓存的效果，后期计划可以使用LurCache替换SoftReference
    
    * 音乐播放采用service + MediaPlayer + Broadcast，其中Broadcast设想也可以采用EventBus和AIDL进行替换
    
    * 音乐下载部分采用IntentService进行下载，并用一个ProgressBar展示下载的进度

    * 使用Git作为整个APP项目的代码版本控制

> 项目是我学习Android的第一个项目，所以没有采用第三方库，而是尽量使用android原声的控件和API进行实现的。



## 第二个App(2018年寒假)

- **项目：[Test](https://github.com/lxhlyf/Test)**

- **简介：**  Test是一个将单独APP和头条APP的部分糅合在一个的多媒体客户端

- **技术点**
    
    * 项目使用MVP模式作为架构
    
    * 通过照相机拍照或者使用ContentProvider从相册中选择选择一张照片最为头像

    * 使用RxJava + Retrofit +OkHttp作网络请求框架

    * 混合开发，原生与JS互相交互调用

    * 使用JieCaoVideoPlayer进行视屏播放，使用MediaPlayer+Service(通过在onStartCommand判断intent的action来盘控制音乐的播放状态)实现了音频的播放
    
    * 使用litepel进行SQLite数据库的操作

    * 使用Git作为整个APP项目的代码版本控制



>正是通过此项目，我的编码能力得到了很大的提升，同时也接触了很多新技术，让我了解了很多第三方库，架构以及设计模式的知识



## 第三个APP(2019暑假)

- **项目：[FrameConstruct](https://github.com/lxhlyf/FrameConstruct)

- **简介：**  FrameConstruct主要用来熟悉Kotlin的用法，以及组件化开发的设计思想，

- **技术点**
    
    * 使用MVP模式作为架构
    
    * 使用Kotlin作为开发语言

    * 使用RxJava + Retrofit + OkHttp作网络请求框架

    * 实现了首页的Toolbar在Banner显示时为透明，Banner滑出界面Toolbar变为灰色，而其他的三个页面总是灰色的，这是仿写成首页的效果。

    * 每一页作为一个Module，使用ARoute进行模块间的调用。实现了解耦和插件化开发的思想

> 这个项目的主要任务侧重在熟悉Kotlin语言和组件化开发的思想，实现虽然简单，但是让我对于Android开发有了更深入的理解。


## 第四个APP(2019年3月)

- **项目：[ClarityNotes](https://github.com/lxhlyf/ClarityNotes)

- **简介：**  ClarityNotes客户端,是我的一个练手的习作，其中采用了litepel以及一些基于Material Design设计风格的库，采用架构是MVC实现上比较简单。

> 分为五大模块: 英语词根笔记 / 英语短语笔记 / 美句笔记 / 读书笔记 / 日记

# 自我评价

- 有强烈的学习欲望，愿意独立钻研并解决问题

- 为人随和，具备团队合作精神及责任感

- 做事细心有条理，喜欢发现问题，研究问题


# 平时如何自学


## 通过书籍

### Java
- 《第一行代码Java》 作者:郭霖
- 《Java开发实战经典》 作者:李兴华

### Android
- 《疯狂Android的讲义》 作者:李刚
- 《Android源码设计模式解析与实战》
- 《Android开发艺术探索》 作者:任玉刚
- 《Android进阶之光》 作者:刘望舒
- 《Android编程权威指南》

### Kotlin
-《疯狂Kotlin讲义》 作者:李刚
-《Kotlin从零到精通Android开发》  作者：欧阳燊

### Flutter
- 《Flutter技术入门与实战》

### Gradle
- 《Gradle》 作者:马斯可

### Groovy
- 《Groovy in action》 作者吴翊

### HTML5,JS,CSS
- 《Java Web开发实战》

### 算法和数据结构
- 《数据结构与算法分析 c语言描述 第二版》
- 《算法图解》
- 《数据结构与算法分析 C++版 第三版》 作者:美国 Mark Allen Weiss
- 《大话数据结构》 作者:程杰

### 网络开发
《图解HTTP协议》

###数据库
- 《Mysql必知必会》

### Python
- 《Python爬虫开发与项目实战》


## 通过网络公开课


## 通过阅读官方源码
[Android](https://developer.android.google.cn/guide/)
[flutter](https://flutter.dev/docs)


## 其他的学习网站
[菜鸟教程](https://www.runoob.com/w3cnote/android-tutorial-intro.html)
[泡在网上的日子](http://www.jcodecraeer.com/)
