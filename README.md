# CMJ - Zero to Hero

基于 [Andrej Karpathy 的 Neural Networks: Zero to Hero](https://github.com/karpathy/nn-zero-to-hero) 系列课程的学习笔记与代码实现。

## 课程内容

课程从零开始构建神经网络，不依赖高级框架，逐步理解反向传播、语言模型等核心概念。

| 课程 | 对应文件 | 内容 |
|------|---------|------|
| Micrograd | `micograd/micograd-1.ipynb` `micograd/micograd-2.ipynb` | 从零构建自动微分引擎，实现反向传播 |
| Makemore Part 1 | `makemore/makemore_part1_bigrams.ipynb` | 基于 bigram 的字符级语言模型 |
| Makemore Part 2 | `makemore/makemore_part2_mlp.ipynb` | 使用 MLP 改进语言模型 |
| Makemore Part 3 | `makemore/makemore_part3_bn.ipynb` | 批归一化与超参数调优 |
| Makemore Part 4 | `makemore/makemore-becoming a backprop ninja.ipynb` | 手动反向传播深度剖析 |
| Makemore Part 5 | `makemore/makemore-5-构建 WaveNet.ipynb` | 构建 WaveNet 架构 |
| PyTorch 练习 | `pytorch-practice.ipynb` | PyTorch 基础操作练习 |

## 项目结构

```
CMJ---zero-to-hero/
├── pytorch-practice.ipynb         # PyTorch 基础练习
├── micograd/
│   ├── micograd-1.ipynb           # 自动微分引擎（上）
│   └── micograd-2.ipynb           # 自动微分引擎（下）
└── makemore/
    ├── names.txt                  # 人名数据集
    ├── makemore_part1_bigrams.ipynb
    ├── makemore_part2_mlp.ipynb
    ├── makemore_part3_bn.ipynb
    ├── makemore-becoming a backprop ninja.ipynb
    └── makemore-5-构建 WaveNet.ipynb
```

## 环境要求

```bash
pip install torch numpy matplotlib
```

所有 notebook 可直接在 Jupyter / VS Code 中运行。

## 参考资源

- [Neural Networks: Zero to Hero 播放列表](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
- [Karpathy/nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero)
- [Micrograd 原仓库](https://github.com/karpathy/micrograd)
- [Makemore 原仓库](https://github.com/karpathy/makemore)
