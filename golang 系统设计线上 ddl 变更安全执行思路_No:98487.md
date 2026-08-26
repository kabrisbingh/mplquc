最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.icrkyw.asia/arts/835084.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.icrkyw.asia/arts/282616.Doc

原标题：CLI 工具进度条交互效果开发
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.icrkyw.asia/arts/676918.Doc

原标题：前端错误监控上报系统搭建
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.icrkyw.asia/arts/920795.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.icrkyw.asia/arts/547145.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.icrkyw.asia/arts/441346.Doc

原标题：golang 多协程任务池并发控制
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.icrkyw.asia/arts/407316.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.icrkyw.asia/arts/361067.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.icrkyw.asia/arts/417274.Doc

原标题：golang mongodb 分页性能优化技巧
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.icrkyw.asia/arts/696874.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.icrkyw.asia/arts/971537.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.icrkyw.asia/arts/713253.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.icrkyw.asia/arts/144189.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.icrkyw.asia/arts/613231.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.icrkyw.asia/arts/191376.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.icrkyw.asia/arts/565294.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.icrkyw.asia/arts/533228.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.icrkyw.asia/arts/231018.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.icrkyw.asia/arts/617187.Doc

原标题：手写简易 ORM 理解对象映射
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.icrkyw.asia/arts/685748.Doc

原标题：版本升级服务启动失败处理
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.icrkyw.asia/arts/021908.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.icrkyw.asia/arts/225548.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.icrkyw.asia/arts/453649.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.icrkyw.asia/arts/508169.Doc

原标题：golang 分布式锁 redis 实现
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.icrkyw.asia/arts/029275.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.icrkyw.asia/arts/318210.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.icrkyw.asia/arts/463509.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.icrkyw.asia/arts/078706.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.icrkyw.asia/arts/071294.Doc

原标题：接口压测定位系统性能瓶颈
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.icrkyw.asia/arts/439427.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.icrkyw.asia/arts/595105.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.icrkyw.asia/arts/475904.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.icrkyw.asia/arts/212724.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.icrkyw.asia/arts/607589.Doc

原标题：golang kafka 同步异步消费对比
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.icrkyw.asia/arts/838797.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/644830.Doc

原标题：golang github actions 完整工作流示例
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.icrkyw.asia/arts/054127.Doc

原标题：golang es 查询语句 DSL 实操
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.icrkyw.asia/arts/010019.Doc

原标题：golang 结构体深拷贝几种实现
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.icrkyw.asia/arts/947027.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.icrkyw.asia/arts/047616.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 webhook 回调处理架构
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.icrkyw.asia/arts/250794.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/217718.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.icrkyw.asia/arts/551971.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.icrkyw.asia/arts/905349.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.icrkyw.asia/arts/517138.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.icrkyw.asia/arts/445981.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.icrkyw.asia/arts/646357.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.icrkyw.asia/arts/633207.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.icrkyw.asia/arts/225515.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.icrkyw.asia/arts/427231.Doc

原标题：golang minio 存储桶权限管控配置
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.icrkyw.asia/arts/901425.Doc

原标题：golang html 模板渲染简单示例
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.icrkyw.asia/arts/812809.Doc

原标题：css 动画性能优化 GPU 加速
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.icrkyw.asia/arts/545292.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.icrkyw.asia/arts/405503.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.icrkyw.asia/arts/553998.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.icrkyw.asia/arts/199347.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.icrkyw.asia/arts/001333.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.icrkyw.asia/arts/684252.Doc

原标题：macOS 脚本执行权限开启
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.icrkyw.asia/arts/294112.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.icrkyw.asia/arts/227106.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/098969.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.icrkyw.asia/arts/508769.Doc

原标题：golang mysql 读写分离简单实现
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.icrkyw.asia/arts/842077.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.icrkyw.asia/arts/139247.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/658930.Doc

原标题：后端登录鉴权模块完整开发
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.icrkyw.asia/arts/530814.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.icrkyw.asia/arts/081376.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.icrkyw.asia/arts/423129.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.icrkyw.asia/arts/413632.Doc

原标题：golang 优雅处理 http 超时设置
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.icrkyw.asia/arts/161825.Doc

原标题：golang 灰度权重流量分发简单实现
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.icrkyw.asia/arts/168295.Doc

原标题：golang kafka 重试机制配置实操
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.icrkyw.asia/arts/151714.Doc

原标题：代码模块化组件化拆分思路
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.icrkyw.asia/arts/826969.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.icrkyw.asia/arts/359129.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.icrkyw.asia/arts/134649.Doc

原标题：程序预加载加快服务启动速度
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.icrkyw.asia/arts/561466.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.icrkyw.asia/arts/467950.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.icrkyw.asia/arts/124119.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.icrkyw.asia/arts/414202.Doc

原标题：实践：数据库回滚点业务调试实践
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.icrkyw.asia/arts/204889.Doc

三、实战开发｜Practice
原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.icrkyw.asia/arts/240056.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.icrkyw.asia/arts/397901.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.icrkyw.asia/arts/197816.Doc

原标题：golang goroutine 池任务调度
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.icrkyw.asia/arts/627749.Doc

原标题：业务错误码完整落地实践
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.icrkyw.asia/arts/120140.Doc

原标题：golang mongodb 分页性能优化技巧
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.icrkyw.asia/arts/222484.Doc

原标题：nodejs 定时任务生产环境避坑
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.icrkyw.asia/arts/683482.Doc

原标题：golang 项目目录分层规范设计
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.icrkyw.asia/arts/833312.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.icrkyw.asia/arts/484463.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.icrkyw.asia/arts/728485.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.icrkyw.asia/arts/724217.Doc

原标题：golang mysql 慢查询日志开启分析
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.icrkyw.asia/arts/677756.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.icrkyw.asia/arts/940269.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.icrkyw.asia/arts/767183.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.icrkyw.asia/arts/199109.Doc

原标题：包管理器依赖缓存清理
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.icrkyw.asia/arts/281494.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.icrkyw.asia/arts/804452.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.icrkyw.asia/arts/796576.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.icrkyw.asia/arts/833759.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.icrkyw.asia/arts/105323.Doc

原标题：nodejs 中间件模式原理剖析
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.icrkyw.asia/arts/521789.Doc

原标题：集成测试业务流程编写示例
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.icrkyw.asia/arts/931216.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.icrkyw.asia/arts/947443.Doc

原标题：部署实践：告警收敛避免告警风暴配置
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.icrkyw.asia/arts/451941.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.icrkyw.asia/arts/186868.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.icrkyw.asia/arts/053701.Doc

原标题：golang etcd 分布式锁实现原理
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.icrkyw.asia/arts/016408.Doc

原标题：golang gorm ORM 数据库操作
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.icrkyw.asia/arts/333174.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.icrkyw.asia/arts/345566.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.icrkyw.asia/arts/320786.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.icrkyw.asia/arts/930771.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.icrkyw.asia/arts/721112.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.icrkyw.asia/arts/407574.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.icrkyw.asia/arts/168662.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.icrkyw.asia/arts/243767.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.icrkyw.asia/arts/949648.Doc

原标题：前端组件库按需加载性能优化
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.icrkyw.asia/arts/086483.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/034926.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.icrkyw.asia/arts/780715.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.icrkyw.asia/arts/517305.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 api 网关核心能力梳理
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.icrkyw.asia/arts/351934.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.icrkyw.asia/arts/890794.Doc

原标题：HTTPS 证书过期更新操作
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.icrkyw.asia/arts/976636.Doc

原标题：golang ci 流水线单元测试集成测试
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.icrkyw.asia/arts/725373.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.icrkyw.asia/arts/571227.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.icrkyw.asia/arts/659634.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.icrkyw.asia/arts/939906.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.icrkyw.asia/arts/851241.Doc

原标题：golang docker 部署 prometheus 整套
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/122828.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.icrkyw.asia/arts/093811.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.icrkyw.asia/arts/083609.Doc

原标题：静态资源 404 路径打包修复
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.icrkyw.asia/arts/161232.Doc

原标题：nodejs 内存溢出问题排查修复
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.icrkyw.asia/arts/788197.Doc

原标题：golang redis lua 脚本开发调试
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.icrkyw.asia/arts/376323.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.icrkyw.asia/arts/120079.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.icrkyw.asia/arts/028139.Doc

原标题：golang mock 单元测试编写技巧
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.icrkyw.asia/arts/162825.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.icrkyw.asia/arts/897670.Doc

?
