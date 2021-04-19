Jmeter压力测试2

1.  **整体目标：**

安装虚拟机

在Jmeter压力测试1搭建的工作环境基础上对Ecshop/BugFree的功能进行性能测试。安装ECShop的同学，对创建新订单的功能进行压力测试；安装BugFree的同学，对添加新Bug描述的功能进行压力测试。并在测试后得出Jmeter测试报告，并根据sysstat得出Linux服务器的CIMN（CPU、IO、Memory以及Network）的性能。

1.  **实验内容：**

    1.  使用Jmeter录制ECShop/BugFree创建新订单/Bug描述的行为，并尝试更改部分行为（例如不同商品的订单、Bug标题等）；

    2.  使用Jmeter进行5\*10、50\*20的压力测试并得出Jmeter Aggregate
        Report，同时运用sysstat对服务器信息进行统计。

2.  **实验要求**

    1.  基本要求：实践压力测试工具Jmeter

    2.  相关日期：

        1.  提交报告日期：2021.4.20按照格式提交到智慧树

    3.  实验报告应包括：

        1.  访问的B/S系统截图

        2.  Jmeter的Testplan展开截图

        3.  Beanshell代码（功能自定义）

        4.  运行Jmeter测试之后的Aggregate Report Result

        5.  运行Jmeter测试之后的服务器性能截图

        6.  根据sysstat结果对压力测试对服务器性能产生的影响作简要的分析

        7.  如发生错误，则简单描述错误并分析错误产生的原因

3.  **参考**

    1.  Jmeter：*http://jmeter.apache.org*

    2.  LAMP及ECShop/BugFree安装请自行搜索
