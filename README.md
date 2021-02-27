# Python-GUI--tkinter

***Python GUI***编写的一个答题系统

**随机答题** 包括选择题和判断题两个部分，可以输入题号进行跳转；

**模拟考试** 每次随机生成100道题，其中题目来自两个题库，各50道；此外包含***答题计时***，***暂停/开始计时***，***错题统计***，***计算得分***等。

## 程序打包成exe
**注意**：最好打包成32位程序（需使用***python32***位版本打包），这样可以兼容32位和64位操作系统。

打包过程可以去掉黑色窗口，参考博客: https://blog.csdn.net/qq_41251963/article/details/111660021

      1.将要封装的python文件，后缀名改为pyw
      
      2.执行 pyinstaller  文件名.pyw -F      (pyinstaller 安装命令：pip install pyinstaller)
