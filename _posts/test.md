**1、描述计算机的组成及其功能**

冯 诺依曼体系，主要由5部分组成：运算器、控制器、存储器、输入设备、输出设备。

CPU：运算器、控制器、寄存器、缓存：

存储器：内存，RAM (Random Access Memory)：

输入设备（Input）：下指令，提供数据等：

输出设备（Output）：输出数据加工的结果：



**2、描述内核功能以及作用**

kernel:	

​	底层监控程序：通用程序：操作系统，为了区分概念中的操作系统而称为kernel：

​		1、驱动底层硬件：

​		2、把底层各硬件资源抽象成为简单的资源：提供系统调用(System call)：

​		3、管理各程序的运行，把有限资源分配给运行中的程序、让彼此之间运行相安无事：

主要功能：

​		驱动程序

​		进程管理

​		安全

​		网络功能

​		内存管理

​		文件系统

​		... ...



**3、按系列罗列常见Linux的发行版，并描述不同发行版之间的联系与区别**

Debian, Slackware, Redhat

​	Debian：三大主流发行版之一，以社区方式运作，没有商业公司支持：

​		Ubuntu：是Debian的二次衍生版：

​		Knoppix：Debian的二次衍生版：

​	Slackware：三大主流发行版之一，是SLS的分支：

​		S.u.S.E：Slackware的二次衍生版：

​			OpenSUSE：S.u.S.E的二次衍生版：Slackware的三次衍生版：

​	RedHat：三大主流发行版之一：

​		Fedora：RedHat的个人版分支：

​		CentOS：基于Red Hat Enterprise的二次发行版：它是来自于Red Hat Enterprise Linux依照开放源代码规定发布的源代码所编译而成：

​	Gentoo：基于Portage包管理系统，而拥有几乎无限制的适应性特性，被官方称作元发行版，支持多达10种以上的计算机系统结构平台：

​	Arch Linux：是一款基于 x86-64 架构的 Linux发行版：系统主要由自由和开源软件组成，支持社区参与：





| 发行版                                                       | 创造者                                                       | 生产者                                                       | 首次公开发行日 (年-月-日)    | 基础发行版                                                   | 最近更新日期 | 目的                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------- | ------------------------------------------------------------ | ------------ | -------------------- |
| [Debian](https://zh.wikipedia.org/wiki/Debian)               | [Ian Murdock](https://zh.wikipedia.org/wiki/Ian_Murdock)     | Debian Project                                               | 1993-08-16                   | none                                                         | 2014-02-08   | 通用                 |
| [Ubuntu](https://zh.wikipedia.org/wiki/Ubuntu)               | [Canonical Ltd](https://zh.wikipedia.org/wiki/Canonical_Ltd). | [Canonical Ltd](https://zh.wikipedia.org/wiki/Canonical_Ltd). | 2004-10-20                   | [Debian](https://zh.wikipedia.org/wiki/Debian)               | 2014-07-25   | 桌面, 服务器         |
| [Knoppix](https://zh.wikipedia.org/wiki/Knoppix)             | [Klaus Knopper](https://zh.wikipedia.org/w/index.php?title=Klaus_Knopper&action=edit&redlink=1) | *dev team*                                                   | ***?*** pre-2003-01-19 (3.1) | [Debian](https://zh.wikipedia.org/wiki/Debian)               | 2008-03-27   | Live CD              |
| [Slackware](https://zh.wikipedia.org/wiki/Slackware)         | [Patrick Volkerding](https://zh.wikipedia.org/w/index.php?title=Patrick_Volkerding&action=edit&redlink=1) | *dev team*                                                   | 1993-07-16                   | [SLS](https://zh.wikipedia.org/w/index.php?title=Softlanding_Linux_System&action=edit&redlink=1) | 2008-05-02   | 桌面, 工作站, 服务器 |
| [SUSE Linux](https://zh.wikipedia.org/wiki/SUSE_Linux_distributions) | SUSE Linux / Novell                                          | [Novell](https://zh.wikipedia.org/wiki/Novell), Inc. *dev team* | 1994-03-?                    | Slackware, Jurix[[4\]](https://zh.wikipedia.org/wiki/Linux%E5%8F%91%E8%A1%8C%E7%89%88%E6%AF%94%E8%BE%83#cite_note-4) | 2008-05-21   | 商业桌面, 服务器     |
| [openSUSE](https://zh.wikipedia.org/wiki/OpenSUSE)           | SUSE Linux / Novell                                          | [Novell](https://zh.wikipedia.org/wiki/Novell), Inc. & [openSUSE Project](https://zh.wikipedia.org/w/index.php?title=OpenSUSE_Project&action=edit&redlink=1) | 1994-03-?                    | [SUSE Linux](https://zh.wikipedia.org/wiki/SUSE_Linux_distributions) | 2017-07-26   | 桌面, 服务器         |
| [Red Hat Linux](https://zh.wikipedia.org/wiki/Red_Hat_Linux) | [Red Hat](https://zh.wikipedia.org/wiki/Red_Hat)             | [Red Hat](https://zh.wikipedia.org/wiki/Red_Hat)             | 1995-05-13 (1.0)             | none                                                         | 2003-03-31   | 服务器, 工作站       |
| [Fedora](https://zh.wikipedia.org/wiki/Fedora)               | [Fedora Project](https://zh.wikipedia.org/wiki/Fedora_Project) | [Fedora Project](https://zh.wikipedia.org/wiki/Fedora_Project) | 2003-11-05                   | [Red Hat Linux](https://zh.wikipedia.org/wiki/Red_Hat_Linux) | 2016-06-21   | 通用                 |
| [CentOS](https://zh.wikipedia.org/wiki/CentOS)               | CentOS Project                                               | CentOS Project                                               | 2004-05-14                   | [RHEL](https://zh.wikipedia.org/wiki/Red_Hat_Enterprise_Linux) | 2016-09-30   | 服务器               |
| [Gentoo Linux](https://zh.wikipedia.org/wiki/Gentoo_Linux)   | [Daniel Robbins](https://zh.wikipedia.org/w/index.php?title=Daniel_Robbins&action=edit&redlink=1) | [Gentoo Foundation](https://zh.wikipedia.org/w/index.php?title=Gentoo_Foundation&action=edit&redlink=1), Inc. | 2002-3-31                    | none                                                         | 2018-01-16   | 通用                 |
| [Arch Linux](https://zh.wikipedia.org/wiki/Arch_Linux)       | [Judd Vinet](https://zh.wikipedia.org/wiki/Judd_Vinet)       | *dev team*                                                   | 2002-03-11                   | none                                                         | 2013-07-1    | 通用                 |





![img](https://img-blog.csdn.net/20141017223815812)



**4、描述常见的开源协议(GPL，LGPL, BSD，Apache等)以及开源协议的区别**

开源协定：

​	GPL, LGPL, BSD, Apache

​		GPL：General Public License

​				copyleft

​			只要在一个软件中使用(”使用”指类库引用，修改后的代码或者衍生代码)GPL 协议的产品，则该软件产品必须也采用GPL协议，既必须也是开源和免费，这就是所谓的”传染性”：

​		GPLv2：

​			GPLv2的主要变化是“自由或死亡”（Liberty or Death）条款:

​			为了在一定程度上保障和尊重其它一些人的自由和权益，无论任何人要发布源于GPL的软件的时候，同时也须遵守强制的条款分享源代码，否则他将根本无权发布该软件:

​		GPLv3：

​			1、解决软件专利问题：

​			2、自由软件许可证与其它商用许可的兼容性问题：

​			3、源代码分割与组成的定义：

​			4、解决数字版权管理的问题，意即反软件修改的硬件限制：

​		LGPL：Lesser GPL

​			允许商业软件通过类库引用(link)方式使用LGPL类库而不需要开源商业软件的代码:

​			但是如果修改LGPL协议的代码或者衍生，则所有修改的代码，涉及修改部分的额外代码和衍生的代码都必须采用LGPL协议:

​		BSD：

​			可以自由的使用，修改源代码，也可以将修改后的代码作为开源或者专有软件再发布：

​			如果发布使用了BSD协议的代码，或则以BSD协议代码为基础做二次开发自己的产品时，需要满足三个条件：

​				1、如果二次分布的产品中包含源代码，则在源代码中必须带有原来的代码中的BSD协定：

​				2、如果二次发布产品是二进制格式的库或程序，则需要在发布的文档或版权声明中说明包含原来的代码中的BSD协定：

​				3、不可以用开源代码的作者或组织，以及原来的产品的名字做市场推广：	

​		Apache：

​			允许代码修改，再发布（作为开源或商业软件）：

​    			1、需要给代码的用户一份Apache Licence：

​    			2、如果你修改了代码，需要再被修改的文件中说明：

​    			3、在延伸的代码中（修改和有源代码衍生的代码中）需要带有原来代码中的协议，商标，专利声明和其他原来作者规定需要包含的说明：

​    			4、如果再发布的产品中包含一个Notice文件，则在Notice文件中需要带有Apache Licence，你可以在Notice中增加自己的许可，但不可以表现为对Apache Licence构成更改：











**5、描述Linux的哲学思想，并按照自己的理解对其进行解释性描述**

Linux的哲学思想：

​		1、一切皆为文件：

​			把几乎所有资源统统抽象为文件形式：包括硬件设备，甚至通信接口等：

​				主要操作有：open(), read(), write(), close(), delete(), create()

​		2、由众多功能单一的程序组成：一个程序只做一件事，并且做好：

​			组合小程序完成复杂任务：

​		3、尽量避免跟用户交互：

​			目标：易于以编程的方式实现自动化任务：

​		4、使用文本文件保存配置信息：

文件是：存储空间存储的一段流式数据，对数据可以做到按名存取：

​	而且Linux有自己独特的文件系统：层级机构，有索引：

这样便于管理和使用。



**6、描述linux目录结构以及目录结构命名规定**

目录：路径映射：

​	以 “/” 为原初起点的倒置树状结构：

​		如：

```
			/dev/pts/2:
				最左侧/: 表示根目录
				其它的/: 表示路径分隔符
```

​	文件的路径表示：

​		绝对路径：从根开始表示出的路径

​		相对路径：从当前位置开始表示出的路径

​	用户有家目录：home：

​		用户的起始目录：普通用户管理文件的位置：

​	工作目录：

​		working directory，用户当前所在的目录(current directory): 相对路径：

命名规定：

​	1、文件名名称严格区分字符大小写：

​	2、目录也是文件，在同一路径下，两个文件不能同名：

​	3、文件可以使用除/以外任意字符：（最好不要使用特殊字符或空格）

​	4、文件名长度不能超过255字符：