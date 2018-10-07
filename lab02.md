---
layout: default
title : 用Construct2制作Ghost Shooter游戏
---
# 用Construct2制作Ghost Shooter游戏
# 1 入门
获取并安装Construct 2，然后启动Construct 2，单击File按钮，然后选择New。![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/Yeh1VspITXoTiTWMOEWILYdJXzp5GHL.ZXrjxbM7hYU!/b/dFMBAAAAAAAA&bo=KQJYAgAAAAARB0E!&rf=viewer_4)
此时会出现模板或示例”对话框。我们选择第一个模板来制作此游戏。
# 2 插入对象
## 1 平铺的背景
游戏的背景至关重要，它为游戏提供了游戏发生的场景，好的背景能引人入胜。所以我们先来制作一个扣人心弦的背景吧。
首先我们点击布局中的空格以插入新对象，然后点击“Tiled Background object ”  ![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/T5eNeF66b.ja4UP5eRlTDBqA11odByLKjnY12Y3j6dw!/b/dDQBAAAAAAAA&bo=tAGdAQAAAAARBxk!&rf=viewer_4)
如图所示，接下来我们将背景铺满以覆盖整个布局。选中背景，将其位置设置为(0,0),大小设置为1280,1024。
## 2 添加图层
有了背景，我们接下来需要为游戏添加几个对象，例如经典打怪游戏中不可或缺的几个元素-怪兽，勇士，子弹以及爆炸效果。
为此我们还需要添加一个活动图层并将主图层锁定。
## 3 添加输入对象
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/zfdXffhvQqRsqGEPKAnMorCFgpgBlsAdbMV1ZX0wUqw!/b/dDIBAAAAAAAA&bo=nwCZAAAAAAARBzY!&rf=viewer_4)
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/2X6LstAEQU1BLB76OoyZ3UE79lmKfaht8kNGVftO3ZA!/b/dFQBAAAAAAAA&bo=NQA*AAAAAAARBzo!&rf=viewer_4)
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/9qaAYXr0lvrFmK9cRQPl5xhHRQn9Rzp*NISgoumUh5U!/b/dDQBAAAAAAAA&bo=NAApAAAAAAARFz0!&rf=viewer_4)
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/E1ext8lh5CTAWqI5fxrungDzPTPx6*8*TvgNpzHzeIo!/b/dDEBAAAAAAAA&bo=kwCAAAAAAAARFzM!&rf=viewer_4)
我们将这4个对象依次插入到活动布局中，得到如下图像。
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/a1PqfmL*PtoBBQPTeW.GMh0ye8j2JTVbCHcTvzVoTho!/b/dDcBAAAAAAAA&bo=1AKYAQAAAAARB38!&rf=viewer_4)
# 3 活动及添加游戏功能
接下来我们需要为不同角色定义不同的事件，来让游戏更好的运行。我们需要添加的有很多，例如控制怪兽的数量，改变怪兽的生命值，以至于怪兽不会变的太脆弱或者太难打死。同时我们可以改变玩家手中的枪射出子弹的速度和威力来让我们更好地进行游戏。我们还可以让怪兽随机出现和不断的产生来让游戏更有趣味性和更具挑战性。我们可以根据个人喜好自定义自己所做游戏的难度。完成一系列操作后我们可以看到如下所示。
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/Veg04GOL1etIpCJRtsj1qugAd3Y1MyIoS62RB4BC1uE!/b/dEYBAAAAAAAA&bo=tgObAgAAAAARBxw!&rf=viewer_4)
# 4 运行游戏
制作好游戏后，我们点击左上方Run layout按钮![image](http://a1.qpic.cn/psb?/V11lkfIM05bhcV/grTZv5v.ZfJym00UnQEMMMJfpXu8UvFLrYAwI7U9NqI!/m/dDQBAAAAAAAAnull&bo=3QAmAAAAAAARB8s!&rf=photolist&t=5)
![gif](http://m.qpic.cn/psb?/V11lkfIM05bhcV/8332aZAaHNSkgwA3ITPCt.GEhe.sTqt8iIA21KHochA!/b/dDEBAAAAAAAA&bo=8ALIAQAAAAARFxs!&rf=viewer_4)