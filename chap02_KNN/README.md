# K-近邻算法（分类）

## 基本思路
1. 存在一个具有标签的样本数据集，即了解每一个样本与分类的对应关系；
2. 输入没有标签的新样本之后
   - 计算新数据与样本数据集中每条数据的距离
   - 根据距离，选择前k个最相似的数据
3. 选择k个数据中出现次数最多的分类，作为新数据的分类。

## 特点
* 优点: 精度高、对异常值不敏感、无数据输入假定
* 缺点：计算复杂度高、空间复杂度高
* 使用数据范围： 数值和标称

## 一般流程
1. 收集数据 ：可以使用任何方法
2. 准备数据 : 距离计算所需要的数值，最好是结构化
3. 分析数据 : 可以使用任何方法
4. 训练算法 ：不适用K-近邻算法
5. 测试算法 ：计算错误率
6. 使用算法 ：首先需要输入样本数据和结构化的输出结果，然后运行Ｋ－近邻算法判定输入数据属于哪个分类，最后执行后续处理.