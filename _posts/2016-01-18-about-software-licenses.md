---
layout: post
title: 常见的开源协议
author: acusp
description:  simple way to learn open source license, 了解常见的开源协议
keywords: 开源协议,软件许可证,software license
categories: others
tags: license
---

刚接触到开源项目时大家都会看到各种软件开源协议，但由于开源协议的数量很多，我们很少对它们有深入的了解。
下这张图就对常用的软件协议进行一下总结，方便大家选择。图片修改自[PAUL MILLER](http://paulmillr.com/posts/simple-description-of-popular-software-licenses/)

![open licenses](http://7xq7pt.com1.z0.glb.clouddn.com/open-source-licenses-zh.jpg)


### <a href="http://www.gnu.org/licenses/gpl.html" target="_blank">GPL</a>（GNU General Public License）

只要你用了任何该协议的库、甚至是一段代码，那么你的整个程序，不管以何种方式链接，都必须全部使用GPL协议、并遵循该协议开源。商业软件公司一般禁用GPL代码，但可以使用GPL的可执行文件和应用程序。

采用GPL授权的软件有：Linux、MySQL等。


### <a href="http://www.gnu.org/copyleft/lesser.html" target="_blank">LGPL</a>（Lesser GPL）

是GPL针对动态链接库放松要求了的版本，即允许非LGPL的代码动态链接到LGPL的模块。*注意：不可以静态链接，否则你的代码也必须用LGPL协议开源。*

采用LGPL的软件有：JBoss、Hibernate、FCKeditor等。


### <a href="http://www.apache.org/licenses/LICENSE-2.0" target="_blank">APL</a>（apache Licence）

修改版本必须保持其原始版权声明；修改过的文件要标明改动。

采用APL的软件有Hadoop、Apache HttpServer等。


### <a href="https://en.wikipedia.org/wiki/BSD_licenses" target="_blank">BSD</a>（Berkeley Software Distribution）

BSD2：修改版本必须保持其原始版权声明。

BSD3：修改版本必须保持其原始版权声明。未经许可不得使用原作者或公司的名字做宣传。

采用BSD协议的软件有：nginx


### <a href="https://en.wikipedia.org/wiki/MIT_License" target="_blank">MIT</a>（Massachusetts Institute of Technology）

修改版本必须保持其原始版权声明。

采用MIT的软件有：jquery、Node.js





