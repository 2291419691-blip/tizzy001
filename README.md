# Python《第一次数据探索》课后作业

大学应用统计学课程作业，按 A、B、C、D 四部分完成。

## 下载

点击以下链接后，在 GitHub 文件页面点击 **Download raw file（下载原始文件）**。

- [完整 Jupyter Notebook](assignment/data_exploration.ipynb)
- [Word 作业报告](assignment/data_exploration_report.docx)
- [完整提交包（含数据、字体、图表和运行说明）](assignment/data_exploration_bundle.zip)

推荐下载完整提交包，解压后阅读 `README_使用说明.txt`。Notebook 已包含运行输出；重新执行时保持 `data` 文件夹与 Notebook 同级。

## 已验证内容

- 16 个代码单元实际运行成功，9 张图均已生成并检查。
- A：300 个正态样本加 5 个人工异常值；N(100,15) 的第二个参数采用标准差。IQR 检出全部 5 个人工异常，同时标记 4 个正态尾部观测。
- B：真实 Palmer Penguins 数据，包含缺失处理、IQR 检测、描述统计、相关热力图、帕累托图和约 200 字结论。
- C：Kaggle Titanic `train.csv` 的公开教学镜像，仅做 EDA，包含生存率、缺失模式、票价箱线图和分析报告。
- D：9 种潜在电商数据质量问题与处理方案。

数据来源、分析口径和依赖版本均记录在附件中；统计结果来自实际运行。提交前请填写姓名、学号、班级。
