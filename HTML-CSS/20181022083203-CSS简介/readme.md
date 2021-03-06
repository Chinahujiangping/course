# CSS 简介

在早期的浏览器中所有标签的样式都是浏览器自定义的，或者是通过标签的某些属性定义的

1994 年哈坤·利提出了 CSS 的最初建议。而当时伯特·波斯（Bert Bos）正在设计一个名为 Argo 的浏览器，于是他们决定一起设计 CSS。CSS 指层叠样式表 (Cascading Style Sheets)

同年，W3C 组织（World WideWeb Consortium）成立，CSS 的创作成员全部成为了 W3C 的工作小组并且全力以赴负责研发 CSS 标准，层叠样式表的开发终于走上正轨。有越来越多的成员参与其中，例如微软公司的托马斯·莱尔顿(Thomas Reaxdon)，他的努力最终令 Internet Explorer 浏览器支持 CSS 标准。哈坤、波斯和其他一些人是这个项目的主要技术负责人。1996 年底，CSS 初稿已经完成，同年 12 月，层叠样式表的第一份正式标准（Cascading style Sheets Level 1）完成，成为 w3c 的推荐标准。

## 语言特点

### 丰富的样式定义

CSS 提供了丰富的文档样式外观，以及设置文本和背景属性的能力；允许为任何元素创建边框，以及元素边框与其他元素间的距离，以及元素边框与元素内容间的距离；允许随意改变文本的大小写方式、修饰方式以及其他页面效果。

### 易于使用和修改

CSS 可以将样式定义在 HTML 元素的 style 属性中，也可以将其定义在 HTML 文档的 header 部分，也可以将样式声明在一个专门的 CSS 文件中，以供 HTML 页面引用。总之，CSS 样式表可以将所有的样式声明统一存放，进行统一管理。
另外，可以将相同样式的元素进行归类，使用同一个样式进行定义，也可以将某个样式应用到所有同名的 HTML 标签中，也可以将一个 CSS 样式指定到某个页面元素中。如果要修改样式，我们只需要在样式列表中找到相应的样式声明进行修改。

### 多页面应用

CSS 样式表可以单独存放在一个 CSS 文件中，这样我们就可以在多个页面中使用同一个 CSS 样式表。CSS 样式表理论上不属于任何页面文件，在任何页面文件中都可以将其引用。这样就可以实现多个页面风格的统一。

### 层叠

简单的说，层叠就是对一个元素多次设置同一个样式，这将使用最后一次设置的属性值。例如对一个站点中的多个页面使用了同一套 CSS 样式表，而某些页面中的某些元素想使用其他样式，就可以针对这些样式单独定义一个样式表应用到页面中。这些后来定义的样式将对前面的样式设置进行重写，在浏览器中看到的将是最后面设置的样式效果。

### 页面压缩

在使用 HTML 定义页面效果的网站中，往往需要大量或重复的表格和 font 元素形成各种规格的文字样式，这样做的后果就是会产生大量的 HTML 标签，从而使页面文件的大小增加。而将样式的声明单独放到 CSS 样式表中，可以大大的减小页面的体积，这样在加载页面时使用的时间也会大大的减少。另外，CSS 样式表的复用更大程序的缩减了页面的体积，减少下载的时间。
