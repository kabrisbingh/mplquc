最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计熔断降级架构讲解
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.etx3og.asia/arts/672135.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.etx3og.asia/arts/319733.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.etx3og.asia/arts/452447.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.etx3og.asia/arts/956503.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.etx3og.asia/arts/787241.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.etx3og.asia/arts/789229.Doc

原标题：零基础理解前后端简单交互流程
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.etx3og.asia/arts/901844.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.etx3og.asia/arts/029546.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.etx3og.asia/arts/645286.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.etx3og.asia/arts/958130.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.etx3og.asia/arts/460055.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.etx3og.asia/arts/785509.Doc

原标题：单元测试用例编写入门实操
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.etx3og.asia/arts/274655.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.etx3og.asia/arts/829274.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.etx3og.asia/arts/944425.Doc

原标题：磁盘占满服务不可用清理方案
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.etx3og.asia/arts/507321.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.etx3og.asia/arts/577465.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.etx3og.asia/arts/302807.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.etx3og.asia/arts/933362.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.etx3og.asia/arts/641495.Doc

原标题：golang 数据库批量更新性能优化
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.etx3og.asia/arts/322882.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/642862.Doc

原标题：golang ip 限流黑名单实现方案
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.etx3og.asia/arts/414836.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/337091.Doc

原标题：golang github actions 多平台构建
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.etx3og.asia/arts/389555.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.etx3og.asia/arts/499566.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.etx3og.asia/arts/266340.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.etx3og.asia/arts/445514.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.etx3og.asia/arts/346794.Doc

原标题：入门实战：搭建简易静态网页项目
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.etx3og.asia/arts/212730.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.etx3og.asia/arts/953972.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.etx3og.asia/arts/671747.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.etx3og.asia/arts/236200.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.etx3og.asia/arts/788347.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.etx3og.asia/arts/727558.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.etx3og.asia/arts/883654.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.etx3og.asia/arts/459577.Doc

原标题：日志敏感信息脱敏泄露防护
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.etx3og.asia/arts/890728.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.etx3og.asia/arts/611061.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.etx3og.asia/arts/816868.Doc


二、踩坑排错｜Troubleshooting
原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.etx3og.asia/arts/199273.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.etx3og.asia/arts/062707.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.etx3og.asia/arts/822748.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.etx3og.asia/arts/094793.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.etx3og.asia/arts/341847.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.etx3og.asia/arts/995769.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.etx3og.asia/arts/078369.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.etx3og.asia/arts/966347.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.etx3og.asia/arts/074370.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.etx3og.asia/arts/932141.Doc

原标题：golang 数据库连接泄露排查
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.etx3og.asia/arts/538009.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.etx3og.asia/arts/015300.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.etx3og.asia/arts/404660.Doc

原标题：前端打包分包加载提速方案
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.etx3og.asia/arts/193841.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.etx3og.asia/arts/001373.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.etx3og.asia/arts/642838.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.etx3og.asia/arts/060818.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.etx3og.asia/arts/648714.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.etx3og.asia/arts/259851.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.etx3og.asia/arts/770625.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.etx3og.asia/arts/761046.Doc

原标题：代码格式化工具团队统一风格
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.etx3og.asia/arts/939677.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.etx3og.asia/arts/840997.Doc

原标题：golang 链路 traceId 透传中间件
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.etx3og.asia/arts/411531.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.etx3og.asia/arts/539214.Doc

原标题：golang redis 发布订阅简单示例
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.etx3og.asia/arts/979519.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.etx3og.asia/arts/189364.Doc

原标题：golang html 模板渲染简单示例
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.etx3og.asia/arts/736278.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.etx3og.asia/arts/565642.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.etx3og.asia/arts/238493.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.etx3og.asia/arts/919168.Doc

原标题：golang mongodb 索引优化查询速度
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.etx3og.asia/arts/123869.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.etx3og.asia/arts/880747.Doc

原标题：程序日志分级输出规范实践
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.etx3og.asia/arts/007106.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.etx3og.asia/arts/583503.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.etx3og.asia/arts/299702.Doc

原标题：golang gin 框架接口开发实战
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.etx3og.asia/arts/102191.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.etx3og.asia/arts/825541.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.etx3og.asia/arts/917104.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.etx3og.asia/arts/263940.Doc

三、实战开发｜Practice
原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.etx3og.asia/arts/607811.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.etx3og.asia/arts/989394.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.etx3og.asia/arts/595377.Doc

原标题：golang 数据库慢查询监控实现
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.etx3og.asia/arts/015539.Doc

原标题：项目语义化版本号规范管理
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.etx3og.asia/arts/417873.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.etx3og.asia/arts/416921.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.etx3og.asia/arts/688404.Doc

原标题：golang 系统设计短链接服务实现思路
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.etx3og.asia/arts/952039.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.etx3og.asia/arts/949772.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.etx3og.asia/arts/613282.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.etx3og.asia/arts/436857.Doc

原标题：golang mysql 存储过程简单使用
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.etx3og.asia/arts/481357.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.etx3og.asia/arts/073632.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.etx3og.asia/arts/865827.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.etx3og.asia/arts/955196.Doc

原标题：接口签名验签完整安全方案
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.etx3og.asia/arts/711394.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.etx3og.asia/arts/641430.Doc

原标题：golang 配置热更新不重启服务
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.etx3og.asia/arts/948324.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.etx3og.asia/arts/231361.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.etx3og.asia/arts/291400.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.etx3og.asia/arts/745660.Doc

原标题：分布式 ID 生成器高并发实现
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.etx3og.asia/arts/287433.Doc

原标题：golang http 请求重试封装工具
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.etx3og.asia/arts/360588.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.etx3og.asia/arts/970143.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.etx3og.asia/arts/642464.Doc

原标题：前端国际化多语言方案落地
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.etx3og.asia/arts/904416.Doc

原标题：本地数据库开发环境搭建指南
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.etx3og.asia/arts/145766.Doc

原标题：golang 分布式锁 redis 实现
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.etx3og.asia/arts/715440.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.etx3og.asia/arts/472771.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.etx3og.asia/arts/815037.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.etx3og.asia/arts/903257.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.etx3og.asia/arts/821034.Doc

原标题：golang mysql 连接泄漏检测方法
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.etx3og.asia/arts/695546.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.etx3og.asia/arts/398994.Doc

原标题：文件分片上传断点续传功能
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.etx3og.asia/arts/663220.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.etx3og.asia/arts/966208.Doc

原标题：入门实战：搭建简易静态网页项目
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.etx3og.asia/arts/684261.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.etx3og.asia/arts/205231.Doc

原标题：短信服务封装失败自动重试
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.etx3og.asia/arts/221143.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.etx3og.asia/arts/013275.Doc

四、架构设计｜Architecture
原标题：golang mock 单元测试编写技巧
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.etx3og.asia/arts/424440.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.etx3og.asia/arts/559137.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.etx3og.asia/arts/796815.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.etx3og.asia/arts/236957.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.etx3og.asia/arts/077240.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.etx3og.asia/arts/093101.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.etx3og.asia/arts/530594.Doc

原标题：golang html 模板渲染简单示例
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.etx3og.asia/arts/002763.Doc

原标题：接口签名验签完整安全方案
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.etx3og.asia/arts/480547.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.etx3og.asia/arts/013360.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/425107.Doc

原标题：golang kafka 死信队列业务落地
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.etx3og.asia/arts/451097.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.etx3og.asia/arts/239760.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.etx3og.asia/arts/748040.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.etx3og.asia/arts/801356.Doc

原标题：JWT 工具封装令牌刷新过期
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.etx3og.asia/arts/026055.Doc

原标题：golang 接口请求日志记录中间件
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.etx3og.asia/arts/181480.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.etx3og.asia/arts/607328.Doc

?
