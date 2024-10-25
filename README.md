## 基于知识图谱的矿山灾难问答系统

### 项目简介

本项目是一个基于Django框架和Neo4j图数据库的矿山灾难问答系统。通过整合矿山灾难相关的数据，并以图谱的形式进行展示，系统旨在为用户提供高效、直观的灾难信息查询与问答服务。

### 主要功能

* **图谱展示功能**：通过Neo4j图数据库，将矿山灾难相关的实体以及它们之间的关系以图谱的形式进行可视化展示。
* **问答功能**：支持用户通过自然语言提问方式查询矿山灾难相关信息。
* **数据初始化功能**：确保系统能够正常运行并提供准确的数据服务。


### 技术架构

本项目主要依赖以下技术：

* **前端:** HTML、CSS、JavaScript
* **后端:** Django
* **图库:** Neo4j
* **可视化库:** echarts.js


### 使用说明

1. 访问系统地址：http://127.0.0.1:8000/
2. 数据初始化：首次使用系统时，请访问**http://127.0.0.1:8000/init_datas**来初始化数据。
3. 提问：在主页面输入您的问题并搜索。


**联系方式**

微信号：zt745324325