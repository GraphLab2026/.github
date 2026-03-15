# GraphRoadMap

## 历史脉络

图技术从 2015 年至今经历了快速发展，从早期的 OLTP 图数据库到 OLAP 图计算分析，再到如今 AI 驱动的轻量化与智能化方向。

![图技术发展时间线 (2015-2026)](../resource/RoadMap.png)

---

## 相关技术发展

### 图数据库 & 图计算平台

| 项目 | 官网 | 说明 |
|------|------|------|
| **Neo4j** | [neo4j.com](https://neo4j.com/) | 成熟的图数据库，Cypher 查询语言 |
| **Nebula Graph** | [nebula-graph.io](https://nebula-graph.io/) | 计算/存储分离架构 |
| **HugeGraph** | [hugegraph.apache.org](https://hugegraph.apache.org/docs/introduction/) | Apache 项目，AI 驱动轻量化 |
| **JanusGraph** | [janusgraph.org](https://janusgraph.org/) | Titan 分支，分布式图数据库 |
| **PuppyGraph** | [puppygraph.com](https://www.puppygraph.com/) | 数据湖图引擎 (Iceberg/Hudi) |
| **GStore** | [gstore.cn](https://www.gstore.cn/#/) | RDF 知识图谱 |
| **GraphScope** | [graphscope.io](https://graphscope.io/) | 阿里一站式图计算平台 |
| **GraphScope NeuG** | [graphscope.io/neug](https://graphscope.io/neug/) | 嵌入式图数据库，"DuckDB for Graphs" |
| **TuGraph** | [tugraph.tech](https://tugraph.tech/?lang=en-US) | 蚂蚁集团，LDBC SNB 记录保持者 |
| **TuGraph-Analyze: Geaflow** | [GitHub](https://github.com/apache/geaflow/blob/master/README_cn.md) | 流批一体图计算 |

> **观察**: 阿里系基础架构具备很强的产品思维，但在具体结合业务时，会有具体的技术瓶颈无法实现。在 AI 时代，这个问题怎么解决？

---

## TODO (截止到 2026 年)

### 业务应用问题

- **面向用户的可视化前端**: 标注、挖掘等的易用性
- **引擎支持 OLTP/OLAP**: 强悍的性能

---

## 思考

> **AI 时代下，Graph 基础设施发展方向是什么？**
>
> Where Are You?
