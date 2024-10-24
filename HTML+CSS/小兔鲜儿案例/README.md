## 项目目录

* images 文件夹：存放固定使用的图片素材
* uploads 文件夹：存放非固定使用的图片素材
* iconfont 文件夹：**字体图标**素材
* css 文件夹：存放 CSS 文件（link 标签引入）
    * base.css：基础公共样式
    * common.css：各个网页相同模块的**重复**样式，例如：头部、底部
    * index.css：首页 CSS 样式
* index.html：首页 HTML 文件

## SEO 三大标签

SEO：**搜索引擎优化**，提升网站搜索排名

提升 SEO 的常见方法；

1. 竞价排名
2. 将网页制作成 html 后缀
3. 标签语义化（在合适的地方使用合适的标签）
4. ...

网页头部 SEO 标签：

* title：网页标题标签
* description：网页描述
* keywords：网页关键词

## Favicon 图标

Favicon 图标：网页图标，出现在**浏览器标题栏**，增加网站辨识度。

图标：favicon.ico，一般存放到网页的根目录

## 版心

wrapper 版心宽度：1240px

## 快捷导航区域（shortcut）

结构：通栏 > 版心 > 导航 ul

布局：flex-end

## 头部区域（header）

结构：.header > **logo** + **导航**（nav）+ **搜索**（search）+ **购物车**（cart）

## 底部区域（footer）

## banner区域

结构：通栏 > 版心 > 轮播图（ul.pic） + 侧导航（subnav > ul） + 圆点指示器（ol）

## 新鲜好物区域（goods）

结构：标题（title）+ 内容（bd）（多区域样式共用）