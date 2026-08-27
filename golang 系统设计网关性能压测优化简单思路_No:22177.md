最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计网关性能压测优化简单思路
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.fidyip.asia/blog/6394279.sHtMl

原标题：golang 数据库连接泄露排查
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.fidyip.asia/blog/3803670.sHtMl

原标题：设计思考：分布式ID系统架构选型对比
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.fidyip.asia/blog/5717232.sHtMl

原标题：实践：接口参数自动校验业务落地实践
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.fidyip.asia/blog/6791583.sHtMl

原标题：golang 系统设计 webhook 回调接口设计要点
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.fidyip.asia/blog/5370287.sHtMl

原标题：golang 系统设计大表结构变更不停机方案
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.fidyip.asia/blog/2089461.sHtMl

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.fidyip.asia/blog/4855090.sHtMl

原标题：Practice：实现请求重试组件支持退避策略
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.fidyip.asia/blog/3514148.sHtMl

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.fidyip.asia/blog/2968997.sHtMl

原标题：方案对比：单体、微服务、模块化单体取舍
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.fidyip.asia/blog/3502770.sHtMl

原标题：golang mysql 长连接短连接对比
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.fidyip.asia/blog/6570946.sHtMl

原标题：golang 系统设计用户签到统计方案
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.fidyip.asia/blog/2609241.sHtMl

原标题：安全实践：最小权限原则数据库账号管控
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.fidyip.asia/blog/4939200.sHtMl

原标题：Redis 热点 key 拆分降低集群压力
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.fidyip.asia/blog/3102070.sHtMl

原标题：CI 构建缓存加速编译速度
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.fidyip.asia/blog/4145181.sHtMl

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.fidyip.asia/blog/7420614.sHtMl

原标题：坑点：环境配置写死代码，上线忘记修改
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.fidyip.asia/blog/5694201.sHtMl

原标题：golang k8s 节点污点容忍度配置
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.fidyip.asia/blog/2706755.sHtMl

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.fidyip.asia/blog/0376462.sHtMl

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.fidyip.asia/blog/4913957.sHtMl

原标题：避坑：定时任务重复执行带来业务脏数据
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.fidyip.asia/blog/6149237.sHtMl

原标题：golang github actions 多平台构建
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.fidyip.asia/blog/4653347.sHtMl

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.fidyip.asia/blog/7480098.sHtMl

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.fidyip.asia/blog/9673313.sHtMl

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.fidyip.asia/blog/0706092.sHtMl

原标题：运维笔记：线上服务健康检查脚本编写
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.fidyip.asia/blog/7100661.sHtMl

原标题：坑点：环境配置写死代码，上线忘记修改
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.fidyip.asia/blog/4254500.sHtMl

原标题：golang 系统设计热点数据缓存处理
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.fidyip.asia/blog/1751761.sHtMl

原标题：请求重试组件退避策略实现
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.fidyip.asia/blog/7035313.sHtMl

原标题：HelloCI：理解持续集成基础工作流程
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.fidyip.asia/blog/0739463.sHtMl

原标题：webpack chunk 分包策略详解
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.fidyip.asia/blog/3478053.sHtMl

原标题：golang lru 缓存淘汰算法编写
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.fidyip.asia/blog/0900393.sHtMl

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.fidyip.asia/blog/3096097.sHtMl

原标题：golang 系统设计 rest 状态码合理使用指南
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.fidyip.asia/blog/2696780.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.fidyip.asia/blog/6682212.sHtMl

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.fidyip.asia/blog/2386374.sHtMl

原标题：Git 子模块更新代码不全修复
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.fidyip.asia/blog/4521438.sHtMl

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.fidyip.asia/blog/8394415.sHtMl

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.fidyip.asia/blog/9211427.sHtMl

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.fidyip.asia/blog/8236346.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 api 网关核心能力完整梳理
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.fidyip.asia/blog/3009580.sHtMl

原标题：Practice：实现异步任务结果查询回调实践
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.fidyip.asia/blog/3839682.sHtMl

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.fidyip.asia/blog/8342629.sHtMl

原标题：多实例部署 Session 共享方案
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.fidyip.asia/blog/5469387.sHtMl

原标题：golang 系统设计指标聚合计算存储选型对比
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.fidyip.asia/blog/6406891.sHtMl

原标题：零基础理解JSON、XML数据格式处理
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.fidyip.asia/blog/7237204.sHtMl

原标题：golang html 模板渲染简单示例
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.fidyip.asia/blog/4936275.sHtMl

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.fidyip.asia/blog/7812682.sHtMl

原标题：Architecture：大文件上传下载系统架构设计
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.fidyip.asia/blog/0563210.sHtMl

原标题：Nginx 透传真实客户端 IP 配置
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.fidyip.asia/blog/8545495.sHtMl

原标题：golang mongodb 文档结构设计原则
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.fidyip.asia/blog/0295458.sHtMl

原标题：定时任务周期调度 demo 开发
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.fidyip.asia/blog/5616157.sHtMl

原标题：golang k8s job 一次性任务执行
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.fidyip.asia/blog/2829686.sHtMl

原标题：golang 表单文件大小限制配置
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.fidyip.asia/blog/6614091.sHtMl

原标题：golang docker 容器资源限制设置
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://book.fidyip.asia/blog/3212921.sHtMl

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.fidyip.asia/blog/9770837.sHtMl

原标题：golang 系统设计限流服务架构讲解
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.fidyip.asia/blog/4306933.sHtMl

原标题：golang 协程 panic 捕获防止崩溃
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.fidyip.asia/blog/7279387.sHtMl

原标题：踩坑：大事务引发数据库连接池耗尽
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.fidyip.asia/blog/5188493.sHtMl

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.fidyip.asia/blog/2096203.sHtMl

原标题：Practice：实现业务唯一流水号生成组件实践
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.fidyip.asia/blog/4300417.sHtMl

原标题：golang 系统设计消息可靠性投递实现
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.fidyip.asia/blog/6139489.sHtMl

原标题：golang redis 位图用户签到统计
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.fidyip.asia/blog/6247215.sHtMl

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.fidyip.asia/blog/3617610.sHtMl

原标题：nodejs redis 缓存业务实战
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.fidyip.asia/blog/6215347.sHtMl

原标题：golang grafana 监控面板简单配置
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.fidyip.asia/blog/0795899.sHtMl

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.fidyip.asia/blog/1317029.sHtMl

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.fidyip.asia/blog/8600340.sHtMl

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.fidyip.asia/blog/0667040.sHtMl

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.fidyip.asia/blog/1921862.sHtMl

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.fidyip.asia/blog/8068158.sHtMl

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.fidyip.asia/blog/0006376.sHtMl

原标题：golang k8s 日志收集 efk 简单架构
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.fidyip.asia/blog/5030703.sHtMl

原标题：入门实践：项目配置文件多环境管理方案
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.fidyip.asia/blog/2012650.sHtMl

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.fidyip.asia/blog/9589702.sHtMl

原标题：项目目录结构规范化最佳实践
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.fidyip.asia/blog/5073359.sHtMl

原标题：前端水印防信息泄露实现
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.fidyip.asia/blog/6608025.sHtMl

原标题：golang 系统设计热点数据缓存处理
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.fidyip.asia/blog/7725426.sHtMl

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.fidyip.asia/blog/0983570.sHtMl

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.fidyip.asia/blog/9167754.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.fidyip.asia/blog/7384776.sHtMl

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.fidyip.asia/blog/3617208.sHtMl

原标题：golang 优雅停机服务关闭实现
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.fidyip.asia/blog/0652709.sHtMl

原标题：安全实践：备份文件访问权限安全管控
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.fidyip.asia/blog/7872882.sHtMl

原标题：后端大文件分片上传接口开发
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.fidyip.asia/blog/5497194.sHtMl

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.fidyip.asia/blog/8204223.sHtMl

原标题：实战：Docker资源监控查看容器状态实操
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.fidyip.asia/blog/5420914.sHtMl

原标题：快速上手简单性能监控指标查看
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.fidyip.asia/blog/1310727.sHtMl

原标题：golang docker 私有仓库搭建使用
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.fidyip.asia/blog/5534206.sHtMl

原标题：HelloTest：理解集成测试基础编写思路
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.fidyip.asia/blog/7570426.sHtMl

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.fidyip.asia/blog/9496256.sHtMl

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.fidyip.asia/blog/1693898.sHtMl

原标题：分布式任务调度集群原型开发
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.fidyip.asia/blog/9688268.sHtMl

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.fidyip.asia/blog/0100206.sHtMl

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.fidyip.asia/blog/5477533.sHtMl

原标题：Performance：后端接口性能优化完整分析流程
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.fidyip.asia/blog/2728383.sHtMl

原标题：提交第一个开源 PR 完整流程
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.fidyip.asia/blog/4396007.sHtMl

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.fidyip.asia/blog/9062729.sHtMl

原标题：读懂开源项目 README 实用技巧
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.fidyip.asia/blog/3579009.sHtMl

原标题：数据库事务 ACID 原理讲解
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.fidyip.asia/blog/2539249.sHtMl

原标题：版本升级服务启动失败处理
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.fidyip.asia/blog/8367333.sHtMl

原标题：数据库读写分离性能优化
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.fidyip.asia/blog/8235431.sHtMl

原标题：nodejs 内存溢出问题排查修复
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.fidyip.asia/blog/0240635.sHtMl

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.fidyip.asia/blog/7538091.sHtMl

原标题：CI 流水线构建失败日志排查
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.fidyip.asia/blog/6262419.sHtMl

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.fidyip.asia/blog/7440805.sHtMl

原标题：容器内存扩容 OOM 被杀死修复
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.fidyip.asia/blog/0524915.sHtMl

原标题：golang 系统设计 mq 消息积压解决方案
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.fidyip.asia/blog/2579885.sHtMl

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.fidyip.asia/blog/1108860.sHtMl

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.fidyip.asia/blog/4249944.sHtMl

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.fidyip.asia/blog/6596448.sHtMl

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.fidyip.asia/blog/5528683.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.fidyip.asia/blog/2548567.sHtMl

原标题：golang 系统设计定时任务分布式锁
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.fidyip.asia/blog/5949409.sHtMl

原标题：golang git 提交信息规范校验
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.fidyip.asia/blog/4217481.sHtMl

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.fidyip.asia/blog/7494937.sHtMl

原标题：分布式 ID 生成器高并发实现
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.fidyip.asia/blog/4360262.sHtMl

原标题：设计思考：分布式会话架构选型对比
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.fidyip.asia/blog/8101897.sHtMl

原标题：安全复盘：定时任务权限过大风险管控
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.fidyip.asia/blog/8244533.sHtMl

原标题：接口幂等性防重复请求实现
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.fidyip.asia/blog/0581202.sHtMl

四、架构设计｜Architecture
原标题：GraphQL 接口查询优化实操
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.fidyip.asia/blog/5381497.sHtMl

原标题：golang 系统设计容器健康检查设计思路
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://book.fidyip.asia/blog/3440622.sHtMl

原标题：golang 系统设计网络超时故障排查思路
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.fidyip.asia/blog/3912385.sHtMl

原标题：golang 系统设计错误码体系完整设计
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.fidyip.asia/blog/9412225.sHtMl

原标题：golang 数据库连接泄露排查
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.fidyip.asia/blog/3290100.sHtMl

原标题：复盘总结：数据库迁移升级风险评估清单
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.fidyip.asia/blog/0214850.sHtMl

原标题：开发记录：业务错误告警邮件通知组件实践
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.fidyip.asia/blog/3597138.sHtMl

原标题：消息队列重复消费业务处理
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.fidyip.asia/blog/8832021.sHtMl

原标题：golang 系统设计多级缓存架构落地
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.fidyip.asia/blog/3850560.sHtMl

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.fidyip.asia/blog/8902366.sHtMl

原标题：Hands‑on：简易代理服务器开发实践
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.fidyip.asia/blog/4647030.sHtMl

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.fidyip.asia/blog/0056069.sHtMl

原标题：从零搭建简单的健康检查接口示例
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.fidyip.asia/blog/0307235.sHtMl

原标题：版本升级服务启动失败处理
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.fidyip.asia/blog/3899376.sHtMl

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.fidyip.asia/blog/0250022.sHtMl

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.fidyip.asia/blog/9062949.sHtMl

原标题：golang 系统设计数据库慢请求排查流程
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.fidyip.asia/blog/8971490.sHtMl

原标题：Hands‑on：简易短链接服务完整开发实践
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.fidyip.asia/blog/0533791.sHtMl

?
