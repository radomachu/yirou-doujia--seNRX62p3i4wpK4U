[合集 - 总结(25)](https://github.com)

[1.CSP2024 - J/S 年度总结大会报告2024-11-05](https://github.com/high-sky/p/18528914)[2.就 NOIP2024 中出现的问题进行深入探讨2024-12-03](https://github.com/high-sky/p/18583849)[3.浅谈分块中的一些技巧01-17](https://github.com/high-sky/articles/18677762)[4.1.浅谈一些数论函数及其应用03-02](https://github.com/high-sky/p/18746988)[5.小trick04-22](https://github.com/high-sky/p/18841531)[6.小记08-02](https://github.com/high-sky/p/19018835)[7.CF407E k-d-sequence 题目分析（0929模拟赛最后一题）09-29](https://github.com/high-sky/p/19119040)[8.CF107C Arrangement & 51Nod 1579 席位安排 题目分析09-29](https://github.com/high-sky/p/19119659)[9.2025多校冲刺CSP模拟赛2 总结10-04](https://github.com/high-sky/p/19125668)[10.斜率优化dp复习笔记10-05](https://github.com/high-sky/p/19126359)[11.概率期望dp 复习笔记10-05](https://github.com/high-sky/p/19126707)[12.2025多校冲刺CSP模拟赛4 总结10-07](https://github.com/high-sky/p/19128530):[ssrdog](https://waling.org)[13.博弈论dp复习笔记10-07](https://github.com/high-sky/p/19128841)[14.OIFHA251009 比赛总结10-09](https://github.com/high-sky/p/19131141)[15.CF1832D2 Red-Blue Operations (Hard Version) && 模拟赛题目分析10-09](https://github.com/high-sky/p/19131779)[16.决斗（模拟赛题目T3）分析10-10](https://github.com/high-sky/p/19132309)[17.括号序列构造字典序最小化问题10-10](https://github.com/high-sky/p/19132406)[18.OIFHA251011 比赛总结10-11](https://github.com/high-sky/p/19135042)[19.子序列自动机学习笔记10-12](https://github.com/high-sky/p/19136370)[20.wqs二分学习笔记10-13](https://github.com/high-sky/p/19137884)[21.P4870 [BalticOI 2009] 甲虫 (Day1) 分析10-13](https://github.com/high-sky/p/19138010)[22.反悔贪心复习笔记10-14](https://github.com/high-sky/p/19140177)[23.2025多校冲刺CSP模拟赛5 总结10-15](https://github.com/high-sky/p/19143552)[24.P1912 [NOI2009] 诗人小G 分析10-15](https://github.com/high-sky/p/19144408)

25.OIFHA251017总结10-17

收起

比赛：OIFHA251017
日期：25.10.17，场地：OIFHA，排名：12/12

**估分**：100+0+75+0=175

**终分**：0+0+0+0=0

**应该得分**：100+30+75+0=205

### 失分

T1 背包挂分 100pts，T3 挂分 75pts

### 时间轴复盘

8:00 比赛开始，先去调了昨天晚上没有调完的 `[JNOI2017]遗失的答案`，也是过啦。

9:00 准时开打。

9:20 来了个 dp，而后想到了分组求解再背包。

背包先来了个平方级别的做法，大样例过了。

然后蒙了一个结论发现大样例全过。

所以就分段写。

扔了。

10:40 了。

T2 看完题感觉太吃操作了，想到后面题目还没有打暴力就跳了。

T3 一眼 O(215T) 暴力，打完之后样例一直没有全过，调了很久，到最后没有调出来。

赛后调了一下，如下原因：

* 多算了 0 对答案的贡献，10pts→0。
* 开成了大根堆以及返回 −1 的时候加上了原始答案，75pts→0。

### 可复用经验

* 无

### 吾赛时四省吾身

* 题目看对了乎？
* 暴力打了乎？
* 所及而至乎？
* 造数据验了乎？

签名：xxx 日期：25.10.17

## 后记

悲伤，哭了一个中午，现在感觉眼睛有点肿。~
