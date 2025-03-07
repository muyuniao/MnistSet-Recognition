# MNIST 手写数字识别项目

![PyTorch](https://img.shields.io/badge/PyTorch-1.13.1-red)
![Python](https://img.shields.io/badge/Python-3.12.7-blue)

一个基于 PyTorch 实现的简单全连接神经网络，用于 MNIST 手写数字识别任务。

## 项目特点
- 使用经典的 MNIST 数据集（28x28 像素灰度图像）
- 实现简单的全连接神经网络（输入层 → 隐藏层 → 输出层）
- 提供完整的训练循环和准确率评估
- 达到 **93.76%** 测试准确率（10 epoch）

## 快速开始

### 环境要求
- Python ≥ 3.8
- PyTorch ≥ 1.13
- torchvision ≥ 0.14

```bash
# 安装依赖
pip install torch torchvision numpy
```

# 运行项目

```python
# 直接运行 Jupyter Notebook: MNIST-Recognition.ipynb
# 或执行以下命令训练模型
python main.py  # 需将 notebook 转换为 .py 文件
```

