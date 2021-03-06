# 很大声周刊-vol.25
很大声周刊，在这里记录日常工作、生活所见，每周一发布。

![img](https://user-images.githubusercontent.com/20842136/138538519-e03eafac-792f-4bb2-bcdb-fdc276e82be3.png)

# mask() - Processing
![image](https://user-images.githubusercontent.com/20842136/138540190-59afc9ae-3e2f-4fce-a2d6-8da83c584678.png)

Processing 中的 [mask()](https://processing.org/reference/mask_.html)，除了用文档中指出的 `image` 作为传参，还可以用 `Graphics`，这会极大拓展 `mask()` 的可用性。

# CCapture.js
![image](https://user-images.githubusercontent.com/20842136/138538733-cf40a936-d3ba-4427-978d-7ad1554aeaf5.png)

对于输出视频来说，录屏是最简单的方式，所见即所得，这种方式在遇到运算量很大、帧率降低，不能实时运行的画面时已依然所见即所得，最终的输出和我们看到的一样，是一个充满卡顿的视频。

[CCapture.js](https://github.com/spite/ccapture.js/) 就是用来解决这种问题的库，可以帮助 `canvas` 以固定帧率输出动画，即便不能程序不能实时运行，CCapture.js 依然能够以稳定的帧率输出画面。

# Video Export
![sketch_86_Output_Demo_01](https://user-images.githubusercontent.com/20842136/138539254-90b22e0e-0e56-46c9-9fd3-f8a77b004a06.gif)

这种录制方式在 Processing 也有对应的库 —— [Video Export](https://funprogramming.org/VideoExport-for-Processing/)，我在[《输出可是一件重要的事情哦》](https://mp.weixin.qq.com/s?__biz=MzAxOTM5MzY1Ng==&mid=2648609911&idx=1&sn=2914f0f4e80d9a8094f5ba6551a0a5ec&chksm=83ed8960b49a00763a7c0aa30b4755128a2eaa24429b48d92808606507a2c64a91086cc15147&token=427395943&lang=zh_CN#rd)这篇文章中写过 Processing 常用输出方式，以及 Video Export 的使用方法。

# 为「明和电机-北京展」制作的交互小玩具
![IMG_8877](https://user-images.githubusercontent.com/20842136/138592463-47fa2267-173e-4f9e-9353-3550dbf99847.jpg)

在线体验：[MaywaDenki-BeiJing](https://openprocessing.org/sketch/1312766)

![640](https://user-images.githubusercontent.com/20842136/138592797-84ff9908-a9ca-4253-8c91-87e27e2006d5.jpg)

[明和电机-北京展](https://mp.weixin.qq.com/s/Qutv0OUI3uzN4ZQZmt2VWQ) 将在10月30号开幕。


# matter.js
![image](https://user-images.githubusercontent.com/20842136/138592576-d57fc533-f38d-4ccb-a130-fcba37a6b014.png)

[Matter.js](https://brm.io/matter-js/) 是基于 web 的 2D 物理引擎。

# 在 JavaScropt 中使用数据库和 API
![image](https://user-images.githubusercontent.com/20842136/138539336-5928b5ec-3d5f-4f39-89b0-198a315bf821.png)

又是 [Daniel Shiffman](https://shiffman.net/) 的课程，[在 JavaScropt 中使用数据库和 API](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YxDKpFzf_2D84p0cyk4T7X) 课程中，通过三个案例教你学会使用外部 API，以及使用 Node.js（后端） 在本地搭建自己的服务器/数据库，并实现数据的保存、收发。

如果在看文章的你和我类似，并非专业程序员，在前端的问题上一不小心都会被搞的晕头转向，后端更是无从下手。相比前端而言，后端更生涩，很难直观地看到效果，很多东西学来学去不知道可以干嘛，没法应用到现实场景中，然后就离放弃不远了。

这个系列课程用实际案例从头带你了解前端、后端、API、数据库，如何相互搭配实现更丰富的交互体验。这是我见到过对这方面知识点最友好的讲解课程，即便如此也并不是面向零基础，你需要了解基本的 JavaScript 知识、命令行等等，反正哪里不会就补哪里，因为没有比这个更友好的课程了，最重要的是在开始前，先打消看一遍就能实现的幻想，轻装前行，祝你顺利。

# 日谈公园 × 大内密谈梦幻联动
![IMG_8886](https://user-images.githubusercontent.com/20842136/138624285-d8ac5c48-f7c9-46ed-84a1-ef23be72c36f.jpeg)
大内都已经九百多期了，最早听还是毕业后刚刚参加工作的时候。不记得什么时候变成了两个节目，不知不觉过了好久，日谈都四百期了。

没想到在周日的凌晨，两位主播互为嘉宾，发布了这期联动节目。

# Processing 如何更快地设置颜色？
![sketch_147_HenDaShengTutorial_Logo_02_01_1035](https://user-images.githubusercontent.com/20842136/138592668-e4b89dfe-4f0e-4478-8d82-db51b3ccb772.png)

在 Processing 中，颜色是使用频率极高的设置，通常我们会通过手动复制、粘贴色值的方式完成，在面对需要大量颜色的需求时，手动设置会浪费很多时间，而且调整起来也很麻烦。

以前写过相关文章[《手动输入颜色可还了得？》](https://mp.weixin.qq.com/s?__biz=MzAxOTM5MzY1Ng==&mid=2648609887&idx=1&sn=862d052d1719e59a9ee8c2ce5903a27c&chksm=83ed8948b49a005ef1c47f00fdfced9a11b345a7fce891e719ef530bf1aece61e7b43cdf25b4&token=427395943&lang=zh_CN#rd)，这次以视频的形式，更细致地聊一聊这件事。

[Processing 如何更快地设置颜色？](https://www.bilibili.com/video/BV1ob4y1h7ab/)这期视频带你了解在 Processing 中，如何快速设置大量颜色，制作自己的配色工具，从此告别手动设置颜色。