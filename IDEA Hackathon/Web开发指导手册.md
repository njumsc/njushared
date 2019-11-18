# **Web开发指导手册**

 ***——For 2019 “PPT Hackathon”***

> 为了帮助大家在比赛中快速上手，以及尽可能取得更多收获，我们编写了这个文档，以备参考。
>
> 方法论多种多样，希望大家有自己的想法，批判看待文中所述。预祝顺利！



[TOC]

---

### 一、概述

##### 1. Web开发是做什么

- 你所看到的一切网站
- 基于 [Chromium](https://www.chromium.org/) 内核的桌面软件，如 [VS Code](https://code.visualstudio.com/)
- 移动应用的部分页面，如手机QQ的QQ空间
- 小程序

##### 2. Web应用的特性

- 一处写完，到处运行
- 无需安装，点开即用

##### 3. Web开发的特性

- 迭代速度快
- 上线效率高
- 需要考虑不同的浏览器环境

### 二、前端

一个页面能被你看到的部分、以及让这一可见部分显示出来的部分，大致是前端的工作。

入手前端，首先需要学习前端三大件：[html](https://www.runoob.com/html/html-tutorial.html)+[css](https://www.runoob.com/css/css-tutorial.html)+[javascript](https://www.runoob.com/js/js-tutorial.html)。

如果把网页看成一个人，那么html决定了你的身体有哪些部分，css决定了你的颜值，javascript决定了你能做什么。

接下来，需要学习流行的前端库和框架。

JS拓展库：[jQuery](https://www.runoob.com/jquery/jquery-tutorial.html)

组件库：[Bootstrap](https://www.runoob.com/bootstrap4/bootstrap4-tutorial.html)

框架：初次学习任选[React](https://www.runoob.com/react/react-tutorial.html)/[Vue](https://www.runoob.com/vue2/vue-tutorial.html)/[AngularJS](https://www.runoob.com/angularjs/angularjs-tutorial.html)其一。

接着，再学习[Redux](https://www.redux.org.cn/)、[TypeScript](https://www.runoob.com/typescript/ts-tutorial.html)等提高开发效率、优化代码逻辑的库和框架。

### 三、后端

后端的工作就是在服务器上处理前端用户的操作，比如登录、发帖等。

入手后端，可以从[LNMP](https://lnmp.org/)开始。

L: Linux，N: Nginx，M: Mysql，P: PHP

无需纠结L和N，先学习[PHP](https://www.runoob.com/php/php-tutorial.html)语言和[Mysql](https://www.runoob.com/mysql/mysql-tutorial.html)数据库。

要注意的是，PHP开发后端是可以同时开发前端的。

这里，能够学习到服务器后端的运作方式、业务逻辑等。

接下来可以学习PHP的框架，如[ThinkPHP](http://www.thinkphp.cn/)。

你可能会追求更好的后端性能，那么就可以学习[Java](https://www.runoob.com/java/java-tutorial.html)，配合[Spring](https://spring.io/)或[SpringBoot](https://spring.io/projects/spring-boot/)响应请求，以及[MyBatis](https://mybatis.org/mybatis-3/)或[JDBC](https://www.runoob.com/w3cnote/jdbc-use-guide.html)访问数据库。

### 四、桌面应用

这一点与前端非常相似，但它比前端多了更多系统层面操作的权限，并且能够独立于浏览器运行（但仍依赖于浏览器内核）。

学习路线与前端一致，而后需要额外学习[Electron](https://electronjs.org/)。

### 五、小程序

详见[微信开放文档](https://developers.weixin.qq.com/miniprogram/dev/framework/)。