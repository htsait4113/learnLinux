## 1.1 认识shell

shell的中文意义为外壳，如同Linux的外壳保护着Linux的内核，并且作为与外界通信的桥梁。shell是命令解释器同时也是一种高级编程语言。作为命令解释器，它解释和执行用户的命令；作为高级编程语言，它能够编写出可运行的脚本，提供函数和控制结构等语言编程能力。

### 1.1.1 shell的概念

shell外壳主要是为了区别于Kernel内核，它是一个用户的操作接口，负责接收用户的命令输入，解释命令并调用相应的应用程序执行指定的操作。其实，shell的概念并不是在UNIX/Linux中才有的，这一概念在Windows系列中也有，只不过其表现为DOS的COMMAND.COM命令解释器或后来的cmd.exe。

shell按是否使用图形界面作为接口的方式分类，可分为两种：图形界面的shell和字符界面的shell。图形界面的shell即GUI shell，提供了一个图形的操作界面，其中包括我们在Linux下所使用的GNOME、KDE和Xfce桌面环境，以及在Windows下使用的Windows Explorer。字符界面的shell即CLI shell，提供一个字符型的操作界面，其中使用比较广泛的CLI shell包括DOS下使用的COMMAND.COM、Windows XP下使用的cmd.exe及UNIX/Linux下使用的bash。

