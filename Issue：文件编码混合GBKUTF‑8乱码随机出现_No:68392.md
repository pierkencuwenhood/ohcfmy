最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.jzt2km.asia/arts/827363.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.jzt2km.asia/arts/755020.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.jzt2km.asia/arts/445589.Doc

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/595226.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.jzt2km.asia/arts/767251.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.jzt2km.asia/arts/393544.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.jzt2km.asia/arts/156259.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.jzt2km.asia/arts/929472.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.jzt2km.asia/arts/293518.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.jzt2km.asia/arts/129821.Doc

原标题：golang kafka 核心概念分区副本
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.jzt2km.asia/arts/971631.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/493888.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.jzt2km.asia/arts/264485.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.jzt2km.asia/arts/378951.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.jzt2km.asia/arts/126840.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.jzt2km.asia/arts/453595.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.jzt2km.asia/arts/149716.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.jzt2km.asia/arts/008033.Doc

原标题：系统字符集统一乱码修复
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.jzt2km.asia/arts/034373.Doc

原标题：golang base64 编码解码实操
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.jzt2km.asia/arts/092811.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.jzt2km.asia/arts/930272.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.jzt2km.asia/arts/971633.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.jzt2km.asia/arts/269142.Doc

原标题：接口压测定位系统性能瓶颈
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.jzt2km.asia/arts/478171.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.jzt2km.asia/arts/893877.Doc

原标题：golang 系统设计会话共享多实例部署
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.jzt2km.asia/arts/166256.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.jzt2km.asia/arts/418693.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.jzt2km.asia/arts/601389.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.jzt2km.asia/arts/482710.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.jzt2km.asia/arts/301378.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.jzt2km.asia/arts/670256.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.jzt2km.asia/arts/353471.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.jzt2km.asia/arts/439743.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/938874.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.jzt2km.asia/arts/220531.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.jzt2km.asia/arts/563092.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.jzt2km.asia/arts/668602.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.jzt2km.asia/arts/075041.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.jzt2km.asia/arts/550911.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.jzt2km.asia/arts/344003.Doc


二、踩坑排错｜Troubleshooting
原标题：Practice：实现跨机器文件同步脚本实践
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.jzt2km.asia/arts/382851.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.jzt2km.asia/arts/901552.Doc

原标题：JWT 工具封装令牌刷新过期
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.jzt2km.asia/arts/416819.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.jzt2km.asia/arts/825737.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.jzt2km.asia/arts/991720.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.jzt2km.asia/arts/184369.Doc

原标题：golang redis 大 key 识别处理方案
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.jzt2km.asia/arts/596625.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.jzt2km.asia/arts/456433.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.jzt2km.asia/arts/620053.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.jzt2km.asia/arts/461442.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.jzt2km.asia/arts/675413.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.jzt2km.asia/arts/564882.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.jzt2km.asia/arts/747770.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.jzt2km.asia/arts/599991.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.jzt2km.asia/arts/722214.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.jzt2km.asia/arts/200067.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.jzt2km.asia/arts/893459.Doc

原标题：文件句柄上限调整上传随机失败
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.jzt2km.asia/arts/562433.Doc

原标题：golang 容器健康检查接口开发
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.jzt2km.asia/arts/635754.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.jzt2km.asia/arts/023056.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.jzt2km.asia/arts/867991.Doc

原标题：Docker 网络模式容器互通设置
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.jzt2km.asia/arts/325222.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.jzt2km.asia/arts/946131.Doc

原标题：异步任务堆积消费能力优化
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.jzt2km.asia/arts/434061.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.jzt2km.asia/arts/315327.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.jzt2km.asia/arts/383927.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.jzt2km.asia/arts/520934.Doc

原标题：从零搭建简单Mock接口服务
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.jzt2km.asia/arts/700461.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.jzt2km.asia/arts/334218.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.jzt2km.asia/arts/044837.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.jzt2km.asia/arts/990028.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.jzt2km.asia/arts/982243.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.jzt2km.asia/arts/509754.Doc

原标题：缓存过期打散防止缓存雪崩
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.jzt2km.asia/arts/736643.Doc

原标题：vite 项目配置与构建提速技巧
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.jzt2km.asia/arts/728555.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.jzt2km.asia/arts/541189.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.jzt2km.asia/arts/116651.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.jzt2km.asia/arts/320919.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.jzt2km.asia/arts/624640.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.jzt2km.asia/arts/803583.Doc

三、实战开发｜Practice
原标题：golang etcd watch 监听配置变更
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.jzt2km.asia/arts/488461.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.jzt2km.asia/arts/788344.Doc

原标题：gRPC 服务端客户端入门示例
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.jzt2km.asia/arts/890609.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.jzt2km.asia/arts/426663.Doc

原标题：前端图片懒加载性能优化
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.jzt2km.asia/arts/446857.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.jzt2km.asia/arts/608008.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.jzt2km.asia/arts/673989.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.jzt2km.asia/arts/486797.Doc

原标题：golang 系统设计内存高占用排查思路
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.jzt2km.asia/arts/133368.Doc

原标题：golang lru 缓存淘汰算法编写
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.jzt2km.asia/arts/759655.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.jzt2km.asia/arts/049154.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.jzt2km.asia/arts/313592.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.jzt2km.asia/arts/555137.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.jzt2km.asia/arts/945688.Doc

原标题：golang 工具函数库封装思路
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.jzt2km.asia/arts/723874.Doc

原标题：开源源码阅读拆解学习思路
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.jzt2km.asia/arts/656137.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.jzt2km.asia/arts/777003.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.jzt2km.asia/arts/864298.Doc

原标题：CI 持续集成自动构建流程
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.jzt2km.asia/arts/577959.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.jzt2km.asia/arts/677957.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.jzt2km.asia/arts/615611.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.jzt2km.asia/arts/159701.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.jzt2km.asia/arts/145146.Doc

原标题：golang channel 通道并发处理
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.jzt2km.asia/arts/914171.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.jzt2km.asia/arts/717106.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.jzt2km.asia/arts/612894.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.jzt2km.asia/arts/208343.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.jzt2km.asia/arts/426973.Doc

原标题：golang 简易埋点日志上报实现
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/021831.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.jzt2km.asia/arts/342005.Doc

原标题：容器资源限制防止宿主机过载
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.jzt2km.asia/arts/159539.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.jzt2km.asia/arts/152313.Doc

原标题：数据库排序规则统一结果一致
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.jzt2km.asia/arts/456088.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/156375.Doc

原标题：入门实践：搭建简单的热更新开发环境
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.jzt2km.asia/arts/270764.Doc

原标题：echarts 大数据渲染性能调优
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.jzt2km.asia/arts/938511.Doc

原标题：golang grpc protobuf 开发实操
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.jzt2km.asia/arts/230485.Doc

原标题：多线程线程安全脏数据规避
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.jzt2km.asia/arts/608394.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.jzt2km.asia/arts/860369.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.jzt2km.asia/arts/537031.Doc

四、架构设计｜Architecture
原标题：golang net/http 超时全套配置
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.jzt2km.asia/arts/799715.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.jzt2km.asia/arts/912874.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.jzt2km.asia/arts/126939.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.jzt2km.asia/arts/177996.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.jzt2km.asia/arts/759740.Doc

原标题：golang 重试退避机制代码实现
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.jzt2km.asia/arts/804319.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.jzt2km.asia/arts/887235.Doc

原标题：service‑worker 离线缓存实践
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.jzt2km.asia/arts/178669.Doc

原标题：golang 熔断降级简易组件开发
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.jzt2km.asia/arts/153525.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.jzt2km.asia/arts/535193.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.jzt2km.asia/arts/340660.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.jzt2km.asia/arts/909257.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.jzt2km.asia/arts/718085.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.jzt2km.asia/arts/325968.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.jzt2km.asia/arts/041851.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.jzt2km.asia/arts/866996.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.jzt2km.asia/arts/433658.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.jzt2km.asia/arts/382743.Doc

?
