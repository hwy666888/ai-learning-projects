# AI Learning Projects

> AI、LLM、Agent、RAG、计算机视觉与 MLOps 学习项目收藏及路线  
> 整理日期：2026-08-13

这个仓库用于集中管理值得长期学习的开源项目，并记录学习进度。8 个主项目已经加星并 Fork 到个人账号；Datawhale 的 `deepagents-in-action` 已加星并作为专项进阶课程收录；其余候选项目按需学习。

## 推荐学习顺序

1. **Agent 基础**：先读 Agent Learning，建立工具、记忆、规划、RAG 和安全等完整概念。
2. **完整应用实战**：学习 LLM Zoomcamp，把当前的“AI 文章趋势分析”扩展成可检索、可问答、可评测的研究助手。
3. **Agent 框架实践**：完成 Hugging Face Agents Course，熟悉 smolagents、LangGraph 和 LlamaIndex。
4. **Agent 工程进阶**：学习 Datawhale Deep Agents 实战，重点掌握 Harness、虚拟文件系统、任务规划、子 Agent、Skills、权限、沙箱和 MCP。
5. **生产级 RAG**：实践 Production Agentic RAG，补齐数据管道、搜索、缓存、监控和部署。
6. **底层与工程化**：并行学习 LLMs From Scratch、Stanford CS336 和 MLOps Zoomcamp。
7. **视觉方向**：使用 Ultralytics 继续改进校园打架检测项目。

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
| Agent 工程专项 | [datawhalechina/deepagents-in-action](https://github.com/datawhalechina/deepagents-in-action) | 暂不 Fork，优先跟随官方更新 | Harness、上下文工程、子 Agent、Skills、权限、沙箱、MCP | ★★★★ |


## Datawhale 精选路线

同类课程不要全部从头学。根据目标选择一条主线，再把其他项目当作补充资料。

| 优先级 | 项目 | 最适合学习 | 建议 |
|---|---|---|---|
| 当前优先 | [Deep Agents 实战](https://github.com/datawhalechina/deepagents-in-action) | 生产级 Agent Harness、任务规划、子 Agent、Skills、沙箱、权限、MCP | 重点完成第 1～9、12 章，并改造“AI 文章趋势分析”项目 |
| Agent 系统基础 | [Hello-Agents](https://github.com/datawhalechina/hello-agents) | ReAct、Reflection、自研 Agent 框架、记忆、协议、评估、多智能体 | 比 Deep Agents 更全面，适合查漏补缺，不必与已有 Agent 课程重复通读 |
| LLM 底层 | [Happy-LLM](https://github.com/datawhalechina/happy-llm) | Transformer、LLaMA、预训练、微调、Agentic RL | 中文底层主线首选；已有个人 Fork |
| RAG 应用 | [LLM Universe](https://github.com/datawhalechina/llm-universe) | 个人知识库、RAG 应用开发和评估 | 最贴近“AI 文章趋势分析”，可与 LLM Zoomcamp 二选一作主线 |
| 检索专项 | [Easy-vecDB](https://github.com/datawhalechina/easy-vecdb) | FAISS、Milvus、ANN、混合检索、向量数据库实现 | 当项目进入检索优化阶段再学 |
| 模型部署与微调 | [Self-LLM](https://github.com/datawhalechina/self-llm) | 50+ 开源模型的部署、使用和 LoRA 微调 | 需要本地模型或私有模型时查阅，不适合现在通读 |
| 前沿选修 | [Learn World Models](https://github.com/datawhalechina/learn-world-model) | VAE、RSSM、Dreamer、规划与评测 | 仍是 Alpha Preview，保持关注，暂不作为当前主线 |
| 路线导航 | [Datawhale AI Learning Roadmap](https://github.com/datawhalechina/datawhale-ai-learning-roadmap) | 根据目标选择课程并记录进度 | 用作导航，不替代具体课程 |

### Deep Agents 实战建议

- **先学**：第 1～5 章，理解 Harness、虚拟文件系统、规划和上下文隔离。
- **再学**：第 7～9 章，掌握 Skills、长期记忆和 Human-in-the-Loop。
- **项目需要时学**：第 10～12 章，补充沙箱、文件权限和 MCP。
- **验收成果**：为“AI 文章趋势分析”实现一个研究 Agent，能够规划任务、调用检索工具、委派子任务、保留长期记忆，并在外部写入前请求人工确认。


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
