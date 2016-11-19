﻿# guohua-cpp

#week1
<b>day1</b>：1的个数  描述:给定一个正整数N，输出从1——N中1 的个数，例如：N=10，1 的个数是2, （1,10）<br>
<b>day2</b>: 排序算法（冒泡，选择排序和shell） 基本排序算法<br>
<b>day3</b>：整数排序  <br>
<b>day4</b>：链表，队列和栈<br>
<b>day5</b>：进制准换  对一个10进制正整数，输出其对应的12进制数：<br>

#week2
<b>day1</b>：字符串反翻转， 例如：输入：“hello guo hua!”   输出：“hua! guo hello” <br>
<b>day2</b>：字符串排列， 例如“abc” 输出所有的排序可能 abc acb bac bca cba cab<br>
<b>day3</b>：链表（1）在O(1)的时间内删除链表节点；（2）找到链表的第K个节点和倒数第K个节点；（3）翻转链表。数组（4）调整数组是顺序是奇数位于偶数之前。<br>
<b>day4</b>：左旋转字符串：把字符串前面的若干个字符转移到字符串的尾部。比如输入字符串“abcdefg”和数字2，得到左旋转2位的结果“cdefgab”;<br>
<b>day5</b>：删除链表中的重复节点，例如：1->2->2->3->3->4->5  得到的结果(1)是1->2->4->5，若得到的结果(2)是1->2->3->4->5,分别实现;<br>

#week3 
<b>还是字符串和数组以及链表的问题，只是day5出现了新的知识，一天一个不要看多</b><br>
<b>day1</b>：（1）寻找数组中的最大值和最小值，例如 {5,6,8,3,7,9} （2）数组的循环移位，具体点讲就是把一个含有N个元素的数组循环右移K位，比如：abcd1234-> 4abcd123->34abcd12->234abcd1->1234abcd,这样的循环移位。<br>
<b>day2</b>： 字符串移位包含问题，给定两个字符串S1和S2，判断S2能否被S1所做的循环移位得到的字符串包含，给定S1=ABCDE，S2=CDEA，则返回true；若给定S1=ABCDE，S2=ACBD，则返回false。<br>
<b>day3</b>：（1）从一个没有给定头结点的链表中，删除一个给定结点。(2)给定一个链表头结点，要求从尾到头打印出来<br>
<b>day4</b>： 给定两个有序的链表 1—>3->5->7->9 和链表 2->4->6->8->10, 现在要把它们重新合并成一个新的有序链表。<br>
<b>day5</b>：（1）判断一个点P(x,y)与点（点A(x1,y1)和点B(x2,y2)）给定的一条直线的位置关系，也就是点P是在线的左边还是右边亦或是在直线上。（2）判断一个给定的点P是否在一个三角形ABC内。  点的数据结构定义为：struct point{double x,y;};<br>
<b>day6</b>：（1）判断两个链表是否相交;(2)判断一个链表是否有环。<br>
<b>day7</b>：（1）连续子数组的最大和；例如 int a[]={-2,5,3,-6,4,-8,6};(2)快速找出满足给定条件的两个数，例如，int a[]={5,6,1,4,7,8,9}.找到满足两个满足和为10的数；<br>
<b>day8</b>：（1）把数组排成最小的数，数组是这样[1]int a={4,7,9,2,3,1},[2] int a={3,32,321}；（2）寻找丑数，【丑数：把只含有因子2,3,5的数称为丑数，习惯上把1当做第一个丑数，例如6是丑数，14不是丑数】求按从小到大的第1500个丑数;<br>

#week4
<b>day1</b>：对int arr[] = { 1, 2, -3, 10, -4, 7, 12, -5 };利用快速排序得到递增序列。补充问题：找出数组中出现次数超过一半的数字，例如 int arr[]={1,2,4,5,2,2,2,2,9,2},2出现了6次，超过数组长度一半，输出2。<br>
<b>day2</b>：1，找到数组中的最小的K个数，例如，数组int arr[]={7,0,2,4,9,1,54,89,32,78},k=3,则最小的K个数是0,1,2。2、统计排序数组中数字出现的次数，例如，数组{1,3,4,5,5,5,5,6,8}和数字5,5出现了4次，输出4.（熟悉二分查找）</br>
<b>day3</b>：1，对int arr[] = { 1, 2, -3, 10, -4, 7, 12, -5 };利用归并排序得到递增序列。2、在一个整型数组中，除一个数出现一次之外，其他数都出现了两次，怎样找到快速找到这个只出现一次的数？如果只出现一次的数有两个，要找这两个的时候又怎么解决呢？<br>
<b>day4</b>：1、一个数的二进制中的1的个数。2、交换两个数。3、不用加减乘除做加法运算。4、求两个数的平均数。<br>
<b>day5</b>：（回顾一下栈和队列的基本定义和性质）用两个栈实现一个队列。<br>

#week5
<b>day1</b>：1、（问题回顾）输入两个链表找到他们的第一个公共节点；2、回顾二叉树的前序、后序、中序遍历，给定一个二叉树的前序遍历{1,2,4,7,3,5,6,8}和中序遍历{4,7,2,1,5,3,8,6}，求出二叉树的后序遍历，并重建此二叉树（有思路就OK）。<br>
<b>day2</b>：1、（问题回顾-字符串）替换字符串中的空格为%RT，例如输入"Hello Guo Hua.",输出"Hello%RTGuo%RTHua.";2、树的遍历，（1）分层遍历，（2）之字形遍历，二叉树如图所示:<br>
<img src="http://s15.sinaimg.cn/mw690/002Ip0v1ty6ISuyrVZsce&690" width="250px" height="200px"><br>
分层遍历输出结果为：1-2-3-4-5-6-7-8-9-10，之字形遍历输出结果为：1-3-2-4-5-6-7-10-9-8.<br>
<b>day3</b>：1、树的深度；2、判断一个数是否为二叉平衡树，【二叉平衡树：它是一 棵空树或它的左右两个子树的高度差的绝对值不超过1，并且左右两个子树都是一棵平衡二叉树。】；3、（额外拓展）求N！的末尾0的个数，N为正整数。<br>
<b>day4</b>：1、二叉树的镜像，给定一个二叉树，实现一个二叉树的镜像：如下图，左边是镜像前的树，右边是镜像后的树：
<img src="http://img.blog.csdn.net/20140930164618503" width="500px" height="200px"><br>
2、判断一个二叉树是不是对称的？3、N!的二进制表示的最低位1的在哪个位置？<br>
<b>day5</b>：1、树的序列化；2、树的反序列化。序列化：从根节点开始按照某一遍历方式（比如前序遍历），让二叉树称为一个序列，同时通过此序列还原回原来的二叉树；反序列化正好和这个过程相反。

#week6
<b>day1</b>：1、(问题回顾)菲波那切数列的第n项;2、二叉树中和为某一值的路径。下图为，菲波那切数列算术表示：<br>
<img src="http://www.ruitear.com/github/fib.jpg"><br>
<b>day2</b>：1、栈的压入弹出序列-给定两个数组序列，一个是栈的压入序列，判断第二个是否为该栈的弹出序列。例如：第一个为{1,2,3,4,5}，第二个为{4,5,3,2,1}；2、了解、认识并熟悉堆排序。<br>
<b>day3</b>：1、了解二叉搜索树，给定一个二叉搜索树，找到其中的第K大的节点。2、输入一个数组判断这个该数组是不是某个二叉搜索树的后序遍历的结果。如果是则返回true，否则返回false，假设输入数组中任意两个数都不相同。<br>
<b>day4</b>：1、二叉树非递归的前中后序遍历（主要关注前序和中序，后序先缓缓周末讲）；2、圆圈中剩下的数（约瑟夫环问题）有1,2,3....n这n个数排成一个圆圈，从数字0开始每次从这个圆圈里面删除第m个数。求最后剩下的是哪个数？<br>
<b>day5</b>：1、给定一个二叉树的中的一个节点，找到中序遍历顺序的下一个节点？树的结构中除了有两个分别指向左右子节点的指针外，还有一个指向父节点的指针。<br>

#week7
<b>day1</b>：1、定义栈的数据结构，在该类型中实现一个能够得到栈最小元素的min函数，且调用min、push以及pop的时间复杂度为O(1)，可以借助STL中的stack。<br>
<b>day2</b>：求1+2+3+...+n的和，1、用循环怎么解？；2、不用循环怎么解？；3、不用乘除法、for、while、if、else、switch、case等关键字以及条件判断怎么解？<br>
<b>day3</b>：求树中两个节点的最低公共父节点：1，树是二叉搜索树；2树不是二叉搜索树，而是一个带有指向父节点的指针的树；3、树就是一个普通的二叉树或者多叉树。<br>
<b>day4</b>：树的子结构，输入两颗二叉树A,B，判断B是不是A的子结构。2、const相关问题const与引用和指针、const类型参数与const成员函数。<br>
<b>day5</b>：二叉搜索树与双向链表：输入一个二叉搜索树，将该二叉树转换成一个排序的双向链表。不能创建任何新的节点，只能调整注重节点的指向。

#week8
<b>day1</b>：1、给定一幅N\*N表示的单通道图像，其中每个像素大小为4自己，写一个方法，将图像旋转90度，不利用额外的内存空间？2、有10瓶药丸，其中9瓶装的是1g/粒的药丸，余下的一瓶装有1.1g/粒的药丸。有一个精细的天平，怎么找到这一瓶1.1g/粒的药？天平只能用一次。<br>
<b>day2</b>：1、一个二维数组，每一行都按照从左到右递增的顺序排序，每一列都按照从上到下递增的顺序排序。写一个函数，输入一个这样的二维数组和一个整数，判断这个数组中是否含有这个数。2、有一个8\*8的棋盘，其中的一个对角的两个方格被切掉了。现在有31张牌，每张牌恰好可以覆盖两个方格。用着31张牌能不能覆盖整个棋牌？<br>
<b>day3</b>：1、给两个整数，求两个数的最大公约数；2、有两个水壶，一个能装3升水，一个能装5升；现在要得到4升水，不考虑缺水的问题，且水壶的而形状不规则，没办法得到精确的容量。<br>
<b>day4</b>：1、"Remove duplicates" Given a sorted array, remove the duplicates in place such that each element appear only once and return the new length. Do not allocate extra space for another array, you must do this in place with constant memory. For example, given input array A=[1,1,2]. Your function should return length =2,and A is now [1,2]. 2、扔鸡蛋问题：有100层高的楼，若从第N层或者更高楼层扔鸡蛋，鸡蛋就会破掉。若从第N层以下就不会破掉，给你两个鸡蛋，请找出N，并要求最差情况下扔鸡蛋的次数为最少。<br>
<b>day5</b>：1、Follow up for "Remove duplicates": What if duplicates are allowed at most twice? For example,given sorted array A=[1,1,1,2,2,3],Your function should return length=5,and A is now [1,1,2,2,3].<br>

#week9-week14
<b>boss-work：</b>利用VS、QT和OpenCV编写一个简单GUI应用，实现简单的图像处理（比如：锐化、滤波和分割等）和视频处理任务（例如简单场景的目标跟踪），相关算法代码数据参考中资料相关opencv书籍。  <b><a href="http://pan.baidu.com/s/1eSPwtR8" target="_blank">资料</a></b>-【提取码：uma5】。</br>
