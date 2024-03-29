# 杂乱知识点

## 数学专题
### 最优化 
  Boyod 《Convex Optimization》
目录速览：
  --
  1 引言 论述了数学优化，最小二乘与线性规划，凸优化，非线性优化，全书概述，字符约定。
  
  I 理论篇
  ----
  
  2 凸集 论述了仿射集和凸集，重要例子，保持凸性的运算，广义不等式，超平面划分与支持，对偶锥与广义不等式。
  
  3 凸函数 论述了一些特性和举例，保持凸性的运算，共轭函数，拟凸函数，log-convex与log-concave对数凸、凹函数，满足广义不等式的凸性。
  
  4 凸优化问题 论述了优化问题，凸优化，线性优化问题，二次优化问题，几何规划，广义不等式约束，向量优化。
  
  5 对偶性 论述了Lagrange对偶函数，Lagrange对偶问题，几何解释，鞍点解释，最优条件，灵敏度分析，举例，可替代原理-表示原理？，广义不等式。
  
  II 应用篇
  ----
  
  6 近似与拟合 论述了范数近似，最小范数问题，正则化近似，鲁棒近似，函数拟合和插值。
  
  7 统计学估计 描述了参数分布估计，非参数分布估计，最优检测器设计和假设检验，Chebyshev和Chernoff边界，实验设计。
  
  8 几何问题 描述了集合映射，集合距离，欧氏距离和角度问题，外容积椭球?，中心化，分类，摆放位置，平面规划。
  
  III 算法篇
  ----
  
  9 无约束最小化 论述了无约束最小化问题，下降方法，梯度下降，最速下降，牛顿法，自洽，实现。
  
  10 等式约束最小化 论述了等式约束最小化问题，带等式约束的牛顿法，牛顿法的不可行之处？，实现。
  
  11 内点法 论述了不等式约束最小化问题，对数障碍函数和中心路径，障碍法，可行性和一阶方法，自洽的复杂度分析，带广义不等式的问题，原始-对偶内点法，实现。
  
  附录篇
  
  A 数学背景 范数、分析、函数、导数、线性代数。
  
  B 二次规划问题 单约束二次优化，S引理，两对称矩阵的值域，强对偶结果证明。
  
  C 数值线性代数背景 矩阵结构及算法复杂度。利用矩阵分解求解线性等式，LU、Cholesky、LDL分解，块消除和Schur补操作，求解未定线性等式。
  


## 图像处理专题
  | 书籍 《Handbook of image processing and computer vision》全三册主题
  
      从能量到图像，https://link.springer.com/book/10.1007/978-3-030-38148-6
      
      从图像到模式，https://link.springer.com/book/10.1007/978-3-030-42374-2
      
      从模式到物体. https://link.springer.com/book/10.1007/978-3-030-42378-0
  
  这套书的好处，可以将图像处理的各种知识点串接称为一个完整的体系，从光的传播到数字图像的获取，到底层图像的处理，到高层特征或模式的提取，再到三维重建。
  三维重建让人不禁想起了Marr的视觉计算导论。
  
  
### 三条脉络：
1. 从物理世界，经光的传播、折射等到数字图像Raw图，然后到数字图像的预处理、变换、去噪、匹配、拼接，提取特征，进行机器学习或DL等作高层抽象语义信息抽取，而后作2.5维\3维重建等或根据语义信息进行控制，形成一个闭环回路.
2. 上述每一小步以历史发展脉络展开，抑或以发展脉络展开.
3. 上述各步骤具体工业化的方案如何，成熟的算法库怎样构建每个模块？


## 机器学习专题
### 脉络一 按照机器学习的各个山头划分
  线性回归、SVM、决策树、
  
### 脉络二 按思路衍生划分
  感知器、神经网络、CNN等DL一派.
  核方法的发展脉络.
  无监督学习的发展脉络.
  鲁棒性的发展脉络.
  loss演变的脉络.
  数据集演变的脉络：规模，类别，利用方式，衡量指标等.
  基于图的方法的发展脉络？
  可解释性发展脉络.
  维持在线增量学习的思路.
  扩展无监督半监督、弱监督等的思路.  
### 脉络三 按照应用领域划分
  图像
  NLP
  推荐网络等
  生物信息
  强化学习、多臂老虎机、智能体等
  芯片、PCB版布局
  
### 脉络四 按照开源算法库的实现方式划分
  OpenCV
  PCL
  pytorch等等

  
