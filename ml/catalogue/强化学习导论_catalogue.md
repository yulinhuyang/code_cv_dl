**第1章 导论** 

1.1 强化学习  

1.2 示例  

1.3 强化学习要素  

1.4 局限性与适用范围  

1.5 扩展实例：井字棋  

1.6 本章小结  

1.7 强化学习的早期历史  

**第I部分 表格型求解方法**  

**第2章 多臂赌博机**  

2.1 一个 k 臂赌博机问题  

2.2 动作-价值方法  

2.3 10 臂测试平台  

2.4 增量式实现  

2.5 跟踪一个非平稳问题  

2.6 乐观初始值  

2.7 基于置信度上界的动作选择  

2.8 梯度赌博机算法  

2.9 关联搜索 (上下文相关的赌博机)  

2.10 本章小结  

**第3章 有限马尔可夫决策过程**  

3.1 “智能体-环境”交互接口  

3.2 目标和收益  

3.3 回报和分幕  

3.4 分幕式和持续性任务的统一表示法  

3.5 策略和价值函数  

3.6 *策略和*价值函数  

3.7 *性和近似算法  

3.8 本章小结  

**第4章 动态规划**  

4.1 策略评估 (预测)  

4.2 策略改进 

4.3 策略迭代  

4.4 价值迭代  

4.5 异步动态规划  

4.6 广义策略迭代  

4.7 动态规划的效率  

4.8 本章小结  

**第5章 蒙特卡洛方法**  

5.1 蒙特卡洛预测  

5.2 动作价值的蒙特卡洛估计  

5.3 蒙特卡洛控制  

5.4 没有试探性出发假设的蒙特卡洛控制  

5.5 基于重要度采样的离轨策略 

5.6 增量式实现 

5.7 离轨策略蒙特卡洛控制 

5.8 折扣敏感的重要度采样 

5.9 每次决策型重要度采样 

5.10 本章小结 

**第6章 时序差分学习** 

6.1 时序差分预测 

6.2 时序差分预测方法的优势 

6.3 TD(0) 的*性 

6.4 Sarsa：同轨策略下的时序差分控制 

6.5 Q 学习：离轨策略下的时序差分控制 

6.6 期望 Sarsa 

6.7 *化偏差与双学习 

6.8 游戏、后位状态和其他特殊例子 

6.9 本章小结 

**第7章 n 步自举法** 

7.1 n 步时序差分预测 

7.2 n 步 Sarsa 

7.3 n 步离轨策略学习 

7.4 ? 带控制变量的每次决策型方法 

7.5 不需要使用重要度采样的离轨策略学习方法：n 步树回溯算法 

7.6 ? 一个统一的算法：n 步 Q(σ) 

7.7 本章小结 

**第8章 基于表格型方法的规划和学习**

8.1 模型和规划 

8.2 Dyna：集成在一起的规划、动作和学习 

8.3 当模型错误的时候 

8.4 优先遍历 

8.5 期望更新与采样更新的对比 

8.6 轨迹采样 

8.7 实时动态规划 

8.8 决策时规划 

8.9 启发式搜索 

8.10 预演算法 

8.11 蒙特卡洛树搜索 

8.12 本章小结 

8.13 第I部分总结 

**第II部分 表格型近似求解方法** 

**第9章 基于函数逼近的同轨策略预测**

9.1 价值函数逼近 

9.2 预测目标 (VE ) 

9.3 随机梯度和半梯度方法 

9.4 线性方法 

9.5 线性方法的特征构造 

9.5.1 多项式基 

9.5.2 傅立叶基 

9.5.3 粗编码 

9.5.4 瓦片编码 

9.5.5 径向基函数 

9.6 手动选择步长参数 

9.7 非线性函数逼近：人工神经网络 

9.8 最小二乘时序差分 

9.9 基于记忆的函数逼近 

9.10 基于核函数的函数逼近 

9.11 深入了解同轨策略学习：“兴趣”与“强调” 

9.12 本章小结 

**第10章 基于函数逼近的同轨策略控制** 

10.1 分幕式半梯度控制 

10.2 半梯度 n 步 Sarsa 

10.3 平均收益：持续性任务中的新的问题设定 

10.4 弃用折扣 

10.5 差分半梯度 n 步 Sarsa 

10.6 本章小结 

**第11 章 基于函数逼近的离轨策略方法** 

11.1 半梯度方法 

11.2 离轨策略发散的例子 

11.3 致命三要素 

11.4 线性价值函数的几何性质 

11.5 对贝尔曼误差做梯度下降 

11.6 贝尔曼误差是不可学习的 

11.7 梯度 TD 方法 

11.8 强调 TD 方法 

11.9 减小方差 

11.10 本章小结 

**第12章 资格迹** 

12.1 λ-回报 

12.2 TD(λ) 

12.3 n-步截断 λ- 回报方法 

12.4 重做更新：在线 λ-回报算法 

12.5 真实的在线 TD(λ) 

12.6 蒙特卡洛学习中的荷兰迹 

12.7 Sarsa(λ) 

12.8 变量 λ 和 γ 

12.9 带有控制变量的离轨策略资格迹 

12.10 从 Watkins 的 Q(λ) 到树回溯 TB(λ) 

12.11 采用资格迹保障离轨策略方法的稳定性 

12.12 实现中的问题 

12.13 本章小结 

**第13章 策略梯度方法** 

13.1 策略近似及其优势 

13.2 策略梯度定理 

13.3 REINFORCE：蒙特卡洛策略梯度 

13.4 带有基线的 REINFORCE 

13.5 “行动器-评判器”方法 

13.6 持续性问题的策略梯度 

13.7 针对连续动作的策略参数化方法 

13.8 本章小结 

**第III部分 表格型深入研究** 

**第14章 心理学** 

14.1 预测与控制 

14.2 经典条件反射 

14.2.1 阻塞与高级条件反射 

14.2.2 Rescorla-Wagner 模型 

14.2.3 TD 模型 

14.2.4 TD 模型模拟 

14.3 工具性条件反射 

14.4 延迟强化 

14.5 认知图 

14.6 习惯行为与目标导向行为 

14.7 本章小结 

**第15章 神经科学** 

15.1 神经科学基础 

15.2 收益信号、强化信号、价值和预测误差 

15.3 收益预测误差假说 

15.4 多巴胺 

15.5 收益预测误差假说的实验支持 

15.6 TD 误差/多巴胺对应 

15.7 神经“行动器-评判器” 

15.8 行动器与评判器学习规则 

15.9 享乐主义神经元 

15.10 集体强化学习 

15.11 大脑中的基于模型的算法 

15.12 成瘾 

15.13 本章小结 

**第 16 章 应用及案例分析** 

16.1 TD-Gammon 

16.2 Samuel 的跳棋程序 

16.3 Watson 的每日双倍投注 

16.4 优化内存控制 

16.5 人类级别的视频游戏 

16.6 主宰围棋游戏 

16.6.1 AlphaGo 

16.6.2 AlphaGo Zero 

16.7 个性化网络服务 

16.8 热气流滑翔 

**第17章 前沿技术** 

17.1 广义价值函数和辅助任务 

17.2 基于选项理论的时序摘要 

17.3 观测量和状态 

17.4 设计收益信号 

17.5 遗留问题 

17.6 人工智能的未来


