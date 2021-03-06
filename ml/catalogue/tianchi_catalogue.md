**赛题一 工业蒸汽量预测**

1 赛题理解 

1.1 赛题背景 

1.2 赛题目标  

1.3 数据概览 

1.4 评估指标  

1.5 赛题模型 

2 数据探索 

2.1 理论知识 

2.1.1 变量识别  

2.1.2 变量分析  

2.1.3 缺失值处理  

2.1.4 异常值处理  

2.1.5 变量转换  

2.1.6 新变量生成 

2.2 赛题数据探索  

2.2.1 导入工具包  

2.2.2 读取数据 

2.2.3 查看数据  

2.2.4 可视化数据分布 

2.2.5 查看特征变量的相关性  

3 特征工程  

3.1 特征工程的重要性和处理  

3.2 数据预处理和特征处理 

3.2.1 数据预处理  

3.2.2 特征处理 

3.3 特征降维  

3.3.1 特征选择  

3.3.2 线性降维  

3.4 赛题特征工程 

3.4.1 异常值分析  

3.4.2 最大值和最小值的归一化 

3.4.3 查看数据分布 

3.4.4 特征相关性  

3.4.5 特征降维  

3.4.6 多重共线性分析  

3.4.7 PCA处理  

4 模型训练 

4.1 回归及相关模型  

4.1.1 回归的概念  

4.1.2 回归模型训练和预测  

4.1.3 线性回归模型 

4.1.4 K近邻回归模型  

4.1.5 决策树回归模型  

4.1.6 集成学习回归模型 

4.2 赛题模型训练  

4.2.1 导入相关库 

4.2.2 切分数据  

4.2.3 多元线性回归  

4.2.4 K近邻回归 

4.2.5 随机森林回归 

4.2.6 LGB模型回归  

5 模型验证  

5.1 模型评估的概念和方法 

5.1.1 欠拟合与过拟合  

5.1.2 模型的泛化与正则化 

5.1.3 回归模型的评估指标和调用方法  

5.1.4 交叉验证  

5.2 模型调参  

5.2.1 调参  

5.2.2 网格搜索  

5.2.3 学习曲线  

5.2.4 验证曲线  

5.3 赛题模型验证和调参  

5.3.1 模型过拟合与欠拟合  

5.3.2 模型正则化 

5.3.3 模型交叉验证 

5.3.4 模型超参空间及调参  

5.3.5 学习曲线和验证曲线  

6 特征优化  

6.1 特征优化的方法  

6.1.1 合成特征  

6.1.2 特征的简单变换  

6.1.3 用决策树创造新特征 

6.1.4 特征组合  

6.2 赛题特征优化  

6.2.1 导入数据 

6.2.2 特征构造方法  

6.2.3 特征构造函数  

6.2.4 特征降维处理 

6.2.5 模型训练和评估  

7 模型融合 

7.1 模型优化 

7.1.1 模型学习曲线 

7.1.2 模型融合提升技术 

7.1.3 预测结果融合策略 

7.1.4 其他提升方法 

7.2 赛题模型融合 

7.2.1 导入工具包 

7.2.2 获取训练数据和测试数据 

7.2.3 模型评价函数 

7.2.4 采用网格搜索训练模型 

7.2.5 单一模型预测效果 

7.2.6 模型融合Boosting方法 

7.2.7 多模型预测Bagging方法 

7.2.8 多模型融合Stacking方法 

7.2.9 模型验证 

7.2.10 使用lr_reg和lgb_reg进行融合预测 



**赛题二 天猫用户重复购买预测**

1 赛题理解 

1.1 赛题背景 

1.2 数据介绍 

1.3 评估指标 

1.4 赛题分析 

2 数据探索 

2.1 理论知识 

2.1.1 缺失数据处理 

2.1.2 不均衡样本 

2.1.3 常见的数据分布 

2.2 赛题数据探索 

2.2.1 导入工具包 

2.2.2 读取数据 

2.2.3 数据集样例查看 

2.2.4 查看数据类型和数据大小 

2.2.5 查看缺失值 

2.2.6 观察数据分布 

2.2.7 探查影响复购的各种因素 

3 特征工程 

3.1 特征工程介绍 

3.1.1 特征工程的概念 

3.1.2 特征归一化 

3.1.3 类别型特征的转换 

3.1.4 高维组合特征的处理 

3.1.5 组合特征 

3.1.6 文本表示模型 

3.2 赛题特征工程思路 

3.3 赛题特征工程构造 

3.3.1 工具导入 

3.3.2 数据读取 

3.3.3 对数据进行内存压缩 

3.3.4 数据处理 

3.3.5 定义特征统计函数 

3.3.6 提取统计特征 

3.3.7 利用Countvector和TF-IDF提取特征 

3.3.8 嵌入特征 



3.3.9 Stacking分类特征 

4 模型训练 

4.1 分类的概念 

4.2 分类相关模型 

4.2.1 逻辑回归分类模型 

4.2.2 K近邻分类模型 

4.2.3 高斯贝叶斯分类模型 

4.2.4 决策树分类模型 

4.2.5 集成学习分类模型 

5 模型验证 

5.1 模型验证指标 

5.1.1 准确度 

5.1.2 查准率和查全率 

5.1.3 F1值 

5.1.4 分类报告 

5.1.5 混淆矩阵 

5.1.6 ROC 

5.1.7 AUC曲线 

5.2 赛题模型验证和评估 

5.2.1 基础代码 

5.2.2 简单验证 

5.2.3 设置交叉验证方式 

5.2.4 模型调参 

5.2.5 混淆矩阵 

5.2.6 不同的分类模型 

5.2.7 自己封装模型 

6 特征优化 

6.1 特征选择技巧 

6.2 赛题特征优化 

6.2.1 基础代码 

6.2.2 缺失值补全 

6.2.3 特征选择 

**赛题三 O2O优惠券预测**

1 赛题理解 

1.1 赛题介绍 

1.2 赛题分析 

2 数据探索 

2.1 理论知识 

2.1.1 数据探索的定义 

2.1.2 数据探索的目的 

2.1.3 相关Python包 

2.2 初步的数据探索 

2.2.1 数据读取 

2.2.2 数据查看 

2.2.3 数据边界探索 

2.2.4 训练集与测试集的相关性 

2.2.5 数据统计 

2.3 数据分布 

2.3.1 对文本数据的数值化处理 

2.3.2 数据分布可视化 

3 特征工程 

3.1 赛题特征工程思路 

3.2 赛题特征构建 

3.2.1 工具函数 

3.2.2 特征群生成函数 

3.2.3 特征集成函数 

3.2.4 特征输出 

3.3 对特征进行探索 

3.3.1 特征读取函数 

3.3.2 特征总览 

3.3.3 查看特征的分布 

3.3.4 特征相关性分析 

4 模型训练 

4.1 模型训练与评估 

4.2 不同算法模型的性能对比 

4.2.1 朴素贝叶斯 

4.2.2 逻辑回归 

4.2.3 决策树 

4.2.4 随机森林 

4.2.5 XGBoost 

4.2.6 LightGBM 

4.2.7 不同特征效果对比 

4.3 结果输出 

5 模型验证 

5.1 评估指标 

5.2 交叉验证 

5.3 模型比较 

5.4 验证结果可视化 

5.5 结果分析 

5.6 模型调参 

5.7 实际方案 

6 提交结果 

6.1 整合及输出结果 

6.2 结果提交及线上验证 

**赛题四 阿里云安全恶意程序检测**

1 赛题理解 

1.1 赛题介绍 

1.2 赛题分析 

2 数据探索 

2.1 训练集数据探索 

2.1.1 数据特征类型 

2.1.2 数据分布 

2.1.3 缺失值 

2.1.4 异常值 

2.1.5 标签分布 

2.2 测试集数据探索 

2.2.1 数据信息 

2.2.2 缺失值 

2.2.3 数据分布 

2.2.4 异常值 

2.3 数据集联合分析 

2.3.1 file_id分析 

2.3.2 API分析 

3 特征工程与基线模型 

3.1 特征工程概述 

3.1.1 特征工程介绍 

3.1.2 构造特征 

3.1.3 特征选择 

3.2 构造线下验证集 

3.2.1 评估穿越 

3.2.2 训练集和测试集的特征差异性 

3.2.3 训练集和测试集的分布差异性 

3.3 基线模型 

3.3.1 数据读取 

3.3.2 特征工程 



3.3.3 基线构建 

3.3.4 特征重要性分析 

3.3.5 模型测试 

4 高阶数据探索 

4.1 变量分析 

4.2 高阶数据探索实战 

4.2.1 数据读取 

4.2.2 多变量交叉探索 

5 特征工程进阶与方案优化 

5.1 pivot特征构建 

5.1.1 pivot特征 

5.1.2 pivot特征构建时间 

5.1.3 pivot特征构建细节和特点 

5.2 业务理解和结果分析 

5.2.1 结合模型理解业务 

5.2.2 多分类问题预测结果分析 

5.3 特征工程进阶实践 

5.3.1 特征工程基础部分 

5.3.2 特征工程进阶部分 

5.3.3 基于LightGBM的模型验证 

5.3.4 模型结果分析 

5.3.5 模型测试 

6 优化技巧与解决方案升级 

6.1 优化技巧：Python处理大数据的技巧 

6.1.1 内存管理控制 

6.1.2 加速数据处理的技巧 

6.1.3 其他开源工具包 

6.2 深度学习解决方案：TextCNN建模 

6.2.1 问题转化 

6.2.2 TextCNN建模 

6.2.3 数据预处理 

6.2.4 TextCNN网络结构 

6.2.5 TextCNN训练和测试 

6.2.6 结果提交 

7 开源方案学习




