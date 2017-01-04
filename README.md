# sabcf
Stream and batch computing framework
一、总体需求

- 高性能
- 流式计算
- 批量计算
- 数据来源
    - 上游算子
    - 流式传输引擎
        - Kafka
        - Scribe
    - 数据库
    - dfs
    - 网络抓取
        - 普通抓取
        - 带userinfo抓取
- 数据写出
    - 下游算子
    - dump
        - dfs
        - db
            - mysql
            - redis
            - elasticsearch
            - ...
        - kafka
- 配置热加载
- 对接资源调度系统
    - Yarn
    - 结合Docker
    - 特殊资源调度系统
- 性能分析&定位
    - trace_id
    - cost_time
    - 数据裂变
    - ...
- 时间窗
- 基础功能组件
    - 数据聚合
    - trace
    - 数据解析
- 不丢不重
- 自动调整并发度

二、设计实现
三、开发排期
