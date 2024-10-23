## 项目目录

* images 文件夹：存放**固定使用**的图片素材，例如：logo、样式修饰图等
* uploads 文件夹：存放**非固定使用**的图片素材，例如：商品图、宣传图等需要**上传**的图片
* css 文件夹：存放 CSS 文件（link 标签引入）
    * base.css：基础公共样式，例如：清除默认样式、设置网页基本样式
    * index.css：首页 CSS 样式
* index.html：首页 HTML 文件

## header 区域 - 布局

通栏：**宽度**与**浏览器窗口**相同的**盒子**

标签结构：通栏 > 版心 > logo + 导航 + 搜索 + 用户

### logo 制作技巧

logo 功能：

* **单击跳转到首页**
* **搜索引擎优化**：**提升**网站搜索**排名**

实现方法：
* 标签结构：h1 > a > 网站名称（搜索关键字）
* css 样式：
    ```css
    .logo a {
        display: block;
        width: 195px;
        height: 41px;
        background-image: url(../images/logo.png);
        /* 隐藏文字 */
        font-size: 0;
    }
    ```

### 导航制作技巧（nav）

导航功能：

* 单击跳转页面

实现方法：

* 标签结构：ul > **li * 3** > **a**
* 优势：避免堆砌 a 标签，网站搜索排名**降级**

### 搜索区域（search）

实现方法：

* 标签结构：.search > input + a / button

### 用户区域（user）

实现方法：

* 标签结构：.user > a > img + span

## banner 区域 - 布局

结构：通栏 banner > 版心 > .left + .right

### 左侧侧导航（left）

实现方法：

* 标签结构：.left > ul > li * 9 > a
* 布局思路：设置 a 标签的**背景图**为**白色**右箭头

### 右侧课程表（right）

实现方法：

* 标签结构：.right > h3 + .content

## 精品推荐（recommend）

实现方法：

* 标签结构：.recommend > h3 + ul + a.modify
* 布局思路：Flex 布局

## 推荐课程（course）

实现方法：

* 标签结构：.hd + .bd
* 布局思路：盒子模型