# Fraud Detection Paper Reproduction

本仓库用于整理与复现「欺诈检测 / 反欺诈」相关论文中的方法与实验。**后续会持续加入更多论文的实现与笔记**，可按论文或年份分文件、分目录维护。

---

## 当前内容

| 类型 | 说明 |
|------|------|
| `One-Class SVM.ipynb` | 单类 SVM 相关实验（如就医行为异常挖掘等场景） |
| `LDA+DNN.ipynb` | LDA + DNN 等组合方法相关实验 |
| 文献阅读笔记（`.docx`） | 与上述主题对应的阅读与梳理（含日期后缀便于区分版本） |

> 生成的中间结果例如 `svm_visit_anomaly_result.csv` 已列入 `.gitignore`，不会入库；复现时请在本机运行 notebook 后自行生成。

---

## 环境与运行

1. 建议使用 Python 3.x，并按各 notebook 中的 `import` 安装依赖（如 `pandas`、`scikit-learn` 等）。
2. 在项目根目录启动 Jupyter：
   ```bash
   jupyter lab
   ```
   或直接在本仓库用 VS Code / Cursor 打开 `.ipynb` 运行。

数据路径、随机种子等若与原作者设定不同，请以各 notebook 内说明为准。

---

## 后续如何扩展仓库

可按论文拆分子目录，便于浏览与协作，例如：

```text
fraud-detection-paper-reproduction/
├── README.md
├── README-2012-one-class-svm.md   # 可选：某篇论文的专项说明
├── 2012-one-class-svm/
│   └── ...
└── 2017-lda-dnn/
    └── ...
```

新建论文复现时，建议在同一处保留：**可运行的代码（notebook 或脚本）**、**数据说明或获取方式**、**与论文/table 对齐的简要结果说明**。具体目录命名可按你的习惯统一即可。

---

## 仓库地址

https://github.com/hhsjonor99-code/fraud-detection-paper-reproduction
