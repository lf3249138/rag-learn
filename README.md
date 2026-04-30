# 大模型应用开发实战一：RAG技术全栈指南

<div align="center">
  <h2>🔍 检索增强生成 (RAG) 技术全栈指南</h2>
  <p><em>从理论到实践，从基础到进阶，构建你的RAG技术体系</em></p>
</div>

<div align="center">
  <br>
  <table>
    <tr>
      <td align="center">🎯 <strong>系统化学习</strong><br>完整的RAG技术体系</td>
      <td align="center">🛠️ <strong>动手实践</strong><br>丰富的项目案例</td>
      <td align="center">🚀 <strong>生产就绪</strong><br>工程化最佳实践</td>
      <td align="center">📊 <strong>多模态支持</strong><br>文本+图像检索</td>
    </tr>
  </table>
</div>

## 项目简介

本项目是一个面向大模型应用开发者的RAG（检索增强生成）技术全栈教程。

**主要内容包括：**

1. **RAG技术基础**：深入浅出地介绍RAG的核心概念、技术原理和应用场景
2. **数据处理全流程**：从数据加载、清洗到文本分块的完整数据准备流程
3. **索引构建与优化**：向量嵌入、多模态嵌入、向量数据库构建及索引优化技术
4. **检索技术进阶**：混合检索、查询构建、Text2SQL等高级检索技术
5. **生成集成与评估**：格式化生成、系统评估与优化方法
6. **项目实战**：从基础到进阶的完整RAG应用开发实践

## 内容大纲

### 第一部分：RAG基础入门

**第一章 解锁RAG** [📖 查看章节](./docs/chapter1)
- [x] [RAG简介](./docs/chapter1/01_RAG_intro.md) - RAG技术概述与应用场景
- [x] [准备工作](./docs/chapter1/02_preparation.md) - 环境配置与准备
- [x] [四步构建RAG](./docs/chapter1/03_get_start_rag.md) - 快速上手RAG开发
- [x] [附：环境部署](./docs/chapter1/virtualenv.md) - Python虚拟环境部署方案补充 (贡献者: [@anarchysaiko](https://github.com/anarchysaiko))

**第二章 数据准备** [📖 查看章节](./docs/chapter2)
- [x] [数据加载](./docs/chapter2/04_data_load.md) - 多格式文档处理与加载
- [x] [文本分块](./docs/chapter2/05_text_chunking.md) - 文本切分策略与优化

### 第二部分：索引构建与优化

**第三章 索引构建** [📖 查看章节](./docs/chapter3)
- [x] [向量嵌入](./docs/chapter3/06_vector_embedding.md) - 文本向量化技术详解
- [x] [多模态嵌入](./docs/chapter3/07_multimodal_embedding.md) - 图文多模态向量化
- [x] [向量数据库](./docs/chapter3/08_vector_db.md) - 向量存储与检索系统
- [x] [Milvus实践](./docs/chapter3/09_milvus.md) - Milvus多模态检索实战
- [x] [索引优化](./docs/chapter3/10_index_optimization.md) - 索引性能调优技巧

### 第三部分：检索技术进阶

**第四章 检索优化** [📖 查看章节](./docs/chapter4)
- [x] [混合检索](./docs/chapter4/11_hybrid_search.md) - 稠密+稀疏检索融合
- [x] [查询构建](./docs/chapter4/12_query_construction.md) - 智能查询理解与构建
- [x] [Text2SQL](./docs/chapter4/13_text2sql.md) - 自然语言转SQL查询
- [x] [查询重构与分发](./docs/chapter4/14_query_rewriting.md) - 查询优化策略
- [x] [检索进阶技术](./docs/chapter4/15_advanced_retrieval_techniques.md) - 高级检索算法

### 第四部分：生成与评估

**第五章 生成集成** [📖 查看章节](./docs/chapter5)
- [x] [格式化生成](./docs/chapter5/16_formatted_generation.md) - 结构化输出与格式控制

**第六章 RAG系统评估** [📖 查看章节](./docs/chapter6)
- [x] [评估介绍](./docs/chapter6/18_system_evaluation.md) - RAG系统评估方法论
- [x] [评估工具](./docs/chapter6/19_common_tools.md) - 常用评估工具与指标

### 第五部分：高级应用与实战

**第七章 高级RAG架构（拓展部分）** [📖 查看章节](./docs/chapter7)

- [x] [基于知识图谱的RAG](./docs/chapter7/20_kg_rag.md)

**第八章 项目实战一** [📖 查看章节](./docs/chapter8)
- [x] [环境配置与项目架构](./docs/chapter8/01_env_architecture.md)
- [x] [数据准备模块实现](./docs/chapter8/02_data_preparation.md)
- [x] [索引构建与检索优化](./docs/chapter8/03_index_retrieval.md)
- [x] [生成集成与系统整合](./docs/chapter8/04_generation_sys.md)

**第九章 项目实战一优化（选修篇）** [📖 查看章节](./docs/chapter9)

[🍽️ 项目展示](https://github.com/FutureUnreal/What-to-eat-today)
- [x] [图RAG架构设计](./docs/chapter9/01_graph_rag_architecture.md)
- [x] [图数据建模与准备](./docs/chapter9/02_graph_data_modeling.md)
- [x] [Milvus索引构建](./docs/chapter9/03_index_construction.md)
- [x] [智能查询路由与检索策略](./docs/chapter9/04_intelligent_query_routing.md)

## 目录结构说明

```
all-in-rag/
├── docs/           # 教程文档
├── code/           # 代码示例
├── data/           # 示例数据
├── models/         # 预训练模型
├── Extra-chapter/  # 扩展章节与社区实践内容
└── README.md       # 项目说明
```