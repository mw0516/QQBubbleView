# QQBubbleView

## Outline

利用三阶贝塞尔曲线模仿QQ空间直播时右下角的礼物冒泡特效

## ScreenShot

![](http://diycode.b0.upaiyun.com/photo/2016/55b80c4c270e41e429c468973f215cc7.gif)

## Feature

* 支持自定义itemview的样式、大小、位置

* 支持动画时间设置

* 支持直接添加view到xml文件

* 支持自定义view的活动区域

## Usage

```
allprojects {
    repositories {
        jcenter()
        maven {
            url 'https://dl.bintray.com/yasic/maven/'
        }
    }
}

compile 'yasic.library.BubbleView:bubbleview:0.0.3'
```



## Point

* 继承自Relativelayout

* 使用三阶贝塞尔曲线模拟运动路径，三阶贝塞尔曲线公式如下


![](http://img.my.csdn.net/uploads/201008/28/0_1282984326C3m1.gif)

* 参考博客http://www.html-js.com/article/1628

* 强烈推荐一个模拟贝塞尔曲线的网站，可以在线模拟出想要的曲线http://myst729.github.io/bezier-curve/

* 利用AnimatorSet组合动画效果

## API
正在设计中，近期会上传到 Maven 仓库服务器，并展示API详细内容
