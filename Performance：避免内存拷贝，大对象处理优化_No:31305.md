最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.sezp3s.asia/arts/046417.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.sezp3s.asia/arts/663295.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.sezp3s.asia/arts/314698.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.sezp3s.asia/arts/856826.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.sezp3s.asia/arts/013449.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.sezp3s.asia/arts/192474.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.sezp3s.asia/arts/914403.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.sezp3s.asia/arts/826533.Doc

原标题：前端防抖节流高频事件处理
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.sezp3s.asia/arts/701518.Doc

原标题：前端骨架屏提升页面体验
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.sezp3s.asia/arts/887609.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.sezp3s.asia/arts/314163.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.sezp3s.asia/arts/786286.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.sezp3s.asia/arts/874321.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.sezp3s.asia/arts/745433.Doc

原标题：golang k8s 滚动更新回滚策略
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.sezp3s.asia/arts/815088.Doc

原标题：消息队列消费堆积扩容处理
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.sezp3s.asia/arts/018233.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.sezp3s.asia/arts/783352.Doc

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.sezp3s.asia/arts/088644.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.sezp3s.asia/arts/182701.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.sezp3s.asia/arts/088148.Doc

原标题：浏览器缓存强制刷新方案
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.sezp3s.asia/arts/343252.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.sezp3s.asia/arts/381048.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.sezp3s.asia/arts/342939.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.sezp3s.asia/arts/293995.Doc

原标题：百万数据 Excel 导出内存优化
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.sezp3s.asia/arts/135142.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.sezp3s.asia/arts/834130.Doc

原标题：缓存穿透防护保护数据库
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.sezp3s.asia/arts/650369.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.sezp3s.asia/arts/822369.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.sezp3s.asia/arts/031828.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.sezp3s.asia/arts/578810.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.sezp3s.asia/arts/869532.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.sezp3s.asia/arts/301040.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.sezp3s.asia/arts/416984.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.sezp3s.asia/arts/918192.Doc

原标题：架构笔记：高并发系统核心设计思路总结
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.sezp3s.asia/arts/784095.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.sezp3s.asia/arts/298723.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.sezp3s.asia/arts/830645.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.sezp3s.asia/arts/663291.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.sezp3s.asia/arts/792922.Doc

原标题：golang kafka 重试机制配置实操
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.sezp3s.asia/arts/270663.Doc


二、踩坑排错｜Troubleshooting
原标题：线上异常：接口偶发超时，完整定位过程记录
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.sezp3s.asia/arts/363240.Doc

原标题：本地数据库开发环境搭建指南
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/962690.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.sezp3s.asia/arts/504359.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.sezp3s.asia/arts/499621.Doc

原标题：代码模块化组件化拆分思路
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.sezp3s.asia/arts/288622.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.sezp3s.asia/arts/676677.Doc

原标题：前端下载导出文件功能实现
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.sezp3s.asia/arts/324972.Doc

原标题：项目构建脚本编译打包解析
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.sezp3s.asia/arts/184315.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.sezp3s.asia/arts/738116.Doc

原标题：golang 数据库批量更新性能优化
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/741703.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.sezp3s.asia/arts/122758.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.sezp3s.asia/arts/867314.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.sezp3s.asia/arts/373998.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.sezp3s.asia/arts/992287.Doc

原标题：golang gin 中间件执行顺序讲解
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.sezp3s.asia/arts/642601.Doc

原标题：Mock 接口服务快速搭建实操
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.sezp3s.asia/arts/953936.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.sezp3s.asia/arts/488137.Doc

原标题：语义化版本依赖管理防错乱
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/883355.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.sezp3s.asia/arts/472056.Doc

原标题：golang 系统信号信号量处理
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.sezp3s.asia/arts/726247.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.sezp3s.asia/arts/637058.Doc

原标题：golang redis lua 脚本开发调试
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.sezp3s.asia/arts/279204.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.sezp3s.asia/arts/383730.Doc

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.sezp3s.asia/arts/663721.Doc

原标题：golang 系统设计文件存储选型对比
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.sezp3s.asia/arts/936133.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.sezp3s.asia/arts/204084.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.sezp3s.asia/arts/249293.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.sezp3s.asia/arts/377732.Doc

原标题：vue3 组合式 API 业务开发实战
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.sezp3s.asia/arts/866381.Doc

原标题：nodejs 接口限流防刷代码实现
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.sezp3s.asia/arts/565227.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.sezp3s.asia/arts/048234.Doc

原标题：消息队列生产消费模型入门
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.sezp3s.asia/arts/013007.Doc

原标题：golang github actions 多平台构建
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.sezp3s.asia/arts/322612.Doc

原标题：静态站点自动部署发布方案
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.sezp3s.asia/arts/931535.Doc

原标题：golang redis 集群 hash 槽讲解
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.sezp3s.asia/arts/230465.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.sezp3s.asia/arts/783112.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.sezp3s.asia/arts/334655.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.sezp3s.asia/arts/713578.Doc

原标题：接口限流逻辑简单模拟实现
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.sezp3s.asia/arts/339005.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.sezp3s.asia/arts/354756.Doc

三、实战开发｜Practice
原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.sezp3s.asia/arts/671464.Doc

原标题：多规则数据脱敏组件开发
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.sezp3s.asia/arts/331468.Doc

原标题：golang 链路追踪简易实现方案
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.sezp3s.asia/arts/116394.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.sezp3s.asia/arts/680185.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.sezp3s.asia/arts/642175.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.sezp3s.asia/arts/792654.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.sezp3s.asia/arts/423059.Doc

原标题：异步任务堆积消费能力优化
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/820079.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.sezp3s.asia/arts/411841.Doc

原标题：golang mysql 防止 sql 注入实践
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.sezp3s.asia/arts/195986.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.sezp3s.asia/arts/608456.Doc

原标题：express 中间件开发业务实践
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/788142.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.sezp3s.asia/arts/150908.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.sezp3s.asia/arts/371880.Doc

原标题：golang docker compose 部署 minio
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/312791.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.sezp3s.asia/arts/826557.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.sezp3s.asia/arts/728941.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.sezp3s.asia/arts/028484.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.sezp3s.asia/arts/226000.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.sezp3s.asia/arts/308593.Doc

原标题：特殊输入字符过滤解析防护
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.sezp3s.asia/arts/104034.Doc

原标题：前端组件库按需加载性能优化
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.sezp3s.asia/arts/458570.Doc

原标题：简易网关请求路由过滤模拟
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.sezp3s.asia/arts/786029.Doc

原标题：不必要字符转义关闭业务异常
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.sezp3s.asia/arts/778895.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.sezp3s.asia/arts/211098.Doc

原标题：OAuth2 第三方登录服务搭建
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.sezp3s.asia/arts/284577.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.sezp3s.asia/arts/773088.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.sezp3s.asia/arts/631063.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.sezp3s.asia/arts/422502.Doc

原标题：golang 互斥锁读写锁并发安全
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.sezp3s.asia/arts/493286.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/458761.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.sezp3s.asia/arts/429419.Doc

原标题：golang k8s 基础概念 pod deployment
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.sezp3s.asia/arts/448756.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.sezp3s.asia/arts/429654.Doc

原标题：golang kafka 批量发送消费优化
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.sezp3s.asia/arts/773356.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.sezp3s.asia/arts/741359.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.sezp3s.asia/arts/793654.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.sezp3s.asia/arts/304114.Doc

原标题：golang redis 五种数据结构实战
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.sezp3s.asia/arts/500851.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/244783.Doc

四、架构设计｜Architecture
原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.sezp3s.asia/arts/246220.Doc

原标题：简易日志收集集中管理方案
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.sezp3s.asia/arts/451362.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.sezp3s.asia/arts/201809.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.sezp3s.asia/arts/296099.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.sezp3s.asia/arts/252544.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.sezp3s.asia/arts/141076.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.sezp3s.asia/arts/536373.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.sezp3s.asia/arts/307628.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.sezp3s.asia/arts/756044.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.sezp3s.asia/arts/781942.Doc

原标题：实战：对象存储断点续传下载实践
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.sezp3s.asia/arts/973797.Doc

原标题：golang 开发环境快速搭建指南
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.sezp3s.asia/arts/568242.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.sezp3s.asia/arts/560050.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/239031.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/898046.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.sezp3s.asia/arts/560309.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.sezp3s.asia/arts/352666.Doc

原标题：golang defer panic 异常处理
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.sezp3s.asia/arts/503233.Doc

?
