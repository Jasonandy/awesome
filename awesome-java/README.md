---
typora-root-url: ..
---

<p align=center>
  <a href="https://github.com/Jasonandy/devtools">
    <img src="http://upload-images.jianshu.io/upload_images/7802425-9eb1bcd006e34aa6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" alt="devtools" >
  </a>
</p>
<p align=center>
  You are what you want to be. - w.b
</p>

# awesome
* Project：awesome-java
* OfficialWebsite：http://awesome.ucaner.cn
* describe：整理收集各类Java学习资料


> awesome-java
+ [interview](./interview)
  - [目录结构](./interview/ReadMe.md)

+ [docs](./docs)
  - [Java 虚拟机面试题全面解析](./docs/Java虚拟机面试题全面解析.pdf)
  - [Java集合详解](./docs/Java集合详解.pdf)
  - [阿里巴巴Java开发手册v1.2.0](./docs/阿里巴巴Java开发手册v1.2.0)

  ​


## 一、[DataStructure 数据结构](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/DataStructure)

### 1.数据结构和算法

​	推荐书籍：(推荐书籍：剑指offer、编程之美、Cracking、程序员代码面试指南，特别是这四本书上的重复题)

#### 1) **数组与链表**

#### 数组：

```java
//创建数组
int c[] = {2,3,6,10,99};
int[] d = new int[10];
```

```java
/**
* 数组检索
* @param args
*/
public static void main(String[] args) {
  String name[];

  name = new String[5];
  name[0] = "egg";
  name[1] = "erqing";
  name[2] = "baby";

  for(int i = 0; i < name.length; i++){
    System.out.println(name[i]);
  }
}

/*
* 插入 
* @param old
* @param value
* @param index
* @return
*/
public static int[] insert(int[] old, int value, int index) {  
  for (int k = old.length - 1; k > index; k--)  
    old[k] = old[k - 1];  
  old[index] = value;  
  return old;  
}  

/**
 * 遍历
 * @param data
 */
public static void traverse(int data[]) {
  for (int j = 0; j < data.length; j++) {
    System.out.println(data[j] + " ");
  }
}

/**
* 删除 
* @param old
* @param index
* @return
*/
public static int[] delete(int[] old, int index) {
  for (int h = index; h < old.length - 1; h++) {
    old[h] = old[h + 1];
  }
  old[old.length - 1] = 0;
  return old;
}
```

**Tips:数组中删除和增加元素的原理**：增加元素，需要将index后面的依次往后移动，然后将值插入index位置，删除则是将后面的值一次向前移动。

数组表示相同类型的一类数据的集合，下标从0开始。

####**单链表：**

![](http://img.my.csdn.net/uploads/201304/13/1365855052_1221.jpg)

**队列和栈，出栈与入栈。**

**链表的删除、插入、反向。**

**字符串操作。**

**Hash表的hash函数，冲突解决方法有哪些。**

**各种排序：冒泡、选择、插入、希尔、归并、快排、堆排、桶排、基数的原理、平均时间复杂度、最坏时间复杂度、空间复杂度、是否稳定。**

**快排的partition函数与归并的Merge函数。**

**对冒泡与快排的改进。**

**二分查找，与变种二分查找。**

**二叉树、B+树、AVL树、红黑树、哈夫曼树。**

**二叉树的前中后续遍历：递归与非递归写法，层序遍历算法。**

二叉树的前序遍历：



**图的BFS与DFS算法，最小生成树prim算法与最短路径Dijkstra算法。**

**KMP算法。**

**排列组合问题。**

**动态规划、贪心算法、分治算法。（一般不会问到）**

**大数据处理：类似10亿条数据找出最大的1000个数.........等等**



#### 2） 数据ArrayList Vector LinkedList







## 二、[InterviewExperience 面试经历](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/InterviewExperience)

### 1.面试相关图谱

![Interview](/awesome-java/media/Interview.png)

### 2.个个公司的面试资料收集





## 三、[JavaSE 基础部分](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/JavaSE)

### 1.JavaSE知识图谱

![JavaSE](/awesome-java/media/JavaSE.png)

### 2. 



## 四、[Network 网络相关](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/Network)

### 1.网络面试图谱

![network](/awesome-java/media/network.png)

### 2.





## 五、[ReadingNotes 读书笔记](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/ReadingNotes)

### 1.读书笔记图谱

![ReadingNotes](/awesome-java/media/ReadingNotes.png)

### 2.





## 六、[algorithm 算法相关](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/algorithm)

### 1.算法面试图谱

![algorithm](/awesome-java/media/algorithm.png)





### 2.



## 七、[bat-java BAT面试](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/bat-java)





## 八、[colnotes 面试笔记收集](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/colnotes)





## 九、[easy-job](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/easy-job)





## 十、[jvm 虚拟机相关](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/jvm)





## 十一、[os 操作系统](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/os)





## 十二、[other-view 其他相关](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/other-view)





## 十三、[pattern 设计模式](https://github.com/Jasonandy/awesome/tree/master/awesome-java/interview/pattern)





<p align=center>
  <a href="https://github.com/Jasonandy/devtools">
    <img src="http://upload-images.jianshu.io/upload_images/7802425-bb910b4ae954107a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" alt="devtools" >
  </a>
</p>