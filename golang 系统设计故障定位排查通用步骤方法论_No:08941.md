最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计故障定位排查通用步骤方法论
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/076037.sHtML

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/195312.sHtML

原标题：golang 系统设计大表结构变更不停机方案
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/336364.sHtML

原标题：golang docker 私有仓库搭建使用
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/758801.sHtML

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/502208.sHtML

原标题：安全笔记：CSP内容安全策略配置实践
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/198726.sHtML

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/030733.sHtML

原标题：调优方案：CDN优化静态资源访问延迟
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/371358.sHtML

原标题：golang minio 存储桶权限管控配置
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/303952.sHtML

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/162001.sHtML

原标题：OpenAPI 自动接口文档生成
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/754923.sHtML

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/930346.sHtML

原标题：分布式锁失效问题排查修复
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/077764.sHtML

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/814610.sHtML

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/346038.sHtML

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/373013.sHtML

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/042802.sHtML

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/372626.sHtML

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/383035.sHtML

原标题：golang 定时任务 cron 使用指南
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/333919.sHtML

原标题：golang 系统设计滑动窗口限流代码示例
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/362694.sHtML

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/155850.sHtML

原标题：多规则数据脱敏组件开发
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/191724.sHtML

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/111159.sHtML

原标题：业务错误码完整落地实践
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/646473.sHtML

原标题：实战项目：百万日志文件解析处理脚本实践
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/032246.sHtML

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/512171.sHtML

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/373879.sHtML

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/307297.sHtML

原标题：nodejs 项目 pm2 部署运维指南
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/741438.sHtML

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/490410.sHtML

原标题：Practice：实现请求大小限制中间件防护大报文
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/825953.sHtML

原标题：golang docker 部署 kafka 本地调试
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/393957.sHtML

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/867735.sHtML

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/076442.sHtML

原标题：大事务拆分回滚日志暴涨解决
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/118740.sHtML

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/410212.sHtML

原标题：pnpm 包管理工具实战避坑指南
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/010021.sHtML

原标题：CI 构建缓存加速编译速度
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/327911.sHtML

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/064270.sHtML


二、踩坑排错｜Troubleshooting
原标题：实战：Redis管道批量操作性能优化实践
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/808969.sHtML

原标题：移动端适配 rem vw 方案对比
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/246280.sHtML

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/099475.sHtML

原标题：golang 系统设计 README 开源文档模板
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/394817.sHtML

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/600294.sHtML

原标题：网络读取超时设置连接挂起防护
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/651740.sHtML

原标题：golang redis 五种数据结构实战
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/793232.sHtML

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/932801.sHtML

原标题：golang 系统设计网关灰度流量切分简单方案
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/126815.sHtML

原标题：golang redis 分布式计数器开发
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/806151.sHtML

原标题：golang mysql 防止 sql 注入实践
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/120435.sHtML

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/913765.sHtML

原标题：Practice：实现数据库连接池简易模拟实现
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/489116.sHtML

原标题：golang mysql exists in 性能对比
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/034711.sHtML

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/436097.sHtML

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/708695.sHtML

原标题：golang toml 配置文件解析教程
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/574784.sHtML

原标题：JSON XML 数据解析处理示例
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/005434.sHtML

原标题：全局时间标准统一逻辑错乱修复
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/463304.sHtML

原标题：Practice：批量异步任务处理系统设计实现
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/017724.sHtML

原标题：nestjs 权限守卫鉴权实现方案
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/142138.sHtML

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/912430.sHtML

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/546306.sHtML

原标题：架构复盘：数据库索引架构设计原则与边界
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/542916.sHtML

原标题：nodejs 定时任务生产环境避坑
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/618218.sHtML

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/639600.sHtML

原标题：消息消费重试次数限制防爆炸
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/569534.sHtML

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/590166.sHtML

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/251635.sHtML

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/694576.sHtML

原标题：项目实践：本地模拟多节点分布式系统实践
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/137842.sHtML

原标题：golang redis lua 脚本原子操作
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/085188.sHtML

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/383180.sHtML

原标题：快速上手简单性能监控指标查看
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/888683.sHtML

原标题：实践：分布式事务本地模拟验证实践
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/268177.sHtML

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/943820.sHtML

原标题：golang html 模板渲染简单示例
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/485783.sHtML

原标题：新手教程：Gittag版本标签打标签实操
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/104754.sHtML

原标题：golang mysql 死锁排查步骤讲解
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/447304.sHtML

原标题：golang k8s rbac 权限控制配置示例
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/940890.sHtML

三、实战开发｜Practice
原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/560180.sHtML

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/861707.sHtML

原标题：axios 二次封装请求拦截处理
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/796719.sHtML

原标题：golang redis 缓存穿透解决方案
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/497649.sHtML

原标题：golang 系统设计唯一索引业务使用场景
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/769383.sHtML

原标题：golang 系统设计海量数据分页查询
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/914357.sHtML

原标题：Security：接口鉴权越权漏洞检测与修复
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/539185.sHtML

原标题：快速入门WebSocket，实现简易双向通信demo
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/893625.sHtML

原标题：快速入门消息通知简单实现方案
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/605694.sHtML

原标题：golang pprof 线上采集性能数据
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/443388.sHtML

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/551868.sHtML

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/010357.sHtML

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/514191.sHtML

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/000984.sHtML

原标题：service‑worker 离线缓存实践
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/631914.sHtML

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/392191.sHtML

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/749942.sHtML

原标题：内存溢出问题现象识别排查
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/673950.sHtML

原标题：零基础理解模块化与组件化基础思想
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/374856.sHtML

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/845408.sHtML

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/251260.sHtML

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/348727.sHtML

原标题：react 状态管理方案选型对比
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/121072.sHtML

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/377280.sHtML

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/821559.sHtML

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/747003.sHtML

原标题：消息队列生产消费模型入门
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/296999.sHtML

原标题：不必要字符转义关闭业务异常
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/798811.sHtML

原标题：新手向：开源项目fork与同步上游代码
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/991644.sHtML

原标题：Practice：实现请求大小限制中间件防护大报文
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/547742.sHtML

原标题：nodejs 信号处理优雅关闭服务
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/233532.sHtML

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/467804.sHtML

原标题：nodejs 日志轮转生产环境配置
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/856688.sHtML

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/132911.sHtML

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/727428.sHtML

原标题：排错：CI流水线构建失败，日志无明确报错
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/832701.sHtML

原标题：快速入门异步编程基础模型
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/191961.sHtML

原标题：OpenAPI 自动接口文档生成
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/663970.sHtML

原标题：golang 系统设计内部服务调用超时设置要点
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/202636.sHtML

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/867869.sHtML

四、架构设计｜Architecture
原标题：分布式 ID 生成器高并发实现
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/362407.sHtML

原标题：JSON XML 数据解析处理示例
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/217556.sHtML

原标题：多操作系统开发兼容处理
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/888824.sHtML

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/398535.sHtML

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/351830.sHtML

原标题：容器软链接文件权限修复
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/213117.sHtML

原标题：golang 系统设计缓存基准测试对比方案
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/969975.sHtML

原标题：不必要字符转义关闭业务异常
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/767104.sHtML

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/454904.sHtML

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/661179.sHtML

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/569199.sHtML

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/411109.sHtML

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/412783.sHtML

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/545076.sHtML

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/627478.sHtML

原标题：nodejs 事件循环机制完整讲解
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/126317.sHtML

原标题：nodejs 流处理大文件不占内存
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/693524.sHtML

原标题：golang 系统设计 rest http 方法使用原则
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://bbs.shengquanyk.cn/Article/details/600292.sHtML

?
