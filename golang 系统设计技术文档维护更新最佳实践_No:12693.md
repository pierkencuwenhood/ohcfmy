最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9370804.sHtML

原标题：正则表达式优化 CPU 占满问题
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3388120.sHtML

原标题：Practice：实现IP黑名单拦截中间件实践
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5241465.sHtML

原标题：golang 系统设计缓存优化落地实操指南
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0860196.sHtML

原标题：golang redis 缓存雪崩完整处理
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8082161.sHtML

原标题：OpenSource：开源项目README高质量编写指南
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8537603.sHtML

原标题：部署实践：容器优雅停机配置处理信号
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0471018.sHtML

原标题：文件句柄耗尽资源泄露处理
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8470507.sHtML

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2253880.sHtML

原标题：nodejs 跨域中间件配置细节
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0137542.sHtML

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8860561.sHtML

原标题：开发复盘：统一错误码体系设计落地实践
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2900127.sHtML

原标题：特殊输入字符过滤解析防护
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3725572.sHtML

原标题：Nginx 缓冲区调优大文件上传
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7244873.sHtML

原标题：golang redis 发布订阅简单示例
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6719645.sHtML

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5951978.sHtML

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7766029.sHtML

原标题：部署实践：数据库迁移脚本版本管理实践
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9319076.sHtML

原标题：动态定时任务业务调度实现
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2125748.sHtML

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9268407.sHtML

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7562821.sHtML

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0023543.sHtML

原标题：golang 系统设计技术方案文档模板参考
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6397191.sHtML

原标题：golang 系统设计接口返回格式统一规范
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6322672.sHtML

原标题：golang docker 部署 kafka 本地调试
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7403771.sHtML

原标题：磁盘 inode 耗尽文件创建失败
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8883222.sHtML

原标题：golang k8s 网络策略网络隔离设置
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0461427.sHtML

原标题：部署实践：Nginx高可用配置方案实践
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8351193.sHtML

原标题：golang 分库分表简单路由实现
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3153954.sHtML

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8778171.sHtML

原标题：零基础理解依赖管理与包管理器
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9705864.sHtML

原标题：golang kafka 重试机制配置实操
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7169024.sHtML

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3068877.sHtML

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8386279.sHtML

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8959578.sHtML

原标题：优化实践：读写分离分担主库查询压力
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7242754.sHtML

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0833595.sHtML

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3562613.sHtML

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0490549.sHtML

原标题：零基础理解JSON、XML数据格式处理
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4209561.sHtML


二、踩坑排错｜Troubleshooting
原标题：批量操作分批处理防止 OOM
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0794499.sHtML

原标题：golang 大文件 http 下载服务
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5206131.sHtML

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3242845.sHtML

原标题：golang mongodb 文档结构设计原则
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7750498.sHtML

原标题：golang gin 路由分组权限管控
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1153387.sHtML

原标题：git rebase 整理提交历史实操
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3053096.sHtML

原标题：前端工程化 webpack 打包优化
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9708157.sHtML

原标题：CI 持续集成自动构建流程
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6139404.sHtML

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8477119.sHtML

原标题：快速入门：API接口调试完整实操步骤
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9919033.sHtML

原标题：golang mysql 慢查询日志开启分析
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3058980.sHtML

原标题：数值类型溢出错乱问题修复
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8285640.sHtML

原标题：golang mysql 悲观锁乐观锁实现
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7945087.sHtML

原标题：全量回归测试提升代码质量
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9851811.sHtML

原标题：golang 灰度权重流量分发简单实现
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1816780.sHtML

原标题：方案设计：分布式分页查询架构难点处理
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3400136.sHtML

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4469279.sHtML

原标题：后端登录鉴权模块完整开发
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2653744.sHtML

原标题：golang 单元测试 table‑driven
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7424340.sHtML

原标题：golang prometheus counter gauge 使用
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9776962.sHtML

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4127425.sHtML

原标题：Git 分支管理多人协作实战教程
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0569103.sHtML

原标题：golang mysql 慢查询日志开启分析
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5920218.sHtML

原标题：内存溢出问题现象识别排查
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4731353.sHtML

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4267672.sHtML

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3688671.sHtML

原标题：零基础理解依赖管理与包管理器
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4583785.sHtML

原标题：请求重试组件退避策略实现
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6437246.sHtML

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3864875.sHtML

原标题：部署实践：服务器防火墙安全组配置实践
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1842244.sHtML

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1595135.sHtML

原标题：golang 系统设计消息消费 offset 管理策略
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3158746.sHtML

原标题：golang 分库分表简单路由实现
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1194146.sHtML

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8591676.sHtML

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0592002.sHtML

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5342737.sHtML

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3878607.sHtML

原标题：nodejs 内存溢出问题排查修复
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5925017.sHtML

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5088108.sHtML

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2847866.sHtML

三、实战开发｜Practice
原标题：缓存基础原理与简单代码实现
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1630799.sHtML

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0475724.sHtML

原标题：RPC 报文大小上限调优大请求
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1708316.sHtML

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0191231.sHtML

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6054468.sHtML

原标题：golang 系统设计告警风暴抑制方案实现
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8344548.sHtML

原标题：部署实践：容器优雅停机配置处理信号
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1395129.sHtML

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3958273.sHtML

原标题：前端打包分包加载提速方案
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5039404.sHtML

原标题：方案对比：定时任务框架选型与架构对比
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8011231.sHtML

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2357584.sHtML

原标题：前端虚拟列表大数据渲染优化
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9624275.sHtML

原标题：golang 系统设计技术方案评审关注点清单参考
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0514545.sHtML

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2579399.sHtML

原标题：golang 系统设计架构图绘图工具选型对比
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9478779.sHtML

原标题：golang redis 大 key 识别处理方案
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7818931.sHtML

原标题：实践：灰度流量切分简易实现方案
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8614727.sHtML

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8899777.sHtML

原标题：实战项目：容器健康探针配置完整实践示例
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7291836.sHtML

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0237451.sHtML

原标题：golang 开发环境快速搭建指南
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6827496.sHtML

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5211163.sHtML

原标题：5分钟快速搭建个人技术文档站点
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0757036.sHtML

原标题：OpenSource：开源项目README高质量编写指南
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0112760.sHtML

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0738239.sHtML

原标题：CI/CD 流水线自动构建部署落地
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4243649.sHtML

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9934230.sHtML

原标题：golang docker 部署 prometheus 整套
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9794547.sHtML

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6167021.sHtML

原标题：安全复盘：消息队列未授权访问安全加固
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1122861.sHtML

原标题：golang docker 部署 es 本地开发
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7149860.sHtML

原标题：从零搭建简单的健康检查接口示例
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1994300.sHtML

原标题：golang kafka 同步异步消费对比
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6650380.sHtML

原标题：golang 项目 docker compose 本地调试
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4979382.sHtML

原标题：golang grafana 监控面板简单配置
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://zhishi.bt97k0.asia/blog/6461943.sHtML

原标题：golang kafka 消息丢失重复消费
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7935705.sHtML

原标题：golang 系统设计配置回滚版本历史记录实现
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1941050.sHtML

原标题：golang redis 发布订阅简单示例
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4225317.sHtML

原标题：golang k8s 节点污点容忍度配置
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://zhishi.bt97k0.asia/blog/1501605.sHtML

原标题：浏览器内存泄漏排查前端页面
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7860523.sHtML

四、架构设计｜Architecture
原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2654561.sHtML

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4088561.sHtML

原标题：新手指南：看懂开源项目的Issue与PR
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0192242.sHtML

原标题：部署复盘：配置热更新不用重启服务方案
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7276247.sHtML

原标题：golang 配置热更新不重启服务
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9618796.sHtML

原标题：golang 大文件 http 下载服务
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3856874.sHtML

原标题：golang 系统设计缓存降级开关快速切库实现
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2047177.sHtML

原标题：简易网关请求路由过滤模拟
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8280055.sHtML

原标题：数据库读写分离性能优化
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8800591.sHtML

原标题：Hands‑on：简易消息推送服务开发实践
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://zhishi.bt97k0.asia/blog/7841365.sHtML

原标题：golang 系统设计技术文档维护更新最佳实践
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://zhishi.bt97k0.asia/blog/4595723.sHtML

原标题：接口签名验签完整安全方案
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://zhishi.bt97k0.asia/blog/3873136.sHtML

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://zhishi.bt97k0.asia/blog/5644729.sHtML

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://zhishi.bt97k0.asia/blog/8792284.sHtML

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://zhishi.bt97k0.asia/blog/0458387.sHtML

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9840913.sHtML

原标题：golang mysql 慢查询日志开启分析
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://zhishi.bt97k0.asia/blog/9256405.sHtML

原标题：服务健康检查监控接口开发
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://zhishi.bt97k0.asia/blog/2451944.sHtML

?
