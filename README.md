# wuziqi2020
五子棋AI

本项目专门用于UESTC2020-C语言A班各位大神提交作业！

## 核心目标
利用所学C语言技能，实现五子棋AI算法，并用自学的Visual Basic .NET 制作交互式图形界面调用C语言编译的dll，实现VB与C的通信

## 项目说明

这个项目说明用于指引后续的工作进程

- 确定要添加的功能

  - 极大极小值搜索 + alpha-beta剪枝 构造的博弈树
  - 贪心评估算法缩减结点
  - 启发式算法优化 alpha-beta剪枝
  - 在GUI里添加 AI对战
  - 迭代加深搜索 避免 “调戏玩家”
  
- 可能添加的功能
  
  - Zobrist 实现缓存 以优化性能
  - 训练 BP 神经网络以替代贪心算法做评估函数
  - 黑棋的“禁手”规则
  - 基于活三与冲四的“算杀”
  
- 如果还有余力（基本8可能）
  - 将 visual basic GUI的 winform 方案 替换为 WPF方案
  - 另外实现基于 遗传算法 的五子棋AI

## 参考

- [本项目的wiki，包括我转载的俸爷转载的五子棋教程（逃](https://github.com/SMagic-L/wuziqi2020/wiki)

