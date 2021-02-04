

**第1章 概论——多视图几何之旅**


1.1 引言——无处不在的射影几何

1.2摄像机投影

1.3由一幅以上的视图重构

1.4三视图几何

1.5四视图几何和n视图重构

1.6转移

1.7欧氏重构

1.8自标定

1.9收获Ⅰ：3D图形模型

1.10收获Ⅱ：视频增强

**第0篇基础知识：射影几何、变换和估计**

本篇大纲

**第2章2D射影几何与变换**

2.1平面几何

2.22D射影平面

2.3射影变换

2.4变换的层次

2.51D射影几何

2.6射影平面的拓扑

2.7从图像恢复仿射和度量性质

2.8二次曲线的其他性质

2.9不动点与直线

2.10结束语

**第3章3D射影几何与变换**

3.1点和射影变换

3.2平面、直线和二次曲面的表示和变换

3.3三次绕线

3.4变换的层次

3.5无穷远平面

3.6绝对二次曲线

3.7绝对对偶二次曲面

3.8结束语

**第4章估计——2D射影变换**

4.1直接线性变换（DLT）算法

4.2不同的代价函数

4.3统计代价函数和最大似然估计

4.4变换不变性和归一化

4.5迭代最小化方法

4.6算法的实验比较

4.7鲁棒估计

4.8单应的自动计算

4.9结束语

**第5章算法评价和误差分析**

5.1性能的上下界

5.2估计变换的协方差

5.3协方差估计的蒙特卡洛法

5.4结束语

**第1篇摄像机几何和单视图几何**

本篇大纲

**第6章摄像机模型**

6.1有限摄像机

6.2射影摄像机

6.3无穷远摄像机

6.4其他摄像机模型

6.5结束语

**第7章摄像机矩阵P的计算**

7.1基本方程

7.2几何误差

7.3受限摄像机的估计

7.4径向失真

7.5结束语

**第8章进一步讨论单视图几何**

8.1射影摄像机对平面、直线和二次曲线的作用

8.2光滑曲面的图像

8.3射影摄像机对二次曲面的作用

8.4摄像机中心的重要性

8.5摄像机标定与绝对二次曲线的图像

8.6消影点与消影线

8.7仿射3D测量和重构

8.8由单视图确定摄像机标定K

8.9单视图重构

8.10标定二次曲线

8.11结束语

**第2篇两视图几何**

本篇大纲

**第9章对极几何和基本矩阵**

9.1对极几何

9.2基本矩阵F

9.3由特殊运动产生的基本矩阵

9.4基本矩阵的几何表示

9.5恢复摄像机矩阵

9.6本质矩阵

9.7结束语

**第10章摄像机和结构的3D重构**

10.1重构方法概述

10.2重构的多义性

10.3射影重构定理

10.4分层重构

10.5直接重构——利用地面知识

10.6结束语

**第11章基本矩阵F的计算**

11.1基本方程

11.2归一化8点算法

11.3代数最小化算法

11.4几何距离

11.5算法的实验评估

11.6F的自动计算

11.7计算F的特殊情形

11.8其他元素的对应

11.9退化

11.10计算F的几何解释

11.11对极线的包络

11.12图像矫正

11.13结束语

**第12章结构计算**

12.1问题陈述

12.2线性三角测量法

12.3几何误差代价函数

12.4Sampon近似（一阶几何矫正）

12.5最优解

12.6估计3D点的概率分布

12.7直线重构

12.8结束语

**第13章场景平面和单应**

13.1给定平面的单应和逆问题

13.2给定F和图像对应下平面诱导的单应

13.3由平面诱导的单应计算F

13.4无穷单应H∞

13.5结束语

**第14章仿射对极几何**

14.1仿射对极几何

14.2仿射基本矩阵

14.3由图像点对应估计FA

14.4三角测量

14.5仿射重构

14.6 Necker反转和浅浮雕多义性

14.7计算运动

14.8结束语

**第3篇三视图几何**

本篇大纲

**第15章三焦点张量**

15.1三焦点张量的几何基础

15.2三焦点张量和张量记号

15.3转移

15.4三幅视图的基本矩阵

15.5结束语

**第16章三焦点张量T 的计算**

16.1基本方程组

16.2归一化线性算法

16.3代数最小化算法

16.4几何距离

16.5算法的实验评价

16.6T的自动计算

16.7计算T的特殊情形

16.8结束语

**第4篇N视图几何**

本篇大纲

**第17章 N线性和多视图张量**

17.1双线性关系

17.2三线性关系

17.3四线性关系

17.4四张平面的交

17.5计数讨论

17.6独立方程数

17.7选取方程

17.8结束语

**第18章N视图计算方法**

18.1射影重构——捆集调整

18.2仿射重构——分解算法

18.3非刚性分解

18.4射影分解

18.5利用平面的射影重构

18.6由序列重构

18.7结束语

**第19章自标定**

19.1引言

19.2代数框架和问题陈述

19.3利用绝对对偶二次曲面标定

19.4 Kruppa方程

19.5 分层解法

19.6 由旋转摄像机标定

19.7 由平面自标定

19.8 平面运动

19.9 单轴旋转——转台运动

19.10双眼装置的自标定

19.11结束语

**第20章对偶**

20.1CarlssonWeinshall对偶

20.2简化重构

20.3结束语

**第21章正负性**

21.1准仿射变换

21.2摄像机的前面和后面

21.33维点集合

21.4获得一个准仿射重构

21.5变换正负性的效果

21.6定向

21.7正负性不等式

21.8哪些点在第三幅视图中可见

21.9哪些点在前面

21.10结束语

**第22章退化配置**

22.1计算摄像机投影矩阵

22.2两视图中的退化特性

22.3CarlssonWeinshall对偶

22.4三视图临界配置

22.5结束语



