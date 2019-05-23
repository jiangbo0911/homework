## 问题描述

图书馆为每个同学分配固定的座位。如图，座位1被分配给同学A，座位2被分配给同学B，座位三未分配，座位四被分配给同学C。依据课表，如果座位上的同学没课，座位状态显示为<font color = "red">“占用”</font>；如果有课，座位状态显示为<font color = "red">“空闲**分钟”</font>。

<img src="https://github.com/hill2hill/homework/blob/master/example.jpeg" width=\textwidth/>


## 问题样例
例如，在2019年5月15日8:00时，在“三层 图书学习空间A 阅览室”

依据课表：

同学A没课，座位1状态为<font color = "red">“占用”</font>

同学B在上课，8:45下课，座位2的状态为<font color = "red">“空闲45分钟”</font>

座位3<font color = "green">“未分配”</font>

## 程序功能

通过GitHub在线协作，编写一个程序，可以查询某个时间、某个阅览室、所有座位的状态。

输入：课程表，作为分配表

输出：图形界面，展示某时刻某阅览室座位占用情况