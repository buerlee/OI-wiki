## 导语

我们知道，通过提交程序、由评测机输入数据并判断输出数据的题目叫传统题。而 OI 发展迅速，普通的传统题已经不能满足我们的所有需求，所以在近几年，有两种非传统题慢慢进入大家的视野。

## 提交答案题

提交答案题，顾名思义，就是直接提交答案的题目。该种题目一般会给你输入文件，然后要求提交包含有 XXX1.out、XXX2.out、XXX3.out......XXXn.out 的压缩包、文件夹或纯文件。评测机做的事情就很简单了：比较答案文件与标准答案即可。

做这种题目一般有两种方法：

1.  手玩。这种方法简单粗暴，但是遇到较大的数据就没辙了。
2.  编写一个程序来获得答案文件。

## 交互题

交互题会有另一个题目自带程序（或者你的程序中评测器添加的非选手代码部分）和你的代码一起交互、一起运行，并不像以前一样只有你自己的程序在运行。你可以看看 [UOJ #206. 【APIO2016】Gap](http://uoj.ac/problem/206) 了解一下交互题。

交互题一般会给你一个头文件，让你 `include` 它。这种题要求你实现一个函数，在评测时，评测工具就会调用这个函数。有时还会给你一些系统自带的辅助函数帮助你做题。
