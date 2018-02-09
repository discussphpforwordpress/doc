## 学习心得总结

### 调用路径
1. 通过zeal软件查看wp开发文档代码走读
2. index.php -> wp-blog-header.php -> wp() -> wp-includes/class-wp.php -> template-loader.php
-> get_index_template() -> theme下的index.php

### 切换路径本地服务器后碰到问题整理
1. [WordPress更改“固定链接”后 页面404原因及解决方法](https://www.jiloc.com/41536.html)

2. 服务器根目录切换到abc.com