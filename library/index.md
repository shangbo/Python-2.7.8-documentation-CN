#目录#

在《
[Python语言参考手册](http:docs.python.org/2.7/reference/index.html)
》中已经准确的描述了Python语言的语法，而这本标准库参考手册则主要介绍Python发行版中的标准库，以及一般随着发行版发布的可选组件。

正如下面的目录中所表明的那样，Python标准库涉及的内容非常广泛，它提供了大量的工具。标准库中包括一些用C编写的内置模块，提供一些必要的系统功能，如文件读写；还包括一些用Python编写的模块，提供针对日常编程问题的一些标准化解决方案；也包括一些针对Python程序可移植性设计的模块，它们将特定系统平台抽象为与平台无关(platform-neutral)的API接口。

windows平台下的Python安装程序一般包含完整的标准库以及一些额外组件。类Unix操作系统则一般提供__Python as a collection of packages__，所以如有需要，使用系统的__packagingtools__获取一些或所有的可选组件。

除了标准库以外，在
[PyPI](https://pypi.python.org/pypi)
中还可以获取成千上万的组件，包括从单独的程序或模块到完整的应用开发框架。

1. 简介
2. 内置函数
3. 非必须的内置函数
4. 内置常量 
	- 由site模块添加的常量
5. 内置类型
	- __真值测试__
	- 逻辑运算符 —— and, or, not
	- 比较运算符
	- 数值类型 —— int, float, long, complex
	- __迭代类型__
	- 序列类型 —— str, unicode, list, tuple, bytearray, buffer, xrange
	- 集合类型 —— set, frozenset
	- 映射类型 —— dict
	- 文件对象
	- __memoryview__类型
	- __语境管理类型__
	- 其他内置类型
	- 特殊属性
6. 内置异常
	- __异常层次__
7. __文本操作__
	- string —— 基本字符串操作
	- re —— 正则表达式操作
	- struct —— 作为二进制数据的字符串
	- difflib —— __Helpers for computing deltas__
	- StringIO —— __Read and write strings as files__
	- cStringIO —— StringIO的快速版本
	- textwrap	—— __Text wrapping and filling__
	- codecs —— 编码注册和基本类型
	- unicodedata —— Unicode数据库
	- stringprep —— 网络数据预处理
	- fpformat —— 浮点数格式化打印
8. 数据类型
9. 数值与数学模块
10. 文件和目录操作
11. 数据持久性
12. 数据压缩与归档
13. 文件类型格式化
14. 密码服务
15. 通用操作系统服务
16. 可选操作系统服务
17. 进程间通信与合作
18. 网络数据处理
19. 结构化标记处理工具
20. 网络协议与支持
21. 多媒体
22. 国际化
23. 程序框架
24. Tk图形化用户界面
25. 开发者工具
26. 调试与性能分析
27. Runtime操作
28. 自定义Python解释器
29. 受限执行
30. 模块导入
31. 语言处理
32. 编译打包
33. 杂项
34. Windows系统特定操作
35. Unix系统特定操作
36. Mac OS X 特定操作
37. MacPython OSA模块
38. SGI IRIX 特定服务
39. SunOS 特定服务
40. Undocumented 模块

