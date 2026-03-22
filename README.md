# 📈 AI Chart Generator — 根据数据自动生成可视化图表

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## ✨ 功能

- 自动分析数据质量
- 统计分布检测
- 异常值识别
- 报告生成

## 🚀 快速开始

```bash
pip install -e .
python -m ai-chart-generator.cli
```

## 📖 使用

```python
from ai-chart-generator import DataAnalyzer

analyzer = DataAnalyzer()
result = analyzer.analyze("data.csv")
print(result)
```
