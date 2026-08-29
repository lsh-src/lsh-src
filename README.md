李韶涵 | Java 后端开发工程师
求职意向：Java 后端开发工程师 | 期望城市：北京 | 22岁

📬 联系方式
📱 电话：13460772183

📧 邮箱：2990732278@qq.com

💻 GitHub：https://github.com/lsh-src

🌐 作品集：https://shaohan-lab.pages.dev

📍 籍贯：河南开封

🛠 专业技能
Java & JVM：熟练掌握集合、并发编程（JUC、线程池、锁、AQS）；熟悉 JVM 内存模型、GC 算法（CMS/G1），具备调优与内存泄漏排查经验

框架 & 微服务：熟练使用 Spring Boot / Spring Cloud Alibaba，理解 IoC、AOP、Bean 生命周期、自动配置；熟悉 Nacos、Gateway、Sentinel、Seata

存储 & 中间件：熟悉 MySQL 事务、索引、MVCC、日志；熟练使用 Redis 缓存、分布式锁；熟悉 RabbitMQ 可靠投递、死信队列、幂等设计

搜索 & 向量检索：熟悉 Elasticsearch 倒排索引、分词、DSL；掌握 BM25 + 向量混合检索 + Reranker 的 RAG 架构

AI 应用开发：熟练使用 LangChain4j / Spring AI 构建 RAG 应用，掌握 Prompt 工程、上下文压缩、防幻觉

工程化：熟练 Git、Docker、K8s 基础编排；熟悉接口压测、SQL 慢查分析

💼 项目经历
CodeWisdom・智码开发者知识库 RAG 平台
独立开发 | 2025.03 - 2026.05
技术栈：Spring Boot / LangChain4j / MySQL / Elasticsearch / Redis / RabbitMQ / Docker / 通义千问
GitHub：https://github.com/lsh-src/code-wisdom

面向开发者的垂直领域 RAG 系统，覆盖文档解析、语义检索、智能问答、知识溯源全链路，解决大模型幻觉与资料查找效率低问题

基于 LangChain4j 构建 RAG 流水线，采用语义分块 + 重叠分块，结合 BGE-M3 向量化与 ES 混合检索（BM25+向量），引入 Reranker 精排，自建测试集召回率 87%，单轮问答 <300ms

设计分层 Prompt + 强制溯源，要求模型标注原文出处；实现会话上下文压缩，Token 消耗降低 30%，支持 10+ 轮追问

使用 Redis 缓存高频问答及热点向量，热门查询响应降至 50ms；Redisson 分布式锁控制文档并发，异步批量聚合日志落库

通过 RabbitMQ 异步解耦文档解析、向量化等耗时任务，手动 ACK + 幂等校验；结合 JVM 调优批量向量化吞吐量提升 40%

EduWisdom・智学 AI 在线学习平台
独立开发 | 2026.05 - 2026.07
技术栈：Spring Cloud Alibaba / Spring Boot / MyBatis-Plus / MySQL / Redis / RabbitMQ / Seata / Docker
GitHub：https://github.com/lsh-src/edu-wisdom

基于 Spring Cloud Alibaba 构建 B2C 在线教育微服务平台，覆盖课程、订单、学习核心业务，落地 AI 答疑与个性化学习能力

基于 Nacos 实现服务注册发现与动态配置，Gateway 统一鉴权路由，Sentinel 热点限流 + 熔断降级，保障选课核心链路高可用

使用 Seata AT 模式保证跨服务数据一致性；Redisson 分布式锁解决高并发课程超卖；Caffeine + Redis 多级缓存承载热点数据，接口响应提速 60%

对接大模型落地 AI 智能助教（知识点答疑、题库生成）；RabbitMQ 异步解耦 AI 生成任务，死信队列 + 重试机制兜底消费失败

负责课程中心、学习记录模块全流程开发；自定义线程池优化批量学习统计，任务耗时降低 35%；结合 GC 日志定位 ThreadLocal 未清理导致的内存泄漏，Full GC 频率下降 60%

东软颐养中心
独立开发 | 2026.05 - 2026.07
技术栈：Spring Boot 3 / Spring Cloud Gateway / Nacos / RabbitMQ / Vue 3 / Element Plus / MySQL / Redis / 阿里云 OSS / AI（RAG）
GitHub：https://github.com/lsh-src/neusoft-elderly-care-system

养老机构日常运营管理平台，覆盖客户、床位、入住、膳食、护理、数据统计及 AI 智能服务等模块

设计并实现 Spring Boot 3 微服务后端，涵盖认证、客户、床位、入住、膳食、护理等核心业务

基于 Vue 3 + Element Plus 实现前端管理系统，包含通用增删改查、膳食日历、数据仪表盘等功能

集成 AI 模块：AI 对话、基于 RAG 的专业问答、健康评估、护理方案推荐、知识库管理

基于 Spring Cloud Gateway 统一网关 + JWT 认证，Nacos 服务注册发现，RabbitMQ 实现入住事件驱动的异步 AI 分析

工程易淘 — 校园二手交易平台
独立开发 | 2025.10 - 2026.02
技术栈：Spring Boot / MyBatis / MySQL / Redis / RabbitMQ / Elasticsearch / Spring Security / WebSocket
GitHub：https://github.com/lsh-src/engitao

校园 C2C 二手交易平台，覆盖商品发布、智能搜索、即时通讯、订单交易全流程

引入 Elasticsearch + IK/Pinyin 插件实现中文分词与拼音匹配，搜索响应 20-50ms；设计 ES + MySQL 双层降级策略

Redis 缓存搜索热词、用户会话；分布式锁控制库存扣减，异步批量聚合浏览量落库

RabbitMQ 异步解耦 AI 商品生成流程，主链路响应从秒级降至百毫秒；手动 ACK + 幂等校验

落地 JWT 鉴权与 WebSocket 即时通讯

🎓 教育背景
河北工程大学 · 软件工程 本科 | 2023.09 - 2027.07
国家励志奖学金（2024）、第十五届蓝桥杯全国软件大赛省级二等奖（2024）
