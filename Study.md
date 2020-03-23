## 学习心得总结

### 基础
轻量级的  lumen/yaf 都行
稍微重量级些的： yii/ ThinkPHP/
PHP官网：http://php.net/manual/zh/index.php
WordPress：https://codex.wordpress.org/zh-cn:%E5%AE%89%E8%A3%85_WordPress#.E5.BC.80.E5.A7.8B.E5.AE.89.E8.A3.85WordPress.E4.B9.8B.E5.89.8D.E4.BD.A0.E9.9C.80.E8.A6.81.E7.9F.A5.E9.81.93.E7.9A.84.E4.B8.9C.E8.A5.BF
[PHP工程师学习计划](https://www.cnblogs.com/Lance--blog/p/4472139.html)
[PHP详细学习计划](http://blog.csdn.net/mepsoft/article/details/48496705)

[vscode：visual studio code 调试php](https://blog.csdn.net/x356982611/article/details/52664334)

### 调用路径
1. 通过zeal软件查看wp开发文档代码走读
2. index.php -> wp-blog-header.php -> wp() -> wp-includes/class-wp.php -> template-loader.php
-> get_index_template() -> theme下的index.php

### 切换路径本地服务器后碰到问题整理
1. [WordPress更改“固定链接”后 页面404原因及解决方法](https://www.jiloc.com/41536.html)

2. 服务器根目录切换到abc.com

### 使用相关插件说明
1. All-in-one WP Migration（网站迁移）
2. Membership by supsystic（会员系统）
3. WeChat Social（第三方登录）

### wordpress使用
[WordPress引入css/js两种方法](https://blog.csdn.net/csnewdn/article/details/54021234)

### 登录注册页面实现
[建立网站如何用wordpress快速设置注册登录页面](https://jingyan.baidu.com/article/656db918cf0c30e380249c6a.html)  
[不用插件，定制化WordPress登陆注册页面](http://www.solagirl.net/custom-wordpress-login-without-plugins.html)  
[WordPress添加QQ、微博第三方登录功能](http://www.euweb.cn/archives/2406)  
[WordPress用户登录后重定向到指定页面](https://www.cnblogs.com/kenshinobiy/p/7476500.html)

[wordpress特定用户设置显示或隐藏头部工具栏](https://jingyan.baidu.com/article/90895e0fb2205e64ed6b0b47.html)
[WordPress用户中心插件Membership演示](https://v.qq.com/x/page/d0381mm1dgi.html)
[WordPress 使用 Ultimate Member 实现前台用户中心功能](https://www.wpdaxue.com/ultimate-member.html)

### 图像处理相关
[6 款 Javascript 的图像处理库](https://segmentfault.com/a/1190000008670319)
[8 个用于增强图片效果的WordPress插件](http://www.iteye.com/news/25401)
[WordPress 限制不同用户角色可上传的文件类型及大小](https://www.wpdaxue.com/wordpress-existing_mimes-upload_size_limit.html)
[20款最好用的wordpress图片相册插件](http://blog.csdn.net/liuxuekai/article/details/52122324)
ImageMagick
[WP_Image_Editor_Imagick 漏洞临时解决方法](https://www.wpdaxue.com/wp_image_editor_imagick.html)
Closify Press

### 图片上传
[PHP+js实现图片上传，编辑](https://www.cnblogs.com/rendd/p/7009186.html)