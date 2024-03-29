# Starfish
metadata map

## 元数据管理 Roadmap 0.1

1.元数据定义

* 元模型管理 
- [ ] 模型类型和实体实现，转换，验证     
- [ ] 模型和数据库交互
- [ ] 元数据API接口                    2022-02-25
- [ ] 元数据模型和实例版本树
- [ ] 支持JSON类型定义和验证（json-schema）(待定)

类型和实体实现方案：类型和实体 使用 Java类和对象进行描述，自动生成Java类作为类型，约束实例。

* DateSet元模型定义

- [ ] 整理现有元数据管理系统定义的元数据模型
- [ ] hive 元数据定义
- [ ] pulsar 元数据定义

- [ ] 多数据源元数据定义（优先级低）

* Process元模型定义

- [ ] 调度元数据定义？？？

2.元数据采集

* 消息系统插件化
- [x] 消息系统插件化, 消费者，生产者
- [ ] 消息系统接收元数据，存储元数据
- [ ] 消息系统生产元数据

* scheduler插件化
- [ ] 集成 dolphinscheduler

* 元数据采集
- [ ] hive 定时采集或者Hook(推荐使用Hook) 采集变更数据上传到消息系统
- [ ] 元数据手动录入(pulsar/hive)
- [ ] 定时采集主要针对RDMS(优先级低)
- [ ] 对接 dolphinscheduler 采集元数据
- [ ] 多种数据源对接

3.元数据血缘
- [ ] 字段级血缘？？？

4.元数据探索

- [ ] 基础查询-API，根据模型查找实例，根据实例查找模型
- [ ] 生成索引数据
- [ ] 高级搜索接口

5.访问权限
- [ ] 平台权限
- [ ] 源权限
- [ ] 数据预览

6.分布式缓存同步



---

## 计划

开始日期：2022-02-07

---

|        |                         | 
|:------:|:------------------------|
|  开始日期  | 2022-02-14              |
|   任务   | 元数据定义-元模型管理             | 
|  KPI   | 1.支持动态配置模型<br> 2.模型约束实例 | 
|  负责人   | Kerwin                  | 
|  参与人   | Kerwin<br>Moouna        | 
|  汇报人   | Kerwin                  | 
| 预计完成时间 | 2022-02-25              | 
|   状态   | 延迟                      | 
| 实际完成时间 |                         | 


---
【腾讯文档】Dolphin Meta & Quality
https://docs.qq.com/doc/DQ1JtaFhlZ2tTY0xv
