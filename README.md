# 《Go入门指南》

在接触 Go 语言之后，对这门编程语言非常着迷，期间也陆陆续续开始一些帮助国内编程爱好者了解和发展 Go 语言的工作，比如开始录制视频教程[《Go编程基础》](https://github.com/Unknwon/go-fundamental-programming)。但由于目前国内并没有比较好的 Go 语言书籍，而国外的优秀书籍因为英文的缘故在一定程度上也为不少 Go 语言爱好者带来了一些学习上的困扰，不仅为了加快扩散 Go 爱好者的国内群体，本人在完成阅读这本名叫 《The Way to Go》 之后，决定每天抽出一点时间来进行翻译的工作，并且以开源的形式免费分享给有需要的 Go 语言爱好者。

尽管该书对目前 Go 语言版本来说有小部分内容相对过时，但是为当下不可多得的好书，相关内容已获得作者同意根据当前 Go 语言版本进行修改而不作出特别声明。

该翻译版本已获得原作者（Ivo Balbaert）本人授权，并表示支持开源事业的发展！

## 翻译进度

14.6 [协程和恢复（recover）](eBook/14.6.md)

## 支持本书

如果你喜欢本书 《Go入门指南》，你可以参与到本书的翻译或纠正工作中来，具体请联系【无闻 E-mail：u\#gogs.io】，一同完善本书并帮助壮大 Go 语言在国内的学习群体，给大家提供更好的学习资源。

## 交流社区

参见 [Go 语言学习资料与社区索引](https://github.com/Unknwon/go-study-index)。

### 新人守则

* 2012 年 3 月 28 日以前的博文中的内容基本过时，不要再看
* 符合等式 _**百度+思考+失败+翻墙+谷歌+尝试=解决**_ 的问题最好不要发问

## 致谢

* 本书原作者：Ivo Balbaert
* 参与翻译人员：
  * [@zhanming](https://github.com/zhanming)
  * themorecolor
  * [@everyx](https://github.com/everyx)
  * [@chidouhu](https://github.com/chidouhu)
  * [@spawnris](https://github.com/spawnris)
  * [@domainname](https://github.com/domainname)
  * [@leisore](https://github.com/leisore)
  * [@dake](https://github.com/dake)
  * [@glight2000](https://github.com/glight2000)
  * [@songleo](https://github.com/songleo)

## 授权许可

除特别声明外，本书中的内容使用 [CC BY-SA 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/)（创作共用 署名-相同方式共享3.0 许可协议）授权，代码遵循 [BSD 3-Clause License](https://github.com/astaxie/build-web-application-with-golang/blob/master/LICENSE.md)（3 项条款的 BSD 许可协议）。

## 开始阅读

[前言](./eBook/preface.md)

想读书的人，不会找不到 [目录](eBook/directory.md) :\)

# 目录

* [前言](preface.md)

## 第一部分：学习 Go 语言

* 第1章：Go 语言的起源，发展与普及
  * 1.1 [起源与发展](01.1.md)
  * 1.2 [语言的主要特性与发展的环境和影响因素](01.2.md)
* 第2章：安装与运行环境
  * 2.1 [平台与架构](02.1.md)
  * 2.2 [Go 环境变量](02.2.md)
  * 2.3 [在 Linux 上安装 Go](02.3.md)
  * 2.4 [在 Mac OS X 上安装 Go](02.4.md)
  * 2.5 [在 Windows 上安装 Go](02.5.md)
  * 2.6 [安装目录清单](02.6.md)
  * 2.7 [Go 运行时（runtime）](02.7.md)
  * 2.8 [Go 解释器](02.8.md)
* 第3章：[编辑器、集成开发环境与其它工具](03.0.md)
  * 3.1 [Go 开发环境的基本要求](03.1.md)
  * 3.2 [编辑器和集成开发环境](03.2.md)
  * 3.3 [调试器](03.3.md)
  * 3.4 [构建并运行 Go 程序](03.4.md)
  * 3.5 [格式化代码](03.5.md)
  * 3.6 [生成代码文档](03.6.md)
  * 3.7 [其它工具](03.7.md)
  * 3.8 [Go 性能说明](03.8.md)
  * 3.9 [与其它语言进行交互](03.9.md)

## 第二部分：语言的核心结构与技术

* 第4章：基本结构和基本数据类型
  * 4.1 [文件名、关键字与标识符](04.1.md)
  * 4.2 [Go 程序的基本结构和要素](04.2.md)
  * 4.3 [常量](04.3.md)
  * 4.4 [变量](04.4.md)
  * 4.5 [基本类型和运算符](04.5.md)
  * 4.6 [字符串](04.6.md)
  * 4.7 [strings 和 strconv 包](04.7.md)
  * 4.8 [时间和日期](04.8.md)
  * 4.9 [指针](04.9.md)
* 第5章：[控制结构](05.0.md)
  * 5.1 [if-else 结构](05.1.md)
  * 5.2 [测试多返回值函数的错误](05.2.md)
  * 5.3 [switch 结构](05.3.md)
  * 5.4 [for 结构](05.4.md)
  * 5.5 [Break 与 continue](05.5.md)
  * 5.6 [标签与 goto](05.6.md)
* 第6章：[函数（function）](06.0.md)
  * 6.1 [介绍](06.1.md)
  * 6.2 [函数参数与返回值](06.2.md)
  * 6.3 [传递变长参数](06.3.md)
  * 6.4 [defer 和追踪](06.4.md)
  * 6.5 [内置函数](06.5.md)
  * 6.6 [递归函数](06.6.md)
  * 6.7 [将函数作为参数](06.7.md)
  * 6.8 [闭包](06.8.md)
  * 6.9 [应用闭包：将函数作为返回值](06.9.md)
  * 6.10 [使用闭包调试](06.10.md)
  * 6.11 [计算函数执行时间](06.11.md)
  * 6.12 [通过内存缓存来提升性能](06.12.md)
* 第7章：[数组与切片](07.0.md)
  * 7.1 [声明和初始化](07.1.md)
  * 7.2 [切片](07.2.md)
  * 7.3 [For-range 结构](07.3.md)
  * 7.4 [切片重组（reslice）](07.4.md)
  * 7.5 [切片的复制与追加](07.5.md)
  * 7.6 [字符串、数组和切片的应用](07.6.md)
* 第8章：[Map](08.0.md)
  * 8.1 [声明、初始化和 make](08.1.md)
  * 8.2 [测试键值对是否存在及删除元素](08.2.md)
  * 8.3 [for-range 的配套用法](08.3.md)
  * 8.4 [map 类型的切片](08.4.md)
  * 8.5 [map 的排序](08.5.md)
  * 8.6 [将 map 的键值对调](08.6.md)
* 第9章：[包（package）](09.0.md)
  * 9.1 [标准库概述](09.1.md)
  * 9.2 [regexp 包](09.2.md)
  * 9.3 [锁和 sync 包](09.3.md)
  * 9.4 [精密计算和 big 包](09.4.md)
  * 9.5 [自定义包和可见性](09.5.md)
  * 9.6 [为自定义包使用 godoc](09.6.md)
  * 9.7 [使用 go install 安装自定义包](09.7.md)
  * 9.8 [自定义包的目录结构、go install 和 go test](09.8.md)
  * 9.9 [通过 Git 打包和安装](09.9.md)
  * 9.10 [Go 的外部包和项目](09.10.md)
  * 9.11 [在 Go 程序中使用外部库](09.11.md)
* 第10章：[结构（struct）与方法（method）](10.0.md)
  * 10.1 [结构体定义](10.1.md)
  * 10.2 [使用工厂方法创建结构体实例](10.2.md)
  * 10.3 [使用自定义包中的结构体](10.3.md)
  * 10.4 [带标签的结构体](10.4.md)
  * 10.5 [匿名字段和内嵌结构体](10.5.md)
  * 10.6 [方法](10.6.md)
  * 10.7 [类型的 String\(\) 方法和格式化描述符](10.7.md)
  * 10.8 [垃圾回收和 SetFinalizer](10.8.md)
* 第11章：[接口（interface）与反射（reflection）](11.0.md)
  * 11.1 [接口是什么](11.1.md)
  * 11.2 [接口嵌套接口](11.2.md)
  * 11.3 [类型断言：如何检测和转换接口变量的类型](11.3.md)
  * 11.4 [类型判断：type-switch](11.4.md)
  * 11.5 [测试一个值是否实现了某个接口](11.5.md)
  * 11.6 [使用方法集与接口](11.6.md)
  * 11.7 [第一个例子：使用 Sorter 接口排序](11.7.md)
  * 11.8 [第二个例子：读和写](11.8.md)
  * 11.9 [空接口](11.9.md)
  * 11.10 [反射包](11.10.md)
  * 11.11 [Printf 和反射](11.11.md)
  * 11.12 [接口与动态类型](11.12.md)
  * 11.13 [总结：Go 中的面向对象](11.13.md)
  * 11.14 [结构体、集合和高阶函数](11.14.md)

## 第三部分：Go 高级编程

* 第12章：[读写数据](12.0.md)
  * 12.1 [读取用户的输入](12.1.md)
  * 12.2 [文件读写](12.2.md)
  * 12.3 [文件拷贝](12.3.md)
  * 12.4 [从命令行读取参数](12.4.md)
  * 12.5 [用 buffer 读取文件](12.5.md)
  * 12.6 [用切片读写文件](12.6.md)
  * 12.7 [用 defer 关闭文件](12.7.md)
  * 12.8 [使用接口的实际例子：fmt.Fprintf](12.8.md)
  * 12.9 [格式化 JSON 数据](12.9.md)
  * 12.10 [XML 数据格式](12.10.md)
  * 12.11 [用 Gob 传输数据](12.11.md)
  * 12.12 [Go 中的密码学](12.12.md)
* 第13章：[错误处理与测试](13.0.md)
  * 13.1 [错误处理](13.1.md)
  * 13.2 [运行时异常和 panic](13.2.md)
  * 13.3 [从 panic 中恢复（Recover）](13.3.md)
  * 13.4 [自定义包中的错误处理和 panicking](13.4.md)
  * 13.5 [一种用闭包处理错误的模式](13.5.md)
  * 13.6 [启动外部命令和程序](13.6.md)
  * 13.7 [Go 中的单元测试和基准测试](13.7.md)
  * 13.8 [测试的具体例子](13.8.md)
  * 13.9 [用（测试数据）表驱动测试](13.9.md)
  * 13.10 [性能调试：分析并优化 Go 程序](13.10.md)
* 第14章：[协程（goroutine）与通道（channel）](14.0.md)
  * 14.1 [并发、并行和协程](14.1.md)
  * 14.2 [使用通道进行协程间通信](14.2.md)
  * 14.3 [协程同步：关闭通道-对阻塞的通道进行测试](14.3.md)
  * 14.4 [使用 select 切换协程](14.4.md)
  * 14.5 [通道，超时和计时器（Ticker）](14.5.md)
  * 14.6 [协程和恢复（recover）](14.6.md)
* 第15章：[网络、模版与网页应用](15.0.md)
  * 15.1 [tcp服务器](15.1.md)
  * 15.2 [一个简单的web服务器](15.2.md)
  * 15.3 [访问并读取页面数据](15.3.md)
  * 15.4 [写一个简单的网页应用](15.4.md)

## 第四部分：实际应用

* 第16章：[常见的陷阱与错误](16.0.md)
  * 16.1 [误用短声明导致变量覆盖](16.1.md)
  * 16.2 [误用字符串](16.2.md)
  * 16.3 [发生错误时使用defer关闭一个文件](16.3.md)
  * 16.4 [何时使用new\(\)和make\(\)](16.4.md)
  * 16.5 [不需要将一个指向切片的指针传递给函数](16.5.md)
  * 16.6 [使用指针指向接口类型](16.6.md)
  * 16.7 [使用值类型时误用指针](16.7.md)
  * 16.8 [误用协程和通道](16.8.md)
  * 16.9 [闭包和协程的使用](16.9.md)
  * 16.10 [糟糕的错误处理](16.10.md)
* 第17章：[模式](17.0.md)
  * 17.1 [关于逗号ok模式](17.1.md)
* 第18章：[出于性能考虑的实用代码片段](18.0.md)
  * 18.1 [字符串](18.1.md)
  * 18.2 [数组和切片](18.2.md)
  * 18.3 [映射](18.3.md)
  * 18.4 [结构体](18.4.md)
  * 18.5 [接口](18.5.md)
  * 18.6 [函数](18.6.md)
  * 18.7 [文件](18.7.md)
  * 18.8 [协程（goroutine）与通道（channel）](18.8.md)
  * 18.9 [网络和网页应用](18.9.md)
  * 18.10 [其他](18.10.md)
  * 18.11 [出于性能考虑的最佳实践和建议](18.11.md)
* 第19章：构建一个完整的应用程序
* 第20章：Go 语言在 Google App Engine 的使用
* 第21章：实际部署案例

## 附录

* A 代码引用
* B 有趣的 Go 引用
* C 代码示例列表
* D 书中的包引用
* E 书中的工具引用
* F 常见问题解答
* G 习题答案
* H 参考文献

## 索引



