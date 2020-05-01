# 对应模块有具体文档

个人博客：[https://www.bianzw.cn](https://www.bianzw.cn) 

# 点云可视

1. 点云可视化
2. 显示点云颜色特征
3. 自定义点云颜色特征
4. 以颜色区别深度
5. 一个视图窗口显示点云
6. 法线及其他特征的可视化
7. 自定义交互

# 云关键点

1. NARF
2. 3DHarris

# 点云存储

1. kdtree_近邻搜索+半径内最近邻搜索
2. 八叉树空间分割进行点分布区域的压缩
3. 基于Octree的空间划分及搜索操作
4. 无序点云数据集的空间变化检测

# 特征提取

1. 点云表面法线特征
2. 用积分图计算有序点云的法线
3. PFH点特征直方图描述子
4. FPFH点特征直方图
5. VFH视点特征直方图描述子
6. NARF_从深度图像中提取NARF关键点
7. RoPs特征描述子
8. 惯性偏心矩描述子_包围盒
9. GASD全局一致的空间分布描述子特征

# 点云配准

1. ICP迭代最近点点云配准
2. NDT正态分布变换进行配准

# 点云分割

1. 随机采样一致性_分割球模型和平面模型
2. 随机采样一致性_分割出平面外的点
3. 圆柱体分割依据法线信息分割_平面上按圆柱体模型分割得到圆柱体点云
4. 欧氏距离分割_平面模型分割平面_平面上按_聚类得到_多个点云团
5. 基于法线差值和曲率差值的区域聚类分割算法
6. 基于颜色差值的区域聚类分割算法
7. 最小分割算法_分割点云_基于距离加权的最小图分割算法
8. 基于不同领域半径估计的法线的差异类_欧氏聚类_分割_点云
9. 超体聚类是一种图像的分割方法
10. 使用渐进式形态学滤波器_识别地面
