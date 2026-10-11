# HMM Regime Strategies

个人量化研究：HMM 市场状态识别、Variational Bayesian HMM 沪深300择时，以及基于状态的多资产配置。

| Notebook | 内容 |
| --- | --- |
| `notebooks/huaxi_hmm.ipynb` | 华西证券 HMM 择时与配置研报复现 |
| `notebooks/sp500_hmm.ipynb` | S&P 500 版本的 HMM 择时实验 |
| `notebooks/vb_hmm_csi300.ipynb` | VB-HMM 沪深300择时与参数验证 |
| `notebooks/hmm_multi_asset_mvo.ipynb` | HMM 状态与多资产均值方差配置 |
| `notebooks/guangfa_hmm.ipynb` | 广发证券周频 HMM 择时研报复现 |

`references/` 包含上述华西和广发研报。`results/` 保存本地已有的图表与汇总，Notebook 中原有输出也予以保留。复现代码与原研报之间的实现差异、数据区间和实验参数以对应 Notebook 为准，不把所有 Notebook 描述为已经在当前环境重跑验证。

安装 `requirements.txt` 后打开 Notebook。代码使用 AkShare、yfinance 等数据源；使用前检查对应数据获取单元和本地路径。SP500 Notebook 没有保存执行输出，其余 Notebook 保留已有结果。

这些内容用于展示研究过程与实现，不构成对未来表现的保证。方法、数据来源和研报作者应按各 Notebook 与参考材料注明。
