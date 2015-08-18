<img src="/app/src/main/res/mipmap-hdpi/ic_meizhi_150602.png" width="128" height="128" /> <img src="/app/src/main/res/mipmap-hdpi/ic_meizhi_150619.png" width="128" height="128" />

端午节回家的时候，无聊之中，做了一个专门欣赏妹纸的小应用，数据来自[代码家](https://github.com/daimajia)的干货网站：http://gank.io 我只抓取了妹纸图做了个新的开源小应用：

直接下载：https://fir.im/mengmeizhi (请尽量 Google Play 下载，搜索「妹纸」即可得，如果喜欢，去给个五星好评，非常感谢！)

源代码：https://github.com/drakeet/Meizhi

本来就是自用或内部使用的，也只开发了一个晚上加一个早上时间，并没有很高级很完善，只适配了小米2s 的屏幕尺寸，一些效果也只有 Android 5.0 以上的系统才会有，就酱啦~

通过这个项目，你可能可以学习到的内容有：

* 多渠道打包
* 使用 ORM 快速操作数据库
* 访问网络，简单解析 HTML
* RecyclerView 瀑布流的使用
* RecyclerView 底部加载更多的简单实现
* Material Design 的下拉刷新
* 使用最新的 Design 兼容库
* 使用 5.0 的 Share 组件或元素动画
* 使用 Toolbar 完全替代 ActionBar

<img src="/screenshots/s1.png" alt="screenshot" title="screenshot" width="270" height="486" />  <img src="/screenshots/s2.png" alt="screenshot" title="screenshot" width="270" height="486" />

<img src="/screenshots/s4.png" alt="screenshot" title="screenshot" width="270" height="486" />  <img src="/screenshots/s5.png" alt="screenshot" title="screenshot" width="270" height="486" />

Contributors

[代码家](https://github.com/daimajia)：增加了首页妹纸卡片点击非图片区域（日期）打开干货页面（http://gank.io）；

[iamwent](https://github.com/iamwent)：Adding feature: saving picture to phone (by long press meizhi image in meizhi detail image page/activity);

###2.0

9号开始重构，开发2.0，至今可谓完成了个完整的干货客户端，不仅仅是看妹纸了，开源又好用，绝对是程序猿必备良心项目...做得匆忙，但代码自认为还是写得很不错的，用了很多注解和 lambda 表达式，用了 RxJava & Retrofit。UI 交互上，细节和动画效果也不少，为了许多小效果有时连发好几个测试版...
