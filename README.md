# zhihu
A spider, by which you can get all of your zhihu collections
知乎收藏夹内容爬虫，以供方便的查看所有内容及搜索

## 0.1 版本

用 node.js 写了一个小脚本，通过手动从浏览器复制自己知乎的 cookies 并粘贴到代码中，以使其爬取自己所有收藏，并写入到一个 markdown 文件中供自己查阅，详见 0.1 文件夹。

## 0.2 版本

改进为不需要 cookie 即可爬取，通过知乎个人主页的网址即可浏览所有自己的收藏夹内容，
并且已经写成一个简单的小网站 https://nought.cc/zh 以后台服务器爬取、前端展示的方式更方便的查看或搜索收藏内容，详见 0.2 版本文件夹。

解决知乎禁止转载不能复制

chrome浏览器，按F12进入Chrome DevTools

点击这个工具栏右上角 x 左边三个小点（customize and control devtools）的那个按钮

点击settings-debugger-disable javascript，回车刷新，就可以复制禁止转载的内容了
