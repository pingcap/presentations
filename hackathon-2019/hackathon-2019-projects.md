
## TiDB Hackathon 2019 完整参赛项目展示

| 序号 | 团队名称 | 项目名称 | 项目简介 | GitHub Repo |
|:----|:-----|:--------|:-----------------------------|:-----------------|
| 1 | 攀登者 | SQLAdvisor | 对 SQL 提供合适的索引优化建议。 | [https://github.com/longxuegang/SQLAdvisor-TiDB.git](https://github.com/longxuegang/SQLAdvisor-TiDB.git) |
| 2 | IPZZ（CTO 特别奖） | TiSearch | Fulltext Search with SQL. | http://github.com/redis-force/parser http://github.com/redis-force/tidb http://github.com/redis-force/tisearch  http://github.com/redis-force/tisearch-fe |
| 3 | 朴实无华且枯燥 | 在线更改集群配置 | 做了一点微小的工作。 | [https://github.com/plainboring](https://github.com/plainboring) |
| 4 | 强特征与浅规则 | TiNet | AI 结合弹性热数据。 | [https://github.com/nolouch/TiNet](https://github.com/nolouch/TiNet) |
| 5 | sut-birds | TiM | TiM - TiDB 多集群运维工具，解决 TiDB 多集群运维以及升级操作复杂易出错等问题, 提高 TiDB 运维人员的效率。 | [https://github.com/tidbops/tim](https://github.com/tidbops/tim) |
| 6 | 柠檬围绕着我 | unistore 中的冷热数据分离 | 使用 S3 存储冷数据并提供读取。 | [https://github.com/bobotu/badger/tree/hackathon](https://github.com/bobotu/badger/tree/hackathon) |
| 7 | TiNewbee | TiKV cluster on Kubernetes | K8s 上实现去中心化 TiKV 集群。 | [https://github.com/tennix/pd/tree/hackathon](https://github.com/tennix/pd/tree/hackathon) |
| 8 | DIstributedIO | 基于 Spanner 的事务模型实现 | 在 TiKV 中实现 Spanner 论文中的事务模型，从模型上成倍的优化了分布式事务的性能。 | [http://github.com/distributedio/tikv, spanner 分支](http://github.com/distributedio/tikv) |
| 9 | .*（二等奖） | TiDB 跨数据中心的解决方案 | 我们为 TiDB 引入了 DC 的概念，并实现了跨数据中心的 follower replication 与读写优化。 | https://github.com/TennyZhuang/tidb  https://github.com/TennyZhuang/tikv  https://github.com/TennyZhuang/pd  https://github.com/TennyZhuang/kvproto |
| 10 | 代码有毒 | SQL 过滤与优化中间件 | 旨在解决用户的SQL 质量参差不齐，迁移和使用过程中，引发集群资源紧的问题。 | [https://github.com/guzhenping/Code-with-poison](https://github.com/guzhenping/Code-with-poison) |
| 11 | ZZZZ | Quotas in TiDB | 基于集群资源配额的多租户隔离实现。 | [https://github.com/baiyuqing](https://github.com/baiyuqing) |
| 12 | 鹰眼小队 | TiDBSlowSQL | A Real time , High performance, Multi-dimension Slow Query Analysis System for TiDB. | [https://github.com/ruiaylin/tidbslowsql](https://github.com/ruiaylin/tidbslowsql) |
| 13 | 祥瑞（最佳创意奖） | sql-spider | 在 SQL 空间中通过多种策略爬取合法 Query 进行测试。 | [https://github.com/zyguan/sql-spider](https://github.com/zyguan/sql-spider) |
| 14 | VIDB（最佳潜力奖） | Self-Driving TiDB | 根据历史负载统计情况，预测未来不同数据区间的访问模式，在空闲时间段提前对不同区间的数据从不同维度来进行调整以适应未来的访问模式。 | 冷热分离模块：https://github.com/pingcap/pd/pull/1848  数据整理模块：https://github.com/tikv/tikv/compare/master...wujy-cs:hackthon?expand=1  https://github.com/pingcap/pd/compare/master...wujy-cs:hackthon?expand=1  副本弹性伸缩模块：https://github.com/pingcap/pd/compare/master...fredchenbj:fredchenbj/add-replica-follower-read?expand=1  https://github.com/pingcap/tidb/compare/master...fredchenbj:fredchenbj/default_replica_read?expand=1   离线预测模块：https://github.com/Jing118/pdpd |
| 15 | Better战队（最佳贡献奖） | 基于 Binlog 的 Fast-PITR | Binlog 的逐级 merge，以最小的代价实现快速 PITR。 | [https://github.com/lvleiice/Better-PITR.git](https://github.com/lvleiice/Better-PITR.git) |
| 16 | 为什么代码总是跑不队 | io-uring speed the rocksdb & tikv | 使用 io-uring 异步 IO 提升 RocksDB 和 TiKV 性能。| [https://github.com/PingCAP-Hackthon2019-Team17](https://github.com/PingCAP-Hackthon2019-Team17) |
| 17 | 放课后茶会 | continuous perf:持续的 profile 与展示 | 提供一个前端为 TiKV 进行持续的 profile，并对调用栈的技术信息进行展示。与静态的、片段的 profile 相比，它能够选择任意时间段的 profile，方便开发者对它们进行分析、挖掘。 | [https://github.com/Hexilee/tikv/rsperftools](https://github.com/Hexilee/tikv/rsperftools) |
| 18 | root12345678 | TiPresto | 结合 TiKV 的分布式存储和 Coprocessor 计算下推能力，以及 Presto 的分布式 SQL Query 能力，实现了 TiDB 生态的 MPP 架构，解决了 TiDB 生态目前无法解决"中等规模快速查询"的问题。 | [https://github.com/marsishandsome/presto/tree/feature/tidb-hackathon-2019](https://github.com/marsishandsome/presto/tree/feature/tidb-hackathon-2019) |
| 19 | Juicy | TIFS | TiFS 数基于 TiKV 和 juicefs 实现的共享 posix 文件系统，为 tiflash 提供持久化的共享存储，以便接下来实现弹性的 Hatp 架构。 | - |
| 20 | 鸽子汤 | 基于 TiKV 的文件系统 | A block device in user space for Linux in Golang. | [https://github.com/jjyr/buse-go](https://github.com/jjyr/buse-go)  |
| 21 | TQL | TiLighting | {fast, correct}- chose two | [https://github.com/zhexuany/TiLightning](https://github.com/zhexuany/TiLightning)  |
| 22 | 东北二人转...... | etcd on tikv | Terraform 是目前最流行的云上资源编排工具，用于管理云上基础设施。我们扩展了 terraform 的功能，支持 tikv as a state backend，使 tikv 成为继 etcd，consul 之外的第三种通用型 kv 状态存储，不用再引入额外的组件。
结合 tidb-operator，可以在大多数云厂商上提供 all in TiDB Stack 的能力。 | [https://github.com/cloud-insight/terraform](https://github.com/cloud-insight/terraform) |
| 23 | ti-cool（二等奖） | tidb-wasm | 将 TiDB 运行在你的浏览器里。 | [https://github.com/lucklove/tidb-wasm](https://github.com/lucklove/tidb-wasm) |
| 24 | 老鸽，稳 | 钛合金， TiDB 扩展方案 | Ti-alloy 基于了 tidb-plugin-framewok。为 TiDB 增加大量用户定制化的功能扩展方案。当前版本已完成和 MySQL 接口相似的 UDF 定义，轻松为 TiDB 添加 UDF。FDW (Foreign Data Wrapper) 原型完成 ，支持读/写操作。参考 Prometheus 的发展经历，实现了 Scan 和 SelectionScan 两种 Scan 接口相应功能已经添加测试。 | [https://github.com/WPH95/tidb/commits/hackathon-2019](https://github.com/WPH95/tidb/commits/hackathon-2019) |
| 25 | exciting（三等奖） | TiExciting | TiExciting 为 TiDB 集群提供图形化部署及运维， 尽可能做到易用、友好、高效。 | https://github.com/breeswish/TiExciting  https://github.com/breeswish/TiExcitingUI |
| 26 | Ti-improve | TiDB 下一代测试 | TiDB 测试革命，通过很方便的测试方式方法来提升 TiDB 的稳定性、性能、测试效率和社区。 | https://github.com/you06/tidb  https://github.com/you06/sqlsmith-go |
| 27 | 我和我的 SQL（三等奖） | 基于路径统计的 sql bug root cause 分析 | 基于路径统计以及代码生成的方式进行 sqlfuzz 和 sql debug。 | [https://github.com/fuzzdebugplatform/fuzz_debug_platform](https://github.com/fuzzdebugplatform/fuzz_debug_platform) |
| 28 | 逊馁（一等奖） | Unified Thread Pool | 在 TiKV 中使用一个统一的自适应线程池处理读请求，能够显著提升性能，并可预测性地限制大查询对小请求的干扰。 | https://github.com/sticnarf/adaptive-thread-pool   https://github.com/sticnarf/tikv/tree/hackathon   https://github.com/sticnarf/tidb/tree/hackathon   https://github.com/waynexia/texn   https://github.com/sticnarf/kvproto/tree/hackathon |
| 29 | Ti3 | 支持 select into 语句 | 支持 select ... into (outfile | dumpfile | variables) 等功能。 | https://github.com/lauhg/parser/tree/ti3-select-into   https://github.com/tr1um7h/tidb/tree/ti3-select-into |
| 30 | 吃火锅小分队 | 利用 Lookahead Information Passing 提速 Hash Join | 对 Hash Join 的 inner 表建立 bloom filter，用以在 outer 表发往 TiDB 前预先过滤其中的数据，减少网络传输的数据量。 | https://github.com/time-and-fate/tidb
https://github.com/time-and-fate/tipb |
| 31 | TPC-YL | 基于动态采样的行数估计 | 在 SQL 查询优化阶段对目标表进行快速样本采集，估算整张表满足查询条件的行数。该方法可以弥补统计信息延迟或缺失情况下的行数估计，同时减少 Column isolation 及列的关联性对现有行数估计方法造成的误差，提高查询性能。同时动态采集的样本有助于在后期开发中用于实现模糊查询及复杂表达式的行数估计，甚至实现近似查询。 | [https://github.com/PiotrNewt/tidb/tree/hackthon_dynamic_sampling](https://github.com/PiotrNewt/tidb/tree/hackthon_dynamic_sampling) |
| 32 | 任我行 | 基于 TiDB 的大数据即服务平台 | 开发 dremio 到 TiDB 的插件，一站式满足实时和海量离线数据的即时分析。实时分析请求的 agg 和 filter 灵活 push down 到 TiDB 集群。100% 的非实时 AP 请求，高性能计算，避免 TiDB 的 AP 计算过载。 | [https://github.com/jackchongs/dremio-tidb](https://github.com/jackchongs/dremio-tidb) |
| 33 | TiBoys | TBSSQL 2.0-- One command inspection, real time diagnosis. | TBSSQL 2.0 扩展了 TiDB 对于时序类型数据的 Streaming 语意支持(包括 TiDB cluster log / TiDB prometheus metrics / TiDB TiKV pprof metrics )， 实现 One Command 自动巡检，实时诊断分析功能。 | https://github.com/qiuyesuifeng/tidb/tree/tiboys/tbssql2.0   https://github.com/qiuyesuifeng/tikv/tree/tiboys/tbssql2.0  https://github.com/qiuyesuifeng/pd/tree/tiboys/tbssql2.0   https://github.com/qiuyesuifeng/parser/tree/tiboys/tbssql2.0   https://github.com/qiuyesuifeng/kvproto/tree/tiboys/tbssql2.0   https://github.com/qiuyesuifeng/tidb-ansible/tree/tiboys/tbssql2.0 |
| 34 | 一起吃鸡 | 高可用的 TiDB 客户端 | Golang 的 TiDB 客户端，基于 go-sql-driver/mysql 封装，支持以下特性：1. 多 TiDB 连接，自动切换故障 TiDB；2. TiDB 负载均衡。 | https://github.com/sicojuy/ticli |
| 35 | Hackathon Fix Typo Team | PD-Web | PD-Web 是对 PD Server Restful API 的可视化实现，目的是降低排除故障成本，增强 PD API 的易用性。用户界面使用卡片的形式展示了 TiKV 节点，除了能够查看节点的基本信息和 Region 实时状态以外，还能对 Region 和 Store 进行手动调度。 | [https://github.com/HFTT/pd-web](https://github.com/HFTT/pd-web) |
| 36 | Sight for Legend | 统计 TiDB 各个 Region 数据冷热程度和操作规律 | 本项目实现了一个对于 TiDB 各个 Region 数据访问情况的监控器，能够把在不同时间段内的对 TiDB 的数据访问情况以热图的形式展示出来。 | [https://github.com/HunDunDM/key-visual](https://github.com/HunDunDM/key-visual) |
| 37 | 做个人吧（三等奖） | Manage many as one with SQL | 用 SQL 查询集群所有节点的信息；用 SQL 修改集群所有节点的配置。 | https://github.com/iosmanthus/tikv/tree/mem-table-scan   https://github.com/gzptgo/pd/tree/stat_api   https://github.com/crazycs520/tidb/tree/hackathon |
