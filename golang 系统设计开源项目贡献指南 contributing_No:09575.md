最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目贡献指南 contributing
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.zyjh0y.asia/blog/379328.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.zyjh0y.asia/blog/182322.Doc

原标题：缓存穿透防护保护数据库
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.zyjh0y.asia/blog/307242.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.zyjh0y.asia/blog/953542.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.zyjh0y.asia/blog/187409.Doc

原标题：golang github actions 多平台构建
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.zyjh0y.asia/blog/002343.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.zyjh0y.asia/blog/392105.Doc

原标题：开发生产环境资源路径统一
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.zyjh0y.asia/blog/733736.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.zyjh0y.asia/blog/774001.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.zyjh0y.asia/blog/811355.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.zyjh0y.asia/blog/175535.Doc

原标题：端口占用访问失败排查方案
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.zyjh0y.asia/blog/230973.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.zyjh0y.asia/blog/363521.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.zyjh0y.asia/blog/382677.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.zyjh0y.asia/blog/540098.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.zyjh0y.asia/blog/558919.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.zyjh0y.asia/blog/282940.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.zyjh0y.asia/blog/917728.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.zyjh0y.asia/blog/521021.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.zyjh0y.asia/blog/768439.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.zyjh0y.asia/blog/283468.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.zyjh0y.asia/blog/369727.Doc

原标题：DNS 解析异常第三方调用故障
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.zyjh0y.asia/blog/335725.Doc

原标题：日志驱动异常日志不输出修复
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.zyjh0y.asia/blog/217824.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.zyjh0y.asia/blog/306711.Doc

原标题：CI 构建缓存加速编译速度
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.zyjh0y.asia/blog/218538.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.zyjh0y.asia/blog/706686.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.zyjh0y.asia/blog/004431.Doc

原标题：golang docker 私有仓库搭建使用
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.zyjh0y.asia/blog/449439.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.zyjh0y.asia/blog/844765.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.zyjh0y.asia/blog/639129.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.zyjh0y.asia/blog/220973.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.zyjh0y.asia/blog/415661.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.zyjh0y.asia/blog/773163.Doc

原标题：golang 消息死信处理业务逻辑
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.zyjh0y.asia/blog/853987.Doc

原标题：golang es 高亮搜索结果实现方案
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.zyjh0y.asia/blog/880914.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.zyjh0y.asia/blog/526331.Doc

原标题：webpack chunk 分包策略详解
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://book.zyjh0y.asia/blog/314273.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.zyjh0y.asia/blog/217493.Doc

原标题：golang etcd 配置中心简单使用
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.zyjh0y.asia/blog/392867.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.zyjh0y.asia/blog/527324.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.zyjh0y.asia/blog/778577.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.zyjh0y.asia/blog/598231.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/595387.Doc

原标题：golang http 服务性能优化调参
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.zyjh0y.asia/blog/629689.Doc

原标题：golang redis bitmap 位图统计实现
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.zyjh0y.asia/blog/618975.Doc

原标题：Security：服务器最小权限账号运维实践
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.zyjh0y.asia/blog/062360.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.zyjh0y.asia/blog/061955.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.zyjh0y.asia/blog/049715.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.zyjh0y.asia/blog/916479.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.zyjh0y.asia/blog/876836.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.zyjh0y.asia/blog/265141.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.zyjh0y.asia/blog/096725.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.zyjh0y.asia/blog/657072.Doc

原标题：golang defer panic 异常处理
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.zyjh0y.asia/blog/963423.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.zyjh0y.asia/blog/411651.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.zyjh0y.asia/blog/856738.Doc

原标题：快速上手调试工具定位简单代码错误
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.zyjh0y.asia/blog/045925.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.zyjh0y.asia/blog/117613.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.zyjh0y.asia/blog/944567.Doc

原标题：golang gin 中间件执行顺序讲解
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.zyjh0y.asia/blog/905845.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.zyjh0y.asia/blog/538664.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.zyjh0y.asia/blog/792867.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.zyjh0y.asia/blog/222092.Doc

原标题：文件锁正确使用避免死锁
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.zyjh0y.asia/blog/824611.Doc

原标题：请求工具封装统一异常处理
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.zyjh0y.asia/blog/047203.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.zyjh0y.asia/blog/816135.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.zyjh0y.asia/blog/881280.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.zyjh0y.asia/blog/147556.Doc

原标题：JWT 令牌过期异常处理
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.zyjh0y.asia/blog/611587.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.zyjh0y.asia/blog/955606.Doc

原标题：golang k8s ingress 路由域名转发
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.zyjh0y.asia/blog/210940.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.zyjh0y.asia/blog/449039.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.zyjh0y.asia/blog/418212.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.zyjh0y.asia/blog/110578.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.zyjh0y.asia/blog/378431.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.zyjh0y.asia/blog/612701.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.zyjh0y.asia/blog/255750.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.zyjh0y.asia/blog/410808.Doc

原标题：日志切割配置防止日志丢失
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.zyjh0y.asia/blog/620426.Doc

三、实战开发｜Practice
原标题：提交第一个开源 PR 完整流程
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.zyjh0y.asia/blog/582615.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.zyjh0y.asia/blog/007242.Doc

原标题：任务执行锁防止并发重复调度
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.zyjh0y.asia/blog/289263.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.zyjh0y.asia/blog/670486.Doc

原标题：golang mysql 字符集排序规则设置
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.zyjh0y.asia/blog/847546.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.zyjh0y.asia/blog/104871.Doc

原标题：短信服务封装失败自动重试
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.zyjh0y.asia/blog/069860.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.zyjh0y.asia/blog/666508.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.zyjh0y.asia/blog/445280.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.zyjh0y.asia/blog/519466.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.zyjh0y.asia/blog/256409.Doc

原标题：前端打包分包加载提速方案
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.zyjh0y.asia/blog/639927.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.zyjh0y.asia/blog/928327.Doc

原标题：nodejs redis 缓存业务实战
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.zyjh0y.asia/blog/913764.Doc

原标题：golang redis 发布订阅简单示例
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.zyjh0y.asia/blog/032257.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.zyjh0y.asia/blog/673784.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.zyjh0y.asia/blog/651278.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.zyjh0y.asia/blog/959098.Doc

原标题：golang 项目环境变量加载方案
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.zyjh0y.asia/blog/214342.Doc

原标题：HTTP 状态码请求头完整梳理
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.zyjh0y.asia/blog/776024.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.zyjh0y.asia/blog/671245.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.zyjh0y.asia/blog/127208.Doc

原标题：golang 系统设计防爬虫简单策略
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.zyjh0y.asia/blog/156168.Doc

原标题：golang 分布式上下文传递方案
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.zyjh0y.asia/blog/307709.Doc

原标题：不必要字符转义关闭业务异常
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.zyjh0y.asia/blog/445215.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.zyjh0y.asia/blog/149057.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.zyjh0y.asia/blog/339940.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.zyjh0y.asia/blog/706868.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.zyjh0y.asia/blog/581650.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.zyjh0y.asia/blog/278401.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.zyjh0y.asia/blog/361724.Doc

原标题：API 大版本不兼容平滑迁移
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.zyjh0y.asia/blog/269876.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.zyjh0y.asia/blog/716449.Doc

原标题：golang 互斥锁读写锁并发安全
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.zyjh0y.asia/blog/410207.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.zyjh0y.asia/blog/584159.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.zyjh0y.asia/blog/604187.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.zyjh0y.asia/blog/082233.Doc

原标题：golang redis 限流几种实现方案
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.zyjh0y.asia/blog/599941.Doc

原标题：实战：对象存储断点续传下载实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.zyjh0y.asia/blog/457922.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.zyjh0y.asia/blog/904080.Doc

四、架构设计｜Architecture
原标题：浏览器缓存强制刷新方案
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.zyjh0y.asia/blog/626021.Doc

原标题：依赖安装失败全方位排错
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.zyjh0y.asia/blog/804901.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.zyjh0y.asia/blog/377765.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.zyjh0y.asia/blog/370254.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.zyjh0y.asia/blog/388195.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.zyjh0y.asia/blog/190669.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.zyjh0y.asia/blog/711870.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.zyjh0y.asia/blog/190030.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.zyjh0y.asia/blog/595433.Doc

原标题：进程线程并发基础概念讲解
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.zyjh0y.asia/blog/824558.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.zyjh0y.asia/blog/958144.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.zyjh0y.asia/blog/979179.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.zyjh0y.asia/blog/241327.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.zyjh0y.asia/blog/675003.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.zyjh0y.asia/blog/155092.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://book.zyjh0y.asia/blog/342017.Doc

原标题：nodejs 流处理大文件不占内存
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.zyjh0y.asia/blog/235227.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.zyjh0y.asia/blog/087646.Doc

?
