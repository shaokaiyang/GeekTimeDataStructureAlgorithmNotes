# GeekTimeDataStructureAlgorithmNotes
**记录在《极客时间》平台上《数据结构与算法之美》专栏的学习笔记**  
**作者信息：王争 前Google工程师**  
**课程海报如下：欢迎扫描右下方二维码订阅（有优惠哦）**
  
![课程海报](./picture/datastructure.jpg ) 
# 相关资源链接
* [算法可视化网站](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
* [课程涉及源码GitHub地址](https://github.com/wangzheng0822/algo)

# 目录
* [开篇词](#0)
* [第1讲 为什么要学习数据结构与算法](#1)
* [第2讲 如何系统高效学习数据结构与算法](#2)
* [第3讲 复杂度分析(上、下)](#3)
* [第4讲 数据结构与算法学习书单](#4)
* [第5讲 数组：为什么很多编程语言中数组从0开始编号](#5)
* [第6讲 链表：如何实现LRU淘汰算法？（上）](#6)
* [第7讲 链表：如何轻松写出正确的链表代码？（下）](#7)
* [第8讲 栈：如何实现浏览器的前进和后退功能？](#8)
* [第9讲 队列：队列在线程池中的应用](#9)
* [第10讲 递归：如何用三行代码找到“最终推荐人”](#10)
* [第11讲 排序：为什么插入排序比冒泡排序更受欢迎？（上） ](#11)
* [第12讲 排序：如何用快排思想在O（n）内查找第K大元素？（下）](#12)
* [第13讲 线性排序：如何根据年龄给100万用户数据排序？ ](#13)
* [第14讲 排序优化：如何实现一个通用的、高性能的排序函数？ ](#14)
* [第15讲 二分查找：如何用最省内存的方式实现快速查找功能？（上）](#15)
* [第16讲 二分查找：如何快速定位IP对应的省份？（下）](#16)
* [第17讲 跳表：为什么Redis一定要用跳表来实现有序集合？](#17)
* [第18讲 散列表：word文档中的单词拼写检查功能是如何实现的？（上）](#18)
* [第19讲 散列表：如何打造一个工业级水平的散列表？（中）](#19)
* [第20讲 散列表：为什么散列表和链表经常会一起使用？（下）](#20)
* [第21讲 哈希算法：如何防止数据库中的用户信息被脱库？（上）](#21)
* [第22讲 哈希算法：哈希算法在分布式系统中有哪些应用？（下）](#22)
* [第23讲 二叉树基础：什么样的二叉树适合用数组来存储？（上）](#23)
* [第24讲 二叉树基础：有了高效的散列表，为什么还需要二叉树？（下）](#24)
* [第25讲 红黑树：为什么工程中都用红黑树这种二叉树？（上）](#25)
* [第26讲 红黑树：实现红黑树的技巧（下）](#26)
* [第27讲 递归树：如何借助树来求解递归算法的时间复杂度？](#27)
* [羁绊前行的，不是肆虐的狂风而是内心的迷茫](#27-1)
* [第28讲 堆和堆排序：为什么说堆排序没有快速排序快？](#28)
* [第29讲 堆的应用：如何快速获取Top 10热门的搜索关键词？](#29)
* [第30讲 图的表示：如何存储微博、微信等社交网络中的好友关系？](#30)
* [第31讲 深度和广度优先搜索：如何找出社交网络中的三度好友关系？](#31)
* [第32讲 字符串匹配基础：如何借助哈希算法实现高效字符串匹配？（上）](#32)
* [第33讲 字符串匹配基础：如何实现文本编辑器中的查找功能？（中）](#33)
* [第34讲 字符串匹配基础：如何借助BM算法轻松理解KMP算法？](#34)
* [第35讲 Trie树：如何实现搜索引擎的搜索关键词提示功能？](#35)
* [第36讲 AC自动机：如何用多模式串匹配实现敏感词过滤功能？](#36)
* [第37讲 贪心算法：如何用贪心算法实现Huffman压缩编码？](#37)
* [第38讲 分治算法：大规模计算框架MapReduce中的分治思想？](#38)
* [测一测你的算法阶段学习成果](#38-1)
* [第39讲 回溯算法：从电影《蝴蝶效应》中学习回溯算法的核心思想](#39)
* [第40讲 初识动态规划：如何巧妙解决“双十一”购物时的凑单问题？](#40)
* [我是怎么学习《数据结构与算法之美》的](#40-1)
* [第41讲 动态规划理论：最优子结构、无后效性等](#41)
* [第42讲 动态规划实战：如何实现搜索引擎中的拼写纠错功能？](#42)
* [第43讲 拓扑排序：如何确定代码源文件的编译依赖关系？](#43)
* [第44讲 最短路径：地图软件是如何计算出最优出行路径的？](#44)
* [第45讲 位图：如何实现网页爬虫中的URL去重功能？](#45)
* [第46讲 概率统计：如何利用朴素贝叶斯算法过滤垃圾短信？](#46)
* [第47讲 向量空间：如何实现一个简单的音乐推荐系统？](#47)
* [第48讲 B+树：MySQL数据库索引是如何实现的？](#48)
* [第49讲 搜索：如何用A*搜索算法实现游戏中的寻路功能？](#49)
* [未完待续……](#99)

# 正文
<h2 id="0">开篇词 从今天起，跨过“数据结构与算法”这道坎</h2>
作者王争，毕业于西安交通大学，读研期间因师兄给的《算法导论》，毕业后进入Google从事翻译相关开发工作。基础知识就像是一座大楼的地基，决定技术高度。想要快速做出点事情，前提条件一定是基础能力过硬，“内功”要到位。  

<h2 id="1">第1讲 为什么要学习数据结构与算法</h2>
为什么要学习数据结构与算法？
  
* 通过大厂面试； 
* 业务开发工程师，真的愿意做一辈子CRUD boy? 对阅读框架源码和理解其背后的设计思想很有用；  
* 基础架构研发工程师，写出达到开源水平的框架才是你的目标！高手对决看细节，这些细节包括算法是否优化、数据存取效率是否高、内存是否节省；
* 对编程有追求，不想被行业淘汰，就不能只会写凑合能用的代码；  

<h2 id="2">第2讲 如何系统高效学习数据结构与算法</h2>
一、数据结构与算法的定义与关系
   
数据结构就是一组数据的存储结构，算法就是操作数据的一组方法，数据结构是为算法服务的，算法要作用在特定的数据结构上。
  
二、学习的重点： 
* 复杂度分析  
* 10个常用数据结构：数组、链表、栈、队列、散列表、二叉树、堆、跳表、图、Trie树；  
* 10个常用算法：递归、排序、二分查找、搜索、哈希算法、贪心算法、分治算法、回溯算法、动态规划、字符串匹配算法；
  
![数据结构与算法学习图谱](./picture/LearningMap.jpg)  
  
三、学习技巧：
* 对于一个新知识，一定要学习它的来历，自身的特点，适合解决的问题，实际的应用场景；  
* 边学边练，适度刷题；  
* 多问、多思考、多互动；  
* 知识需要沉淀，不要试图一下子掌握所有；  

<h2 id="3">第3讲 复杂度分析(上、下)</h2>
一、为什么要进行复杂度分析及什么是复杂度分析  

事后统计法具有局限性，因此需要一个不用具体的测试数据来测试，就可以粗略估计算法执行效率的方法。数据结构与算法解决的是“如何让计算机更快时间、更省空间的解决问题”，因此需要从执行时间和占用空间两个维度进行评估，复杂度描述的是算法执行时间（占用空间）与数据规模的增长之间的关系。掌握复杂度分析，能编写出性能更优的代码，有利于降低系统开发和维护成本。
* 测试结果非常依赖测试环境；  
* 测试结果受数据规模的影响很大： 
 
二、如何进行复杂度分析，大O表示及计算法则  
大O复杂度表示，T（n）= O(f(n)),T（n）表示代码执行时间；n表示数据规模；f(n)表示每行代码执行的次数总和；O表示代码执行时间和f(n)表达式成正比；其表示代码执行时间随数据规模增长的变化趋势，也叫渐进时间复杂度。在n很大时，公式中的低阶、常量、系数三部分并不左右增长趋势，所以可以忽略。  
时间复杂度分析：  
* 只关注循环执行次数最多的一段代码。 
* 加法法则：总复杂度等于量级最大的那段代码的复杂度。 
* 乘法法则：嵌套代码的复杂度等于嵌套内外代码复杂度的乘积。   

三、常用的时间（空间）复杂度  
时间复杂度分析：
* 多项式量级：O(1),O(logn),O(n),O(nlogn),O(n^k),O(m+n),O(m*n)  
* 非多项式量级：O（2^n）,O(n!)  

空间复杂度分析：O（1）,O(n),O(n^2)  
四、如何掌握好复杂度分析？  
关键在于多练习，多思考，熟能生巧。

五、复杂度深度分析  
* 最好情况时间复杂度：在理想情况下，执行这段代码的时间复杂度。  
* 最坏情况复杂度：在最糟糕情况下，执行这段改吗的时间复杂度。  
* 平均时间复杂度：取所有情况的平均值，也叫加权平均时间复杂度或期望时间复杂度。  
* 均摊时间复杂度：每一次O（n）的插入操作后都跟着n-1次O（1）次插入操作，所以把耗时较多的操作时间均摊到接下来的n-1耗时少的操作上，这样时间复杂度就为O（1）。适用场景为在一组连续操作中，大部分情况下的时间复杂度都很低，只有个别情况的时间复杂度比较高，并且这些操作之间存在前后连贯的时序关系。  
```c
 // array 表示一个长度为 n 的数组
 // 代码中的 array.length 就等于 n
 int[] array = new int[n];
 int count = 0;
 
 void insert(int val) {
    if (count == array.length) {
       int sum = 0;
       for (int i = 0; i < array.length; ++i) {
          sum = sum + array[i];
       }
       array[0] = sum;
       count = 1;
    }

    array[count] = val;
    ++count;
 }

```
上述代码功能：往数组中插入数据，若数组有空闲位置，则直接插入；如果数组满，则遍历求和之后将sum值放在数组首位继续插入数据。其在数组非满时最好时间复杂度为O（1），在数组满时时间复杂度为O（n），平均时间复杂度为O(1)。  
* 平均时间复杂度（代码在不同情况下复杂度出现量级差别，用代码所有可能情况下的执行次数的加权平均值表示）VS均摊时间复杂度（满足两个条件，高级别复杂度操作远大于低级别复杂度操作；两种操作出现具有时序规律）  
  
<h2 id="4">第4讲 数据结构与算法学习书单</h2>
数据结构与算法学习书单推荐  
针对入门的趣味书  
* 《大话数据结构》其把理论讲的很有趣，不枯燥。针对每个数据结构和算法都结合生活中的例子进行了详解。  
* 《算法图解》“像小说一样有趣的算法入门书”。  

针对特定编程语言的教科书  
* 《数据结构与算法分析：C语言描述、C++描述、Java描述、JavaScript描述、Python描述》  

面试必刷宝典  
* 《剑指offer》涵盖了所有经典、常见的面试题。  
* 《编程珠玑》讲了很多针对海量数据的处理技巧。  
* 《编程之美》有一定难度，适合喜欢钻研算法的人。  

经典大部头  
* 《算法导论》  
* 《算法》  

殿堂级经典  
* 《计算机程序设计艺术》这套书的深度、广度、系统性、全面性是其他所有数据结构与算法书籍都无法相比的，看这本书需要具备扎实的数学、算法、计算机基础。  

闲暇阅读  
* 《算法帝国》  
* 《数学之美》  
* 《算法之美》  

<h2 id="5">第5讲 数组：为什么很多编程语言中数组从0开始编号</h2>
<h2 id="6">第6讲 链表：如何实现LRU淘汰算法？（上）</h2>
<h2 id="7">第7讲 链表：如何轻松写出正确的链表代码？（下）</h2>
<h2 id="8">第8讲 栈：如何实现浏览器的前进和后退功能？</h2>
<h2 id="9">第9讲 队列：队列在线程池中的应用</h2>
<h2 id="10">第10讲 递归：如何用三行代码找到“最终推荐人”</h2>
<h2 id="11">第11讲 排序：为什么插入排序比冒泡排序更受欢迎？（上）</h2>
<h2 id="12">第12讲 排序：如何用快排思想在O（n）内查找第K大元素？（下）</h2>
<h2 id="13">第13讲 线性排序：如何根据年龄给100万用户数据排序？ </h2>
<h2 id="14">第14讲 排序优化：如何实现一个通用的、高性能的排序函数？ </h2>
<h2 id="15">第15讲 二分查找：如何用最省内存的方式实现快速查找功能？（上）</h2>
<h2 id="16">第16讲 二分查找：如何快速定位IP对应的省份？（下） </h2>
<h2 id="17">第17讲 跳表：为什么Redis一定要用跳表来实现有序集合？</h2>
<h2 id="18">第18讲 散列表：word文档中的单词拼写检查功能是如何实现的？（上）</h2>
<h2 id="19">第19讲 散列表：如何打造一个工业级水平的散列表？（中）</h2>
<h2 id="20">第20讲 散列表：为什么散列表和链表经常会一起使用？（下）</h2>
<h2 id="21">第21讲 哈希算法：如何防止数据库中的用户信息被脱库？（上）</h2>
<h2 id="22">第22讲 哈希算法：哈希算法在分布式系统中有哪些应用？（下）</h2>
<h2 id="23">第23讲 二叉树基础：什么样的二叉树适合用数组来存储？（上）</h2>
<h2 id="24">第24讲 二叉树基础：有了高效的散列表，为什么还需要二叉树？（下）</h2>
<h2 id="25">第25讲 红黑树：为什么工程中都用红黑树这种二叉树？（上）</h2>
<h2 id="26">第26讲 红黑树：实现红黑树的技巧（下）</h2>
<h2 id="27">第27讲 递归树：如何借助树来求解递归算法的时间复杂度？</h2>
<h2 id="27-1">羁绊前行的，不是肆虐的狂风而是内心的迷茫</h2>
<h2 id="28">第28讲 堆和堆排序：为什么说堆排序没有快速排序快？</h2>
<h2 id="29">第29讲 堆的应用：如何快速获取Top 10热门的搜索关键词？</h2>
<h2 id="30">第30讲 图的表示：如何存储微博、微信等社交网络中的好友关系？</h2>
<h2 id="31">第31讲 深度和广度优先搜索：如何找出社交网络中的三度好友关系？</h2>
<h2 id="32">第32讲 字符串匹配基础：如何借助哈希算法实现高效字符串匹配？（上）</h2>
<h2 id="33">第33讲 字符串匹配基础：如何实现文本编辑器中的查找功能？（中）</h2>
<h2 id="34">第34讲 字符串匹配基础：如何借助BM算法轻松理解KMP算法？（下）</h2>
<h2 id="35">第35讲 Trie树：如何实现搜索引擎的搜索关键词提示功能？</h2>
<h2 id="36">第36讲 AC自动机：如何用多模式串匹配实现敏感词过滤功能？</h2>
<h2 id="37">第37讲 贪心算法：如何用贪心算法实现Huffman压缩编码？</h2>
<h2 id="38">第38讲 分治算法：大规模计算框架MapReduce中的分治思想？</h2>
<h2 id="38-1">测一测你的算法阶段学习成果</h2>
<h2 id="39">第39讲 回溯算法：从电影《蝴蝶效应》中学习回溯算法的核心思想</h2>
<h2 id="40">第40讲 初识动态规划：如何巧妙解决“双十一”购物时的凑单问题？</h2>
<h2 id="40-1">我是怎么学习《数据结构与算法之美》的</h2>
<h2 id="41">第41讲 动态规划理论：最优子结构、无后效性等</h2>
<h2 id="42">第42讲 动态规划实战：如何实现搜索引擎中的拼写纠错功能？</h2>
<h2 id="43">第43讲 拓扑排序：如何确定代码源文件的编译依赖关系？</h2>
<h2 id="44">第44讲 最短路径：地图软件是如何计算出最优出行路径的？</h2>
<h2 id="45">第45讲 位图：如何实现网页爬虫中的URL去重功能？</h2>
<h2 id="46">第46讲 概率统计：如何利用朴素贝叶斯算法过滤垃圾短信？</h2>
<h2 id="47">第47讲 向量空间：如何实现一个简单的音乐推荐系统？</h2>
<h2 id="48">第48讲 B+树：MySQL数据库索引是如何实现的？</h2>
<h2 id="49">第49讲 搜索：如何用A*搜索算法实现游戏中的寻路功能？</h2>
<h2 id="99">未完待续……</h2>

## 觉得有价值 感谢支持
![赞赏码](./picture/AppreciationCode.jpg ) 