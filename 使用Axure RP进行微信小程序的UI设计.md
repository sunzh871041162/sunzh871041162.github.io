# 使用Axure RP进行微信小程序的UI设计

团队：the-earn-money-system  
作者：sunzh871041162


UI(User Interface)是用户与系统之间进行交互的媒介，合适的UI设计能使得用户更快地上手、更方便地使用软件，当然一个好的UI带来的不仅仅是良好的用户体验，还影响了软件对用户的吸引程度、用户的留存率等。  

--------
Axure RP是一款快速原型原型设计工具，拥有可视化工作环境，不用进行编程就能够在线框图上定义各种效果和交互。  

--------
本文介绍使用Axure软件来进行微信小程序的UI设计的一些操作(本文参照的软件版本为Axure RP 8)  

## Axure基本介绍：  

这是Axure的主界面：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/zhuyemian.png)

左上角的页面框内包含了各个页面，可以看做是小程序不同页面，页面的包含关系表示了小程序页面的包含关系：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/yemian.png)

Axure默认的元件库内包含了多类可使用的元件：  
 ![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/yuanjian.png)
 
基本元件内，有多种图形和图片、占位符、按钮等元件供我们选择：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/4.png)

比如我们可以用一个矩形来代表小程序的主要页面，在这个矩形上放置一个图片元件，我们就可以引入自己的图片：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/5.png)

同时，当我们选中每个元件时，可以对它进行命名、添加交互、改变样式等操作，每个元件的命名最好是有意义的命名，这样当  
一个页面元件较多时，在添加交互等操作时可以方便找到想要的元件：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/6.png)

良好的元件命名习惯，也可以方便我们在右下角的概要框内，迅速地选中想要找到的元件进行编辑：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/7.png)


## 交互的添加：  

选中一个元件后，在它的属性一栏选中鼠标单击，点击添加用例，就可以为这个元件添加一个鼠标单击它时进行的交互操作，例  
如，单击该幅名为“a”的图片，设置点击它时，在当前窗口打开Page1页面：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/8.png)

通过添加用例，可以设置各种不同的交互效果，例如显示、隐藏、改变面板状态、弹出窗口、关闭窗口等等交互效果。  

## 动态面板的使用：  

动态面板是基本元件中的一个元件，我们可以为它添加多个状态，并可以使它在各个界面间进行切换或者为各个界面设置不同的  
交互操作。动态面板是比较重要的一个元件，例如，我们可以用它制作一个很多小程序都有的循环滚动的推荐栏：

为动态面板添加多个状态，最顶端的为初始状态：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/9.png)

对不同状态页可以进行不同的设计：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/10.png)

对于动态面板，为它设置载入时切换到下一个状态以及在切换时循环切换到下一个状态两个交互操作，即可让动态面板在它的各  
个状态页之间切换，同时还可为切换设置不同的动画效果，例如向左滑动：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/11.png)

## 文板框的使用：  

在使用小程序时，我们时常会遇到需要我们进行输入的情况，对于输入的UI设计，可以使用表单元件内的文本框，对于文本框，  
也可以对它进行交互设置，同时还可以对文本框的输入类型、字符数量等进行限制：  
![](https://github.com/sunzh871041162/sunzh871041162.github.io/blob/master/imgs/12.png)

Axure的默认元件库内还提供多行文本框、列表框、复选框、单选按钮等元件供用户选择，合理使用这些元件可以帮助用户设计  
出合适的UI。  

----
Axure的默认元件库已经提供了相当丰富的元件供用户选择使用，同时用户也可以在Axure的官方网站元件库下载免费或者付费  
的元件库使用。  
