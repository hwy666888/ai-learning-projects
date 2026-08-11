# AI Learning Projects

> AI、LLM、Agent、RAG、计算机视觉与 MLOps 学习项目收藏及路线  
> 整理日期：2026-08-11

这个仓库用于集中管理值得长期学习的开源项目，并记录学习进度。8 个主项目已经加星并 Fork 到个人账号；2 个备选项目暂作参考。

## 推荐学习顺序

1. **Agent 基础**：先读 Agent Learning，建立工具、记忆、规划、RAG 和安全等完整概念。
2. **完整应用实战**：学习 LLM Zoomcamp，把当前的“AI 文章趋势分析”扩展成可检索、可问答、可评测的研究助手。
3. **Agent 框架实践**：完成 Hugging Face Agents Course，熟悉 smolagents、LangGraph 和 LlamaIndex。
4. **生产级 RAG**：实践 Production Agentic RAG，补齐数据管道、搜索、缓存、监控和部署。
5. **底层与工程化**：并行学习 LLMs From Scratch、Stanford CS336 和 MLOps Zoomcamp。
6. **视觉方向**：使用 Ultralytics 继续改进校园打架检测项目。

## 主推荐项目

| 路线 | 原始项目 | 我的 Fork | 学习重点 | 难度 |
|---|---|---|---|---|
| LLM 应用 | [DataTalksClub/llm-zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) | [hwy666888/llm-zoomcamp](https://github.com/hwy666888/llm-zoomcamp) | RAG、Agent、向量检索、评测、监控 | ★★★ |
| Agent 系统 | [Haozhe-Xing/agent_learning](https://github.com/Haozhe-Xing/agent_learning) | [hwy666888/agent_learning](https://github.com/hwy666888/agent_learning) | 工具、记忆、规划、MCP、多智能体、安全 | ★★★ |
| LLM 原理 | [rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch) | [hwy666888/LLMs-from-scratch](https://github.com/hwy666888/LLMs-from-scratch) | Tokenizer、Attention、GPT、预训练、微调 | ★★★★ |
| Agent 框架 | [huggingface/agents-course](https://github.com/huggingface/agents-course) | [hwy666888/agents-course](https://github.com/hwy666888/agents-course) | smolagents、LangGraph、LlamaIndex、Agentic RAG | ★★★ |
| 高阶课程 | [stanford-cs336/stanford-cs336.github.io](https://github.com/stanford-cs336/stanford-cs336.github.io) | [hwy666888/stanford-cs336.github.io](https://github.com/hwy666888/stanford-cs336.github.io) | 现代语言模型训练、优化、缩放与对齐 | ★★★★★ |
| 生产级 RAG | [jamwithai/production-agentic-rag-course](https://github.com/jamwithai/production-agentic-rag-course) | [hwy666888/production-agentic-rag-course](https://github.com/hwy666888/production-agentic-rag-course) | FastAPI、OpenSearch、Airflow、Redis、Langfuse、LangGraph | ★★★★ |
| 计算机视觉 | [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) | [hwy666888/ultralytics](https://github.com/hwy666888/ultralytics) | YOLO 检测、分割、姿态估计与模型部署 | ★★★ |
| MLOps | [DataTalksClub/mlops-zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) | [hwy666888/mlops-zoomcamp](https://github.com/hwy666888/mlops-zoomcamp) | MLflow、流水线、部署、监控、CI/CD | ★★★★ |

## 备选参考

| 项目 | 适合场景 | 备注 |
|---|---|---|
| [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) | 需要中文材料和入门级 Agent 示例 | 部分练习依赖 Microsoft Foundry/Azure |
| [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | 需要覆盖面很广的 AI 工程参考手册 | 内容量很大，适合长期查阅 |

## 建议的第一个实践项目

围绕现有“AI 文章趋势分析”项目，逐步完成：

- [ ] 抓取并清洗 AI 文章
- [ ] 建立关键词与向量混合检索
- [ ] 增加文章问答和来源引用
- [ ] 增加热点趋势总结 Agent
- [ ] 建立固定评测数据集
- [ ] 记录回答质量、延迟和成本
- [ ] 部署一个可以演示的 Web 界面

## 学习进度

- [ ] 选定第一个项目
- [ ] 完成本地环境配置
- [ ] 跑通官方最小示例
- [ ] 完成一个章节练习
- [ ] 整理中文学习笔记
- [ ] 基于所学改进自己的项目
- [ ] 提交一次开源 Issue 或 Pull Request

## 使用说明

- **Star** 用于长期收藏原项目。
- **Fork** 用于保存自己的学习修改和笔记。
- Fork 不会自动同步上游更新；学习前可在 GitHub 页面使用 **Sync fork**。
- 不建议一次把所有项目都克隆到电脑，按学习顺序逐个下载即可。
