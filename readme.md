# 塔斯汀小程序模仿小程序
- 本项目归塔斯汀所有，只做学习所用，请尊重原厂版权
- fiddler 抓包工具抓取图片
- 界面模仿采用markman做标记
  1. 我们没有设计稿，如何一比一还原小程序？
  2. 拍屏得到小程序截图
  3. 使用在线大小[转换工具](https://www.gaitubao.com/)，将图片改为750,以后写wxss时，可以量像素直接写进去，因为小程序以750rpx作为设计稿标准大小帮我们自动适配，非常好用
  4. 使用[marman](http://getmarkman.com/)先标注，再写样式，以后上了班就不用了， 有设计师给你标好，现在， 还是自己来LOL 吧

- 项目配置在根目录app.json
  - 隐藏并定制navigationBar
  "navigationBarStyle":"custom"

- 启动定位功能


- 使用了BEM 国际css命名规范
  tst_banners 广告位
  tst_banners__img  Element

- css 技巧
  1. 能不用定位就不用定位
    脱离文档流
  2. 移动端多用弹性布局

- git 提交