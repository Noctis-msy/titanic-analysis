# 泰坦尼克号生存预测分析

> 基于泰坦尼克号乘客数据，探索影响乘客生存的关键因素，并构建生存预测模型。

## 项目简介

TODO：一句话说明项目做了什么。

## 数据来源

- 泰坦尼克号乘客数据：`data/train.csv`（训练集 712 条）、`data/test.csv`（测试集 179 条）
- 字段：`PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked`

## 项目结构

```
titanic-analysis/
├── data/            # 原始数据
├── notebooks/       # 探索性分析 notebook
├── src/             # 正式代码
│   ├── clean.py     # 数据清洗
│   ├── features.py  # 特征工程
│   ├── model.py     # 建模预测
│   └── visualize.py # 可视化
├── reports/         # 报告与图表输出
├── app/             # Streamlit 看板
├── README.md
└── requirements.txt
```

## 使用方法

1. 安装依赖：`pip install -r requirements.txt`
2. 数据清洗：`python src/clean.py`
3. 训练模型：`python src/model.py`
4. 启动看板：`streamlit run app/app.py`

## 分析结论

TODO：哪些因素影响生存。

## 模型效果

TODO：模型准确率。

## 可视化看板

TODO：看板链接与截图。
