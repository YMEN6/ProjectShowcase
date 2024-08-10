# README

### 版本说明

| 时间       | 修订版本 | 说明                       |
| ---------- | -------- | -------------------------- |
| 2024/06/13 | 0.10     | 针对当前简历项目进行初始化 |
| 2024/08/10 | 0.11     | 简单补充近期项目           |



### 项目说明

[**容器轻量执行框架 LitePodOpsFramework**](https://github.com/YMEN6/ProjectShowcase/blob/main/LitePodOps.md)

LitePodOpsFramework为严格资源配额POD提供轻量、无干扰的操作下发通道。框架通过读写拆分，结合CROUP、Namespace、ReNice、分批平缓等方式，确保操作全程轻量无干扰，避免资源竞争。同时，框架通过多级白名单、串并行调度控制、熔断等手段确保风险可控。



##### [微型仓储管理系统 MWMS](https://github.com/YMEN6/ProjectShowcase/blob/main/MicroWarehouseManagementSystem.md)

MWMS是一款面向有限计算资源的微型仓储管理系统，适用于小型仓储环境，提供库存管理、订单管理、库存跟踪和订单报告等功能；



##### [任务调度平台 AirflowPlus](https://github.com/YMEN6/ProjectShowcase/blob/main/AirflowPlus.md)

AirflowPlus基于开源项目Apache-Airflow进行二次开发，针对高度并行化场景，对调度性能进行优化以克服原生项目的性能瓶颈。



##### [交易运维平台 TradingOpSystem](https://github.com/YMEN6/ProjectShowcase/blob/main/TradingOpSystem.md)

TradingOpSystem通过抽象多种网络连接方式为统一接口，并构建网络连接池和链路聚合技术，解决了高频量化交易系统中的网络连接复杂、运维困难、带宽有限和稳定性低的问题，适用于高频交易系统、金融数据中心和复杂网络环境下的运维管理。

