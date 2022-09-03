<h1><center>Ajax</center></h1>

## 1、关于Ajax

**AJAX**即“**Asynchronous JavaScript and XML**”（非同步的[JavaScript](https://zh.m.wikipedia.org/wiki/JavaScript)与[XML](https://zh.m.wikipedia.org/wiki/XML)技术），指的是一套综合了多项技术的[浏览器](https://zh.m.wikipedia.org/wiki/瀏覽器)端[网页](https://zh.m.wikipedia.org/wiki/網頁)开发技术。Ajax的概念由[杰西·詹姆士·贾瑞特](https://zh.m.wikipedia.org/wiki/傑西·詹姆士·賈瑞特)所提出。

| [编程范型](https://zh.m.wikipedia.org/wiki/编程范型) | [Webapp](https://zh.m.wikipedia.org/wiki/网络应用程序), [HTML](https://zh.m.wikipedia.org/wiki/HTML), [JavaScript](https://zh.m.wikipedia.org/wiki/JavaScript), [DHTML](https://zh.m.wikipedia.org/wiki/DHTML), [DOM](https://zh.m.wikipedia.org/wiki/文档对象模型), [XMLHttpRequest](https://zh.m.wikipedia.org/wiki/XMLHttpRequest), [JSON](https://zh.m.wikipedia.org/wiki/JSON), [XML](https://zh.m.wikipedia.org/wiki/XML), [XSLT](https://zh.m.wikipedia.org/wiki/XSLT), [XHTML](https://zh.m.wikipedia.org/wiki/XHTML), [CSS](https://zh.m.wikipedia.org/wiki/Cascading_Style_Sheets) |
| :--------------------------------------------------- | ------------------------------------------------------------ |
| 设计者                                               | [杰西·詹姆士·贾瑞特](https://zh.m.wikipedia.org/wiki/傑西·詹姆士·賈瑞特) |
| 发行时间                                             | 2005年2月18日，17年前                                        |

传统的Web应用允许用户端填写表单（form），当送出表单时就向[网页伺服器](https://zh.m.wikipedia.org/wiki/網頁伺服器)发送一个请求。伺服器接收并处理传来的表单，然后送回一个新的网页，但这个做法浪费了许多带宽，因为在前后两个页面中的大部分[HTML](https://zh.m.wikipedia.org/wiki/HTML)码往往是相同的。由于每次应用的沟通都需要向伺服器发送请求，应用的回应时间依赖于伺服器的回应时间。这导致了用户界面的回应比本机应用慢得多。

与此不同，AJAX应用可以仅向伺服器发送并取回必须的数据，并在客户端采用JavaScript处理来自伺服器的回应。因为在伺服器和浏览器之间交换的数据大量减少，伺服器回应更快了。同时，很多的处理工作可以在发出请求的[客户端](https://zh.m.wikipedia.org/wiki/客户端)机器上完成，因此Web伺服器的负荷也减少了。

类似于[DHTML](https://zh.m.wikipedia.org/wiki/DHTML)或[LAMP](https://zh.m.wikipedia.org/wiki/LAMP)，AJAX不是指一种单一的技术，而是有机地利用了一系列相关的技术。虽然其名称包含XML，但实际上数据格式可以由[JSON](https://zh.m.wikipedia.org/wiki/JSON)代替以进一步减少数据量。而客户端与服务器也并不需要异步。一些基于AJAX的“派生／合成”式（derivative/composite）的技术也正在出现，如[AFLAX](https://zh.m.wikipedia.org/wiki/AFLAX)。

## 2、详解

##### 		**Ajax是对于XMLHttpRequest的使用**

![image.png](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/fc811623b8b240d0b5ffa466f3566d3b~tplv-k3u1fbpfcp-zoom-in-crop-mark:3024:0:0:0.awebp)

![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/1a740f6ebceb4503a57de3a7096d4ff4~tplv-k3u1fbpfcp-zoom-in-crop-mark:3024:0:0:0.awebp)

我们可以通过这些方法与对象属性来进行代码实现。