# 相关技术分享与交流
## 技术流
|Nodejs|Anrular|
|-|-|
| [图片上传技术](https://github.com/Big-xiong/nodejs_demo/issues/3) | [脏检测机制](https://github.com/Big-xiong/angular_demo/issues/2)|
| [服务器代理](https://github.com/Big-xiong/nodejs_demo/issues/1) |[关于$http无法传参](https://github.com/Big-xiong/angular_demo/issues/1)|
|[爬虫](https://github.com/Big-xiong/nodejs_demo/issues/2)||
## 问题流
- [关于angular如何根据搜索得到的内容来获取分页数](https://github.com/Big-xiong/angular_demo/issues/3)
- 弹性盒+rem布局
  sublime Text里面设置基础的rem
  首选项->插件设置->cssrem(sublime插件)->setting user 打开文件设置基础的rem,一般为 64 或者 75
  ```javascript
  <script type="text/javascript">
      // 把尺寸放大N倍（N是window.devicePixelRatio）
      var wd = document.documentElement.clientWidth*window.devicePixelRatio/10;
      //物理像素*设备像素比=真实像素
      document.getElementsByTagName("html")[0].style.fontSize = wd + "px";
      // 把屏幕的倍率缩小到N分之一（N是window.devicePixelRatio）
      var scale = 1/window.devicePixelRatio;
      var mstr = 'initial-scale='+ scale +', maximum-scale='+ scale +', minimum-scale='+ scale +', user-scalable=no';
      document.getElementById("vp").content = mstr;
  </script>
  ```
