### Day1
>###### 1.给定一个二维数组，所有位置的值不是0就是1。规定每个位置可以和它一起上下左右位置上的值相连。<br>有一个叫做岛的概念，定义如下：<br>连成一片的1，如果周围都是0，那么这一片1，构成一个岛。求整张图上有多少个小岛。

>###### 2.给定一个数组arr，返回子数组的最大累加和。
例如：
```
[1,-2,3,5,-2,6,-1]
```
所有的子数组中，[3,5,-2,6]可以得到最大的和为12。

### Day2
>###### 从1开始整数，剔除包含9的数字（9,19,29...）之后，返回排在第n个的数

### Day3
>###### 1、已知一个字符串都是由左括号(和右括号)组成，判断该字符串是否是有效的括号组合。

>###### 2、题目进阶： 已知一个字符串都是由左括号(和右括号)组成，返回最长有效括号子串的长度。

### Day4
>######  1、有一排正数，玩家A和玩家B都可以看到。 每位玩家在拿走数字的时候，都只能从最左和最右的数中选择一个。 玩家A先拿，玩家B再拿，两人交替拿走所有的数字， 两人都力争自己拿到的数的总和比对方多。请返回最后获胜者的分数。
例如： 5,2,3,4 玩家A先拿，当前他只能拿走5或者4。 如果玩家A拿走5，那么剩下2，3，4。轮到玩家B，此时玩家B可以选择2或4中的一个，… 如果玩家A拿走4，那么剩下5，2，3。轮到玩家B，此时玩家B可以选择5或3中的一个，…

### Day5
>######  1、输入一个矩阵，按照从外向里以顺时针的顺序依次打印出每一个数字，<br>例如，如果输入如下矩阵： [[1,2,3,4],[5,6,7,8],[9,10,11,12],[13,14,15,16]]<br>则依次打印出数字1,2,3,4,8,12,16,15,14,13,9,5,6,7,11,10.

### Day6
>######  1、从扑克牌中随机抽取5张牌，判断是不是一个顺子，即这五张牌是不是连续的。2~10为数字本身，A为1，J为11，Q为12，K为13，而大小王为0，可以看成任意数字。

### Day7
>######  1、斐波那契数列，要求输入一个整数n，输出斐波那契数列的第n项。

### Day8
>######  1、青蛙跳台阶问题。一只青蛙一次可以跳上1级台阶，也可以跳上2级。求该青蛙跳上一个n级的台阶总共有多少种跳法。（即为斐波那契问题，只是往前走了一位，1,2,3,5,8....f(0)=1 －－假设n级台阶，那么第一步就有两种情况，跳一步，跟跳两步。<br>情况一：跳一步，那么接下去的就是f(n-1)；<br>情况二：跳两步，那么接下去的就是f(n-2)。<br>所以跳法总数是f(n)=f(n-1)+f(n-2)。）

>######  2、变态跳台阶问题。一只青蛙一次可以跳上1级台阶，也可以跳上2级……它也可以跳上n级。求该青蛙跳上一个n级的台阶总共有多少种跳法。（斐波那契变形f(0)=f(1)=1，1,1,2,4,8...那么第一步就有ｎ种情况，跳一步、跳两步、...、跳ｎ步。<br>情况一：跳一步，那么接下去的就是f(n-1)；<br>情况二：跳两步，那么接下去的就是f(n-2)；<br>...<br>情况ｎ：跳ｎ步，那么接下去的就是f(0)。<br>所以跳法总数是f(n)=f(n-1)+f(n-2)+...+f(0)=2^(n-1)*f(0)。）