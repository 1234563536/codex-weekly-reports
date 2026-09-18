# 2026-09-14 至 2026-09-18 成果索引

> 公开脱敏版。本索引使用逻辑路径，不包含本机绝对路径。

| 类别 | 成果 | 规模 | 状态 | 逻辑位置 |
|---|---|---:|---|---|
| 研究方案 | 世界模型、OPD、Token Credit 演示稿 | 74 页 | 已完成 | `<RESEARCH_OUTPUT>/research_routes_2026-09-14.pptx` |
| 研究方案 | 演示稿 PDF | 74 页 | 已完成 | `<RESEARCH_OUTPUT>/research_routes_2026-09-14.pdf` |
| 数据集方案 | BranchCUA 技术演示稿 | 28 页 | 已完成 | `<RESEARCH_OUTPUT>/branchcua_counterfactual_recovery_2026-09-14.pptx` |
| 运行监控 | GPU/worker 定时监控 | 约 2.9k 行代码及测试 | 已部署 | `<MONITOR_SOURCE>/vllm_gpu_watch/` |
| 文献调研 | 大模型隐空间综述 | 24 页 | 已完成首版 | `<LATENT_RESEARCH>/latent_space_review_2025_2026.pdf` |
| 文献调研 | 论文索引 | 81 条记录 | 已完成首版 | `<LATENT_RESEARCH>/paper_index.csv` |
| 实验 | Coconut 本地工作流 | 3 类模型配置 | 部分完成 | `<EXPERIMENT_ROOT>/coconut/` |
| 实验 | GPT-2 阶段检查点 | 6 个 | 阶段性完成 | `<EXPERIMENT_ROOT>/coconut/local/runs/…` |
| 评测 | QA 评测器 | 约 6.3k 行源码及测试 | 工具完成 | `<QA_EVALUATOR>/` |
| 评测 | 七数据集 full run | 51,713 个计划样本 | 运行中 | `<QA_RUN>/` |
| 检索 | 检索配置审计 | 10.9M passages | 已完成 | `<RETRIEVAL_AUDIT>/retrieval_setup_audit.md` |
| 指标 | 5 组实验 × 6 数据集汇总 | 30 行 | 已完成 | `<METRICS_OUTPUT>/summary.csv` |

## 逻辑路径说明

- `<RESEARCH_OUTPUT>`：研究演示稿与导出文档目录。
- `<DESIGN_DOCS>`：设计说明和实施计划目录。
- `<MONITOR_SOURCE>`：GPU/服务监控源码工作区。
- `<LATENT_RESEARCH>`：隐空间论文索引、综述和研究地图目录。
- `<ENV_ROOT>`：公共实验环境目录。
- `<EXPERIMENT_ROOT>`：本地实验项目根目录。
- `<QA_EVALUATOR>`：重构后的 QA 评测器源码目录。
- `<QA_RUN>`：全量评测运行目录。
- `<RETRIEVAL_AUDIT>`：检索系统审计结果目录。
- `<METRICS_OUTPUT>`：历史评测指标汇总目录。

真实绝对路径仅保存在本地私有附录中。如果仓库保持公开，该映射不会上传。

## 不纳入公开仓库的内容

- 账号密码、应用密码、API Token 和任何凭据字段；
- 模型服务或检索服务的地址和端口；
- 邮件地址、机器账号和完整目录结构；
- 模型权重、训练检查点、缓存与运行日志；
- 原始聊天记录和样本级模型输出；
- 包含第三方版权内容的论文 PDF；
- 未清理元数据或外部关系的办公文档原件。
