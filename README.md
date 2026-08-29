李韶涵
Java 后端开发工程师 · 22岁 · 期望城市：北京

📱 电话        📧 邮箱              💻 GitHub  🌐 作品集                 📍 籍贯  
13460772183  2990732278@qq.com  lsh-src    shaohan-lab.pages.dev  河南开封   
<details open>
<summary><b>Java & JVM</b></summary>

集合、并发编程（JUC、线程池、锁、AQS）、JVM 内存模型、GC 算法（CMS/G1）、调优排查

</details>

<details open>
<summary><b>框架 & 微服务</b></summary>

Spring Boot / Spring Cloud Alibaba、IoC / AOP、Nacos / Gateway / Sentinel / Seata

</details>

<details open>
<summary><b>存储 & 中间件</b></summary>

MySQL（事务、索引、MVCC、日志）、Redis（缓存、分布式锁）、RabbitMQ（可靠投递、死信队列、幂等）

</details>

<details open>
<summary><b>搜索 & 向量检索</b></summary>

Elasticsearch 倒排索引、分词、DSL；BM25 + 向量混合检索 + Reranker 精排的 RAG 架构

</details>

<details open>
<summary><b>AI 应用开发</b></summary>

LangChain4j / Spring AI 构建 RAG 应用，Prompt 工程、上下文压缩、防幻觉溯源

</details>

<details open>
<summary><b>工程化</b></summary>

Git、Docker、K8s 基础编排；接口压测、SQL 慢查分析

</details>

💼 项目经历
CodeWisdom · 智码开发者知识库 RAG 平台
独立开发 | 2025.03 – 2026.05

技术栈：Spring Boot / LangChain4j / MySQL / Elasticsearch / Redis / RabbitMQ / Docker / 通义千问

🔗 GitHub：https://github.com/lsh-src/code-wisdom

面向开发者的垂直领域 RAG 系统，解决大模型专业知识幻觉、资料查找效率低问题。

基于 LangChain4j 构建 RAG 流水线：语义分块 + 重叠分块、BGE-M3 向量化、ES 混合检索（BM25 + 向量）、Reranker 精排，自建测试集召回率 87%，单轮问答 < 300ms
分层 Prompt + 强制溯源、会话上下文压缩（Token 消耗降低 30%）
Redis 缓存高频问答与热点向量；Redisson 分布式锁；RabbitMQ 异步解耦；JVM 调优提升批量向量化吞吐量 40%
EduWisdom · 智学 AI 在线学习平台
独立开发 | 2026.05 – 2026.07

技术栈：Spring Cloud Alibaba / Spring Boot / MyBatis-Plus / MySQL / Redis / RabbitMQ / Seata / Docker

🔗 GitHub：https://github.com/lsh-src/edu-wisdom

基于 Spring Cloud Alibaba 的 B2C 在线教育微服务平台，覆盖课程、订单、学习核心业务，落地 AI 答疑与个性化学习。

Nacos 服务注册与配置、Gateway 统一鉴权、Sentinel 限流熔断，保障高并发选课链路
Seata AT 模式保证跨服务一致性；Redisson 分布式锁解决超卖；Caffeine + Redis 多级缓存提速 60%
对接大模型实现 AI 智能助教；RabbitMQ 异步解耦；GC 日志定位 ThreadLocal 内存泄漏，Full GC 频率下降 60%
东软颐养中心
独立开发 | 2026.05 – 2026.07

技术栈：Spring Boot 3 / Spring Cloud Gateway / Nacos / RabbitMQ / Vue 3 / Element Plus / MySQL / Redis / 阿里云 OSS / AI（RAG）

🔗 GitHub：https://github.com/lsh-src/neusoft-elderly-care-system

养老机构日常运营管理平台，覆盖客户、床位、入住、膳食、护理、数据统计及 AI 服务。

后端：Spring Boot 3 微服务架构，认证、客户、床位、入住、膳食、护理等核心模块
前端：Vue 3 + Element Plus 管理系统，通用增删改查、膳食日历、数据仪表盘
AI 模块：AI 对话、RAG 专业问答、健康评估、护理方案推荐、知识库管理
基础设施：网关 JWT 认证、Nacos 注册发现、RabbitMQ 事件驱动异步 AI 分析、OSS 文件上传
工程易淘 — 校园二手交易平台
独立开发 | 2025.10 – 2026.02

技术栈：Spring Boot / MyBatis / MySQL / Redis / RabbitMQ / Elasticsearch / Spring Security / WebSocket

🔗 GitHub：https://github.com/lsh-src/engitao

校园 C2C 二手交易平台，商品发布、智能搜索、即时通讯、订单交易全流程。

Elasticsearch + IK/Pinyin 插件中文分词与拼音匹配，搜索响应 20–50ms；ES + MySQL 双层降级
Redis 缓存搜索热词、用户会话；分布式锁控制库存扣减；异步批量聚合浏览量落库
RabbitMQ 异步解耦 AI 商品生成；JWT 鉴权 + WebSocket 即时通讯
🎓 教育背景
河北工程大学 · 软件工程 本科 | 2023.09 – 2027.06

🏆 国家励志奖学金（2024）
🥈 第十五届蓝桥杯全国软件大赛省级二等奖（2024）
