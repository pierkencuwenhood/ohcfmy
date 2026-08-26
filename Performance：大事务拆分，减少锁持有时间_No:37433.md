最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Performance：大事务拆分，减少锁持有时间
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.e0bao8.asia/blog/220654.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.e0bao8.asia/blog/716466.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.e0bao8.asia/blog/353525.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.e0bao8.asia/blog/602366.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.e0bao8.asia/blog/142141.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.e0bao8.asia/blog/316345.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.e0bao8.asia/blog/633057.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.e0bao8.asia/blog/300959.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.e0bao8.asia/blog/888999.Doc

原标题：hosts 配置本地回环访问修复
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.e0bao8.asia/blog/482397.Doc

原标题：Shell 运维脚本服务器效率提升
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.e0bao8.asia/blog/597067.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.e0bao8.asia/blog/508258.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.e0bao8.asia/blog/388330.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.e0bao8.asia/blog/493481.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.e0bao8.asia/blog/319668.Doc

原标题：手写简易 RPC 服务通信原型
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.e0bao8.asia/blog/776478.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.e0bao8.asia/blog/609472.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.e0bao8.asia/blog/591330.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.e0bao8.asia/blog/672559.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.e0bao8.asia/blog/411716.Doc

原标题：golang 优雅处理数据库事务
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.e0bao8.asia/blog/924066.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.e0bao8.asia/blog/020636.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.e0bao8.asia/blog/451043.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.e0bao8.asia/blog/762818.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.e0bao8.asia/blog/897032.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.e0bao8.asia/blog/565809.Doc

原标题：golang 系统设计短信发送限流降级
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.e0bao8.asia/blog/085694.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.e0bao8.asia/blog/675927.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.e0bao8.asia/blog/839456.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.e0bao8.asia/blog/042652.Doc

原标题：golang redis pipeline 原子性说明
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.e0bao8.asia/blog/995255.Doc

原标题：HTTPS 证书过期更新操作
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.e0bao8.asia/blog/612553.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.e0bao8.asia/blog/797477.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.e0bao8.asia/blog/606225.Doc

原标题：定时任务周期调度 demo 开发
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.e0bao8.asia/blog/645309.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.e0bao8.asia/blog/962418.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.e0bao8.asia/blog/116474.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.e0bao8.asia/blog/857144.Doc

原标题：golang mysql 批量导入数据实操
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.e0bao8.asia/blog/531761.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.e0bao8.asia/blog/902479.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计短链接服务实现思路
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.e0bao8.asia/blog/379764.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.e0bao8.asia/blog/664346.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.e0bao8.asia/blog/161664.Doc

原标题：简易日志收集集中管理方案
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.e0bao8.asia/blog/897236.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.e0bao8.asia/blog/716624.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.e0bao8.asia/blog/070512.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.e0bao8.asia/blog/119489.Doc

原标题：golang docker 部署 prometheus 整套
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.e0bao8.asia/blog/153747.Doc

原标题：项目目录结构规范化最佳实践
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.e0bao8.asia/blog/568071.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.e0bao8.asia/blog/919630.Doc

原标题：文件监控服务自动重启开发
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.e0bao8.asia/blog/902186.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.e0bao8.asia/blog/590268.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.e0bao8.asia/blog/230005.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.e0bao8.asia/blog/583321.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.e0bao8.asia/blog/086144.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.e0bao8.asia/blog/456044.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.e0bao8.asia/blog/521386.Doc

原标题：前端防抖节流高频事件处理
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.e0bao8.asia/blog/753476.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.e0bao8.asia/blog/453997.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.e0bao8.asia/blog/276547.Doc

原标题：golang github actions 发布 release 包
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.e0bao8.asia/blog/220249.Doc

原标题：golang mysql 主从同步延迟兼容
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.e0bao8.asia/blog/073512.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.e0bao8.asia/blog/349227.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.e0bao8.asia/blog/296179.Doc

原标题：nodejs 定时任务生产环境避坑
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.e0bao8.asia/blog/323923.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.e0bao8.asia/blog/691254.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.e0bao8.asia/blog/445153.Doc

原标题：磁盘占满服务不可用清理方案
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.e0bao8.asia/blog/456850.Doc

原标题：对象存储上传下载权限实操
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.e0bao8.asia/blog/563764.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.e0bao8.asia/blog/978155.Doc

原标题：golang redis hyperloglog 基数统计
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.e0bao8.asia/blog/206875.Doc

原标题：golang 单元测试 mock http 请求
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.e0bao8.asia/blog/864846.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.e0bao8.asia/blog/535271.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.e0bao8.asia/blog/263507.Doc

原标题：golang 系统设计热点数据缓存处理
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.e0bao8.asia/blog/897006.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.e0bao8.asia/blog/490392.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.e0bao8.asia/blog/933113.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.e0bao8.asia/blog/933524.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.e0bao8.asia/blog/942035.Doc

原标题：golang github actions 发布 release 包
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.e0bao8.asia/blog/895266.Doc

三、实战开发｜Practice
原标题：golang docker 多阶段构建 go 镜像
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.e0bao8.asia/blog/042166.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.e0bao8.asia/blog/626629.Doc

原标题：golang 系统设计 mq 消息重复消费处理
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.e0bao8.asia/blog/855598.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.e0bao8.asia/blog/311878.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.e0bao8.asia/blog/452519.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.e0bao8.asia/blog/130412.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.e0bao8.asia/blog/249396.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.e0bao8.asia/blog/755240.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.e0bao8.asia/blog/514973.Doc

原标题：golang 配置热更新不重启服务
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.e0bao8.asia/blog/620617.Doc

原标题：异步任务堆积消费能力优化
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://book.e0bao8.asia/blog/397870.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.e0bao8.asia/blog/078512.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.e0bao8.asia/blog/676643.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.e0bao8.asia/blog/076279.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.e0bao8.asia/blog/048132.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.e0bao8.asia/blog/941424.Doc

原标题：golang 分布式锁防死锁处理
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.e0bao8.asia/blog/943572.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.e0bao8.asia/blog/268720.Doc

原标题：定时任务重复执行分布式锁
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.e0bao8.asia/blog/827761.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.e0bao8.asia/blog/851067.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.e0bao8.asia/blog/644794.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.e0bao8.asia/blog/371719.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.e0bao8.asia/blog/126265.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.e0bao8.asia/blog/208919.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.e0bao8.asia/blog/184727.Doc

原标题：缓存基础原理与简单代码实现
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.e0bao8.asia/blog/562554.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.e0bao8.asia/blog/821857.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.e0bao8.asia/blog/152841.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.e0bao8.asia/blog/331455.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.e0bao8.asia/blog/630405.Doc

原标题：快速入门对象存储基础使用场景
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.e0bao8.asia/blog/820791.Doc

原标题：golang context 上下文传参讲解
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.e0bao8.asia/blog/822002.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.e0bao8.asia/blog/731694.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.e0bao8.asia/blog/150776.Doc

原标题：限流组件计数器令牌桶模式实现
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.e0bao8.asia/blog/460998.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.e0bao8.asia/blog/169483.Doc

原标题：golang docker 基础命令实操汇总
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.e0bao8.asia/blog/186600.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.e0bao8.asia/blog/041706.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.e0bao8.asia/blog/753602.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.e0bao8.asia/blog/622419.Doc

四、架构设计｜Architecture
原标题：零基础学习简单正则表达式实战案例
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.e0bao8.asia/blog/484661.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://book.e0bao8.asia/blog/429545.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://book.e0bao8.asia/blog/907025.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.e0bao8.asia/blog/163905.Doc

原标题：golang 配置文件多环境加载
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.e0bao8.asia/blog/855767.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.e0bao8.asia/blog/457028.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.e0bao8.asia/blog/048553.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.e0bao8.asia/blog/675193.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.e0bao8.asia/blog/093986.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.e0bao8.asia/blog/561135.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.e0bao8.asia/blog/292905.Doc

原标题：安全组端口开放网络访问
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.e0bao8.asia/blog/267763.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.e0bao8.asia/blog/371403.Doc

原标题：golang makefile 自动化构建脚本
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.e0bao8.asia/blog/080329.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.e0bao8.asia/blog/790462.Doc

原标题：WSL 文件权限访问异常修复
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.e0bao8.asia/blog/919321.Doc

原标题：Docker 容器网络不通排查
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.e0bao8.asia/blog/347489.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.e0bao8.asia/blog/233657.Doc

?
