# 李韶涵
Java 后端开发工程师｜22 岁｜期望城市：北京
📬 **联系方式**

| 项目 | 内容 |
| --- | --- |
| 📱 电话 | 13460772183 |
| 📧 邮箱 | 2990732278@qq.com |
| 💻 GitHub | [lsh‑src](https://github.com/lsh-src) |
| 🌐 作品集 | [https://shaohan.aijava.workers.dev/](https://shaohan.aijava.workers.dev/) |
| 📍 籍贯 | 河南开封 |

---

## 🎓 教育背景
**河北工程大学 · 软件工程 本科**｜2023.09 – 2027.07
- 🏆 国家励志奖学金（2024）
- 🥈 第十五届蓝桥杯全国软件大赛省级二等奖（2024）

---

## 🛠 专业技能
<details open>
<summary><b>☕ Java 基础 & JVM</b></summary>
熟练掌握集合框架及底层数据结构、并发编程（线程池、JUC、锁机制、AQS、ThreadLocal、虚拟线程）；深刻理解 JVM 内存模型、类加载机制、GC 算法（CMS/G1），具备 JVM 调优与内存泄漏排查经验
</details>

<details open>
<summary><b>🔧 框架 & 微服务</b></summary>
熟练使用 Spring Boot / Spring Cloud Alibaba，深刻理解 IoC、AOP、Bean 生命周期、循环依赖、自动配置原理；熟悉 Nacos、Gateway、Sentinel、Seata、OpenFeign 等微服务组件
</details>

<details open>
<summary><b>💾 存储 & 中间件</b></summary>
熟练掌握 MySQL 事务、索引、锁机制、MVCC、redo/undo/binlog；熟练使用 Redis 数据类型、持久化、哨兵、分布式锁、Lua 脚本、延迟队列；熟悉 RabbitMQ 可靠投递、手动 ACK、死信队列、幂等设计
</details>

<details open>
<summary><b>🔍 搜索引擎 & 向量检索</b></summary>
熟悉 Elasticsearch 倒排索引、分词、DSL 查询；掌握向量检索 + BM25 混合检索 + RRF 融合 + Reranker 精排的 RAG 架构；了解 Qdrant 向量数据库基本使用
</details>

<details open>
<summary><b>🤖 AI 应用开发</b></summary>
熟练使用 LangChain4j / Spring AI 构建 RAG 应用，掌握 Prompt 工程、上下文压缩、防幻觉溯源；了解 SSE 流式输出；善用 AI 编码工具辅助开发，可甄别修正生成代码逻辑缺陷
</details>

<details open>
<summary><b>⚙️ 工程化</b></summary>
熟练使用 Git、Docker、K8s 基础编排；熟悉单元/集成测试、接口压测、SQL 慢查分析
</details>

---

## 💼 项目经历
### 📚 CodeWisdom・智码开发者知识库 RAG 平台
**独立开发**｜2026.03 – 2026.05
> 🛠 技术栈：Spring Boot 3 / LangChain4j / MySQL / Elasticsearch / Redis / RabbitMQ / Redisson / Docker / 通义千问
> 🔗 GitHub：[https://github.com/lsh-src/code-wisdom](https://github.com/lsh-src/code-wisdom)
> 🌐 项目地址：[http://8.160.191.116/](http://8.160.191.116/)

面向开发者的垂直领域检索增强生成（RAG）平台，覆盖 Markdown/PDF 文档解析、混合检索、智能问答与知识溯源全链路，提升专业技术资料检索效率并降低模型幻觉。

- 🔎 **RAG 检索流水线**：基于 LangChain4j 构建文档解析、递归分块、Embedding 与问答全链路；采用 Elasticsearch BM25 + 向量 KNN 双路召回，通过 RRF 融合与 Reranker 对候选结果精排
- 📝 **Prompt 与上下文优化**：设计 System/User 分层提示词，强制模型基于检索证据回答并标注来源片段；利用 Redis 会话窗口控制上下文长度，缓存首轮问答以降低重复请求开销
- ⚡ **缓存与并发控制**：使用 Redis 缓存高频首轮问答，结合文档更新主动失效保证一致性；采用 Redisson 文档粒度分布式锁与完成态检查，按文档替换索引，避免并发解析与重复消费
- 📨 **异步解耦与可靠消费**：通过 RabbitMQ 异步处理文档解析、向量化与索引任务，接口快速返回 202 Accepted；结合手动 ACK、失败 NACK、死信队列与 Java 21 虚拟线程，提升任务可靠性与吞吐能力

---

### 🎓 EduWisdom・智学 AI 在线学习平台
**独立开发**｜2026.05 – 2026.07
> 🛠 技术栈：Spring Cloud Alibaba / Spring Boot / Gateway / Nacos / Sentinel / Seata / MyBatis‑Plus / MySQL / Redis / Redisson / RabbitMQ / Caffeine / LangChain4j / Qdrant / Vue 3 / Docker
> 🔗 GitHub：[https://github.com/lsh-src/edu-wisdom](https://github.com/lsh-src/edu-wisdom)

基于 Spring Cloud Alibaba 构建 B2C 在线教育微服务平台，覆盖课程、订单、学习等核心业务，集成 AI 知识库问答与高并发选课能力。

- 🤖 **AI 知识库问答**：基于 LangChain4j + Qdrant 实现 Markdown 文档上传、分段、向量化存储与相似度检索，支持知识库问答及流式对话；使用 Redis 持久化聊天记忆；基于 Redisson 延迟队列实现聊天记录异步落库，设计 3 次延迟重试与失败队列
- 🧩 **微服务治理**：使用 Nacos 管理服务注册发现与共享配置，Gateway 统一路由和认证入口，结合 OpenFeign Fallback 实现服务降级；接入 Sentinel 参数流控异常处理
- 🔐 **事务与消息解耦**：在订单状态流转、订单取消及优惠券核销等跨服务流程中使用 Seata @GlobalTransactional 保证数据一致性；通过 RabbitMQ 解耦订单、课程、学习、营销事件，配置消费者失败重试及 error exchange 兜底
- 🎯 **高并发营销场景**：使用 Redis Lua 脚本原子完成优惠券领取资格校验、用户限领和库存扣减，结合数据库条件更新避免优惠券超发；在 API 层使用 Caffeine 缓存角色和课程分类数据

---

## ✨ 核心优势
- 💪 扎实的 Java 后端与微服务工程基础，独立完成多个高复杂度项目（RAG 平台、在线教育微服务平台）
- 🤖 拥有完整 AI 应用落地实战经验，熟练基于 LangChain4j 完成混合检索、Prompt 工程、上下文压缩、防幻觉溯源整套 RAG 链路开发
- 🛠 具备 JVM 调优、多级缓存、分布式锁、消息队列实战经验，定位解决过 ThreadLocal 内存泄漏、高并发优惠券超卖等线上类问题
- 🚀 学习能力强，擅长结合大模型辅助开发，同时能够甄别、修正 AI 生成代码缺陷，具备良好问题排查与工程落地意识
