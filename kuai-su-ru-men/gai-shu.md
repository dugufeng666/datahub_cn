# 💡 概述

{% hint style="info" %}
**GitBook tip:** A succinct video overview is a great way to introduce folks to your product. Embed a Loom, Vimeo or YouTube video and you're good to go! We love this video from the fine folks at Loom as a perfect example of a succinct feature overview.
{% endhint %}

### 搜索和发现

#### **搜索数据堆栈**的所有角落

DataHub 的统一搜索体验可跨数据库、数据湖、BI 平台、ML 功能存储、编排工具等显示结果。

![](https://raw.githubusercontent.com/datahub-project/static-assets/main/imgs/feature-search-all-corners-of-your-datastack.gif)

#### **跟踪端到端世系**

通过跨平台、数据集、ETL/ELT 管道、图表、仪表板等跟踪沿袭，快速了解数据的端到端旅程。

![](https://raw.githubusercontent.com/datahub-project/static-assets/main/imgs/feature-end-to-end-lineage.png)

#### **了解中断性变更对下游依赖项**的影响

使用影响分析主动确定哪些实体可能受到重大变更的影响。

![](https://raw.githubusercontent.com/datahub-project/static-assets/main/imgs/feature-impact-analysis.gif)

#### **查看元数据 360 度概览**

结合_技术和逻辑_元数据，提供数据实体的 360º 视图。

生成**数据集统计信息**以了解数据的形状和分布

![](https://raw.githubusercontent.com/datahub-project/static-assets/main/imgs/feature-dataset-stats.png)

从远大期望等工具捕获历史**数据验证结果**

利用 DataHub 的**架构版本历史记录**来跟踪数据物理结构随时间的变化

***

### 现代数据治理

#### **实时**治理

[操作框架](https://datahubproject.io/docs/actions)支持以下实时用例：

* **通知：**在数据中心进行更改时生成特定于组织的通知。例如，在将“PII”标记添加到任何数据资产时，向治理团队发送电子邮件。
* **工作流集成：**将数据中心集成到组织的内部工作流中。例如，在数据集上提出特定标记或术语时创建 Jira 票证。
* **同步：**将数据中心中所做的更改同步到第三方系统。例如，将 DataHub 中的标记添加反映到 Snowflake 中。
* **审计：**审核谁在数据中心上进行了哪些更改。

#### **管理实体所有权**

快速轻松地将实体所有权分配给用户和用户组。

![](https://raw.githubusercontent.com/datahub-project/static-assets/main/imgs/feature-entity-owner.png)

#### **使用标签、词汇表术语和域**进行治理

使数据所有者能够通过以下方式管理其数据实体：

1. **标签：**非正式的、松散控制的标签，用作搜索和发现的工具。没有正式的中央管理。
2. **词汇表术语：**具有可选层次结构的受控词汇表，通常用于描述核心业务概念和度量。
3. **域：**特选的顶级文件夹或类别，广泛用于 Data Mesh 中，用于按部门（即财务、市场营销）或数据产品组织实体。

![](https://raw.githubusercontent.com/datahub-project/static-assets/main/imgs/feature-tags-terms-domains.png)

***

### 数据中心管理

#### **创建用户、组和访问策略**

DataHub 管理员可以创建策略来定义谁可以对哪些资源执行什么操作。创建新策略时，您将能够定义以下内容：

* **策略类型** - 平台（顶级 DataHub 平台权限，即管理用户、组和策略）或元数据（操作所有权、标签、文档等的能力）
* **资源类型** - 指定资源类型，例如数据集、仪表板、管道等
* **权限** - 选择权限集，例如编辑所有者、编辑文档、编辑链接
* **用户和/或组** - 分配相关用户和组;还可以将策略分配给资源所有者，无论他们属于哪个组

![](https://raw.githubusercontent.com/datahub-project/static-assets/main/imgs/feature-manage-policies.png)

#### **从 UI** 引入元数据

使用DataHub用户界面创建，配置，计划和执行批处理元数据摄取。这样可以最大程度地减少操作自定义集成管道所需的开销，从而更轻松地将元数据导入 DataHub。

![](https://raw.githubusercontent.com/datahub-project/static-assets/main/imgs/feature-managed-ingestion-config.png)

\
