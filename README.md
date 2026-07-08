# 李韶涵 | Java 后端开发工程师

> 求职意向：Java 后端开发工程师 | 期望城市：北京 | 22岁

## 📬 联系方式
- 📱 电话：13460772183
- 📧 邮箱：2990732278@qq.com
- 📍 籍贯：河南开封

## 🛠 技术栈
### Java 基础与 JVM
熟练掌握 Java 核心语法、集合框架、并发编程（线程池、JUC）；熟悉 JVM 内存模型与 GC 机制，具备基础问题排查能力。

### 框架与微服务
熟练使用 Spring Boot / Spring MVC / MyBatis-Plus 开发；熟悉 Spring Cloud Alibaba（Nacos / Gateway / Sentinel / Seata），有完整微服务项目实践。

### 存储与中间件
- 熟练使用 MySQL 编写复杂 SQL，熟悉事务隔离级别与索引优化
- 熟练使用 Redis 实现缓存与分布式锁
- 熟悉 RabbitMQ 消息可靠投递与幂等设计

### 搜索引擎
熟悉 Elasticsearch，掌握倒排索引原理、IK/Pinyin 分词配置与基础 DSL 查询。

### 工程化与工具
Git 版本管理、Docker 容器化部署、Linux 基础运维、Postman 接口联调。

### AI 开发提效
熟练使用 Claude Code 等 AI 工具辅助开发，能甄别并修正生成代码的逻辑问题。

## 💼 项目经历
### 工程易淘 · 校园二手交易平台
`独立开发` | 2025.10 - 2026.02
**技术栈**：Spring Boot / MyBatis / MySQL / Redis / RabbitMQ / Elasticsearch / Spring Security / WebSocket

- 覆盖商品发布、智能搜索、即时通讯、订单交易全流程的校园 C2C 二手交易平台
- 引入 Elasticsearch + IK/Pinyin 插件实现中文分词与拼音匹配，搜索响应 20-50ms；设计 ES + MySQL 双层降级策略保障可用性
- 基于 Spring Security + JWT 实现登录认证，WebSocket 支持商品即时通讯
- Redis 承载搜索热词、用户会话与缓存；分布式锁控制库存扣减，异步批量聚合浏览量落库，降低数据库写入压力
- RabbitMQ 异步解耦 AI 商品描述生成，主流程响应从秒级降至百毫秒级；手动 ACK + 幂等校验保障消息可靠消费

### 河工学堂 · 校园 AI 智能学习平台
`独立开发` | 2026.03 - 2026.07
**技术栈**：Spring Cloud Alibaba / Spring Boot / MyBatis-Plus / MySQL / Redis / RabbitMQ / Seata / Docker

- 基于 Spring Cloud Alibaba 构建的 B2C 在线教育微服务平台，覆盖课程、订单、学习核心业务，落地 AI 答疑与推荐能力
- 基于 Nacos 实现服务注册发现与动态配置，Gateway 统一鉴权路由，Sentinel 配置热点限流与熔断降级
- Seata AT 模式保障订单支付、课程开通、学习记录的数据一致性，梳理并优化全局锁性能瓶颈
- Redisson 分布式锁管控库存扣减，解决高并发超卖问题；Caffeine + Redis 多级缓存承载热点数据
- 对接大模型落地 AI 智能助教，支持知识点答疑与个性化题库生成；RabbitMQ 异步解耦耗时流程
- 负责课程中心、学习记录模块全流程开发；自定义线程池优化批量学习数据统计，任务耗时降低 35%；通过 GC 日志分析定位内存泄漏，Full GC 频率下降 60%

## 🎓 教育背景
**河北工程大学** · 软件工程 本科 | 2023.09 - 2027.06

---

> 持续深耕 Java 后端技术，关注微服务架构与 AI 开发提效，仓库持续更新中。
