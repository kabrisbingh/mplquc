最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.mljc3b.asia/arts/953570.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.mljc3b.asia/arts/861326.Doc

原标题：系统时间同步定时任务偏移
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.mljc3b.asia/arts/860459.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.mljc3b.asia/arts/744991.Doc

原标题：golang 信号量控制并发数量
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.mljc3b.asia/arts/448008.Doc

原标题：golang redis 分布式计数器开发
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.mljc3b.asia/arts/578110.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/644448.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/232818.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.mljc3b.asia/arts/645621.Doc

原标题：golang 系统设计 webhook 回调接口设计要点
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.mljc3b.asia/arts/169689.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.mljc3b.asia/arts/411603.Doc

原标题：接口签名校验防篡改实现
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.mljc3b.asia/arts/047092.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.mljc3b.asia/arts/047336.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/644974.Doc

原标题：golang 系统设计海量数据分页查询
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/537009.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.mljc3b.asia/arts/171222.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.mljc3b.asia/arts/088760.Doc

原标题：零基础理解模块化与组件化基础思想
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.mljc3b.asia/arts/308695.Doc

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.mljc3b.asia/arts/112707.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/898181.Doc

原标题：系统时间同步定时任务偏移
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.mljc3b.asia/arts/157298.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/156995.Doc

原标题：从零学习简单分页逻辑实现思路
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/637255.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.mljc3b.asia/arts/100639.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.mljc3b.asia/arts/345606.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.mljc3b.asia/arts/640903.Doc

原标题：golang docker 容器资源限制设置
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/855584.Doc

原标题：零基础理解HTTP常用请求头与状态码
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.mljc3b.asia/arts/566693.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.mljc3b.asia/arts/060050.Doc

原标题：批量数据处理脚本编写技巧
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.mljc3b.asia/arts/816544.Doc

原标题：内存广播本地进程消息通知
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/548404.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.mljc3b.asia/arts/345636.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.mljc3b.asia/arts/718641.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.mljc3b.asia/arts/344139.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.mljc3b.asia/arts/162059.Doc

原标题：golang kafka 死信队列业务落地
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.mljc3b.asia/arts/985939.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/077112.Doc

原标题：golang 系统设计定时任务分布式锁
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.mljc3b.asia/arts/530766.Doc

原标题：Docker 容器入门镜像实操教程
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.mljc3b.asia/arts/892100.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.mljc3b.asia/arts/391559.Doc


二、踩坑排错｜Troubleshooting
原标题：开源源码阅读拆解学习思路
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/500518.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.mljc3b.asia/arts/488652.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/427406.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.mljc3b.asia/arts/799797.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/741515.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.mljc3b.asia/arts/238404.Doc

原标题：程序性能指标 CPU 内存监控
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.mljc3b.asia/arts/237307.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.mljc3b.asia/arts/900712.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.mljc3b.asia/arts/294776.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.mljc3b.asia/arts/379374.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/189966.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.mljc3b.asia/arts/003984.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/073074.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/717553.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.mljc3b.asia/arts/423380.Doc

原标题：GitHub Markdown 文档语法汇总
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.mljc3b.asia/arts/341768.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.mljc3b.asia/arts/728297.Doc

原标题：依赖版本冲突兼容修复方案
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.mljc3b.asia/arts/555779.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.mljc3b.asia/arts/876520.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.mljc3b.asia/arts/082656.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.mljc3b.asia/arts/886708.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.mljc3b.asia/arts/794939.Doc

原标题：Git commit 钩子提交规范校验
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.mljc3b.asia/arts/829531.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.mljc3b.asia/arts/428076.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.mljc3b.asia/arts/158396.Doc

原标题：hosts 配置本地回环访问修复
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.mljc3b.asia/arts/493586.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.mljc3b.asia/arts/869449.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.mljc3b.asia/arts/163076.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.mljc3b.asia/arts/829034.Doc

原标题：服务熔断防止故障级联传播
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.mljc3b.asia/arts/378768.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.mljc3b.asia/arts/719460.Doc

原标题：golang gorm ORM 数据库操作
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.mljc3b.asia/arts/544954.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.mljc3b.asia/arts/122095.Doc

原标题：项目语义化版本号规范管理
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.mljc3b.asia/arts/468327.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.mljc3b.asia/arts/682845.Doc

原标题：Performance：JSON序列化性能优化实践
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/304211.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.mljc3b.asia/arts/749213.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.mljc3b.asia/arts/604690.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/992473.Doc

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/190856.Doc

三、实战开发｜Practice
原标题：前端静态缓存更新生效处理
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.mljc3b.asia/arts/182005.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.mljc3b.asia/arts/274445.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.mljc3b.asia/arts/850679.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/190224.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.mljc3b.asia/arts/028021.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.mljc3b.asia/arts/460220.Doc

原标题：Shell 运维脚本服务器效率提升
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.mljc3b.asia/arts/788708.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.mljc3b.asia/arts/456286.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.mljc3b.asia/arts/057621.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.mljc3b.asia/arts/742771.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.mljc3b.asia/arts/950682.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/096989.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.mljc3b.asia/arts/968605.Doc

原标题：git rebase 整理提交历史实操
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.mljc3b.asia/arts/120513.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.mljc3b.asia/arts/167391.Doc

原标题：定时任务重复执行分布式锁
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.mljc3b.asia/arts/238705.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.mljc3b.asia/arts/818431.Doc

原标题：golang 单元测试 mock http 请求
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.mljc3b.asia/arts/339436.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.mljc3b.asia/arts/078314.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/278605.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.mljc3b.asia/arts/500861.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.mljc3b.asia/arts/377554.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/153210.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.mljc3b.asia/arts/824301.Doc

原标题：golang kafka 消息顺序性保证方案
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.mljc3b.asia/arts/685775.Doc

原标题：git rebase 整理提交历史实操
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.mljc3b.asia/arts/122895.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/078107.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.mljc3b.asia/arts/960523.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.mljc3b.asia/arts/245925.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.mljc3b.asia/arts/028069.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.mljc3b.asia/arts/488063.Doc

原标题：golang kafka 同步异步消费对比
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/156925.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.mljc3b.asia/arts/855334.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.mljc3b.asia/arts/335084.Doc

原标题：Docker 容器网络不通排查
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/314479.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.mljc3b.asia/arts/276426.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.mljc3b.asia/arts/410595.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/533606.Doc

原标题：golang grpc protobuf 开发实操
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.mljc3b.asia/arts/668925.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.mljc3b.asia/arts/752219.Doc

四、架构设计｜Architecture
原标题：golang 系统设计日志规范结构化日志落地
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.mljc3b.asia/arts/701769.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/606494.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/552690.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.mljc3b.asia/arts/908204.Doc

原标题：golang k8s secret 加密敏感信息
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.mljc3b.asia/arts/803554.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.mljc3b.asia/arts/233290.Doc

原标题：Cookie Session 会话状态管理
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.mljc3b.asia/arts/986904.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.mljc3b.asia/arts/560587.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.mljc3b.asia/arts/800968.Doc

原标题：API 接口调试与异常处理实战
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.mljc3b.asia/arts/573290.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.mljc3b.asia/arts/821124.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.mljc3b.asia/arts/596455.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.mljc3b.asia/arts/597602.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.mljc3b.asia/arts/237408.Doc

原标题：golang github actions 多平台构建
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/126425.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/450829.Doc

原标题：golang k8s 滚动更新回滚策略
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.mljc3b.asia/arts/581032.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/564022.Doc

?
