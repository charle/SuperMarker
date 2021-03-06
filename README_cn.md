### 为何有 Super Marker
---

从 12 年开始写前端，深深地感受到切图不仅仅是件技术活，它更是一件体力活。假如一张设计稿上有 50 个 div，这不算多吧，那么为了知道这些元素的 width, height, margin, pading, font-size 等属性，我们至少得测量 200+ 次，如果你是一个不太迅速的切图仔，这些操作需要花费你一二十分钟，这还没算上元素 border-color, background, color 等值的获取时间。那么一个网站的测量工作就要花费一个多小时的时间。

有一个比 Photoshop 轻量一点的工具，mark man，不过它依然需要我们放大图片，选择元素的左上角和右下角，从而得知改元素的尺寸信息。

没事儿，现在有了 Super Marker，这是一款比 mark man 更加强大的图片信息标记工具，它的强大在于智能化和自动化，可以为我们自动提取我们需要的信息，而我们需要做的只是在图片上“胡乱”地画两下。


### 演示地址
---

中文版: [Super Marker](http://barretlee.github.io/SuperMarker/index_cn.html)

English Version: [Super Marker](http://barretlee.github.io/SuperMarker/)


### 功能
---

|功能           |快捷键   |功能介绍                        |
|--------------|-----|-------------------------------------------------|
|**移动**     |Move|如果你的图片过大，可以轻松移动图片|
|**放大**     |Ctrl+(+/-)|由于浏览器自身有放大功能，这个功能需要等到我空闲比较多的时候补上|
|**尺子**     |Ruler|一个相当好用的尺寸量取工具，这个要感谢 mark man，因为我是模仿它的|
|**自动线条标记**|横向<br />Horizen<br />纵向<br />Vertical<br />网状<br />Net|提供了横向、纵向以及网状的线条，你只需要在图片上选择区域，程序会帮你分析哪些地方需要画线。
|**取色器**   |Color|你会看到这东西很好用！|
|**选框信息** |Info|在你的图片上会有很多的线条，这些线条将图片划分成很多区块，通过这个选框工具，可以选择一个或者多个区块（如果是多个区块则合并成一个）的信息|
|**线条选择工具**|Select|你可以通过画框来选择线条，也可以在这个工具激活模式下，点击线条以选中它。当然，也可以使用它来取消选择哦！|
|**删除**     |Delete|当你选中一些线条之后，就可以用到这个工具了，点击它就能删除选中的线条|
|**清空**     |Clear|清空画面中所有的线条和框|


### Licence
--- 

Licensed under MIT.

Copyright (C) 2014 https://github.com/barretlee/SuperMarker

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



