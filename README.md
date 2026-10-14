# 王小畅｜Agent 开发 & AI 全栈作品集

> **HR 看这里 👋** 想快速了解我？下面两项作品包含项目用途、我的贡献，以及可以直接查看的演示和源码。

**上海大学 · 人工智能硕士在读 · 2028 届 · 上海**  
求职方向：**Agent 开发 / AI 全栈实习** ｜ 每周可线下 **4 天** ｜ 可连续实习 **6 个月**

我关注如何把 LLM、检索和工具调用连接成可靠的业务流程，具备 Python / Java 后端实践与企业实习经历。研究方向为 **LLM、PDE 求解、深度展开网络**。

## 两个核心项目

| 项目 | 做什么 | 我的角色 | 快速查看 |
| --- | --- | --- | --- |
| **YF-Agent · 酒店预订智能客服** | 在闲鱼店铺提供酒店咨询、条件修改、推荐与预订引导 | 独立开发酒店预订业务场景 | [源码](https://github.com/spark216/YF-agent) · [演示](https://github.com/spark216/YF-agent/blob/main/docs/DEMO.md) |
| **ScholarAgent · 学研智搜** | 将科研问题转化为多源论文检索、排序与证据整理 | 三人团队核心开发，负责 Agent 编排与检索调度 | [源码](https://github.com/spark216/scholar-agent) · [演示](https://github.com/spark216/scholar-agent/blob/main/docs/DEMO.md) |

### YF-Agent｜让客服记住需求，也能处理需求变化

- **业务流程：** LangGraph 编排需求收集、槽位补全、酒店检索、条件协商与人工确认；覆盖约 **1 万家酒店目录**。
- **我的重点：** 分离近期对话、结构化槽位与任务状态；条件变化后使旧候选失效，结合会话级并发控制、消息去重与持久化检查点处理任务恢复。
- **工程交付：** FastAPI 工作台、条件卡片、执行轨迹与自动化验证。公开仓库提供 **60 条合成业务轨迹**及 CI 记录，便于查看业务与恢复边界。

`Python` · `LangGraph` · `FastAPI` · `Redis / SQLite` · `BGE-M3 / FAISS` · `WebSocket / SSE`

[项目贡献与技术入口](projects/hotel-agent.md) · [架构设计](https://github.com/spark216/YF-agent/blob/main/docs/ARCHITECTURE.md) · [测试说明](https://github.com/spark216/YF-agent/blob/main/docs/TESTING.md)

### ScholarAgent｜把复杂科研需求变成可追踪的检索过程

- **业务流程：** 理解研究需求，联合学术 API、词法检索与语义检索，输出论文列表及可回查的研究证据。
- **我的重点：** 基于 LangGraph 管理候选集、覆盖缺口、检索轮次与 API 预算；处理查询演化、多源去重、异常降级及离线复测。
- **团队交付：** Vue 3 + FastAPI 交互系统，包含论文卡片、检索轨迹和证据矩阵；仓库附真实运行截图与检索消融报告。

`Python` · `LangGraph` · `FastAPI / Vue 3` · `BGE-M3 / FAISS / FTS5` · `RRF / Cross-Encoder`

[项目贡献与技术入口](projects/scholar-agent.md) · [检索消融报告](https://github.com/spark216/scholar-agent/blob/main/docs/ABLATION_REPORT.md)

<details>
<summary><strong>📷 点开看运行效果：酒店客服工作台与学术检索界面</strong></summary>

**酒店客服工作台** — 对话、条件卡片、候选酒店与执行轨迹。

![酒店预订客服工作台](assets/hotel-workbench.png)

截图来自实际运行的离线演示，使用样例房态、哈希编码器与模拟 Redis；BGE-M3 和真实服务接入见项目文档。

**ScholarAgent 学研智搜** — 科研需求输入、论文列表与证据比较。

![学研智搜查询入口](assets/scholar-home.jpg)

![论文结果与关系图](assets/scholar-papers.jpg)

截图来自项目记录的本地真实检索，运行条件与输出见演示文档。

</details>

## 教育与工程经历

- **上海大学｜人工智能硕士在读**，2025.09—2028.06；研究生二等奖学金、中国研究生数学建模竞赛国家级二等奖。
- **浙江工业大学｜软件工程学士**，2021.09—2025.06；GPA 3.68/4.00，专业前 10%，CET-6。
- **杭州精伦网络科技有限公司｜Java 开发实习生**，2023.06—2023.10；参与业务接口、数据聚合、MySQL 查询优化与异常排查。

## 其他项目与学习

- [水稻病害识别系统](https://github.com/spark216/Rice-Disease-Recognition-System)：早期深度学习项目，探索数据增强、注意力机制与轻量化识别。
- [self-llm](https://github.com/spark216/self-llm)：开源学习与复现入口，区别于个人独立开发项目。

如果项目与岗位匹配，欢迎通过招聘平台与我交流。谢谢你看到这里！
