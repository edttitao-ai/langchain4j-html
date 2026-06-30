# LangChain4j & langGraph4j 教程

<div align="center">

[![Stars](https://img.shields.io/github/stars/your-username/langchain4j-html-v1?style=social)](https://github.com/your-username/langchain4j-html-v1/stargazers)
[![License](https://img.shields.io/github/license/your-username/langchain4j-html-v1)](LICENSE)
[![Issues](https://img.shields.io/github/issues/your-username/langchain4j-html-v1)](https://github.com/your-username/langchain4j-html-v1/issues)

**面向 Java 工程师的 LLM 应用开发教程** | 26 个交互式章节 | 纯静态部署

[English](./README_EN.md) | 中文

</div>

---

## 项目简介

本教程系统讲解 **LangChain4j** 和 **langGraph4j** 在 Java 项目中的实际应用，涵盖从基础 API 调用到生产级 RAG、Agents、MCP 等高级特性。

**特点**：
- 📖 26 个完整章节，循序渐进
- 💻 代码示例覆盖 OpenAI / 通义千问 / 智谱 GLM 等主流模型
- ⚠️ 每章包含官方文档的注意要点和避坑指南
- 🎯 交互式学习体验，浏览器直接打开即可

---

## 学习路径

### 基础篇（第 1-9 章）

| 章节 | 主题 | 预估时长 |
|:---:|------|:-------:|
| ch01 | 底层 API：ChatLanguageModel | 30min |
| ch02 | 多轮对话 | 25min |
| ch03 | 参数调优 | 20min |
| ch04 | 流式输出 | 30min |
| ch05 | 门面接口 AiServices | 25min |
| ch06 | 工具调用 ToolCalling | 40min |
| ch07 | 结构化输出 | 30min |
| ch08 | 分类 Classification | 20min |
| ch09 | 图像生成 ImageGeneration | 25min |

### 高级篇（第 10-19 章）

| 章节 | 主题 | 预估时长 |
|:---:|------|:-------:|
| ch10 | Spring Boot 集成 | 40min |
| ch11 | HTTP 客户端选择 | 20min |
| ch12 | 日志配置 | 15min |
| ch13 | JSON Codec | 25min |
| ch14 | RAG 检索增强生成 | 45min |
| ch15 | Agents 代理 | 40min |
| ch16 | MCP 模型上下文协议 | 35min |
| ch17 | Guardrails 安全防护 | 30min |
| ch18 | 可观测性 Observability | 25min |
| ch19 | Skills 技能系统 | 35min |

### langGraph4j 篇（第 1-7 章）

| 章节 | 主题 | 预估时长 |
|:---:|------|:-------:|
| lg01 | 核心库入门 | 35min |
| lg02 | 子图 Subgraph | 30min |
| lg03 | 并行分支 Parallel | 25min |
| lg04 | 流式传输 Streaming | 30min |
| lg05 | 钩子 Hooks | 20min |
| lg06 | 取消 Cancellation | 15min |
| lg07 | 检查点 Checkpointing | 30min |

---

## 快速开始

### 方式一：直接打开

下载或克隆项目后，直接用浏览器打开 `index.html` 即可开始学习。

### 方式二：本地服务器

```bash
# Python 3
python -m http.server 8080

# Node.js (npx)
npx serve .

# 或使用 VS Code 的 Live Server 插件
```

然后访问 http://localhost:8080

---

## 项目结构

```
langchain4j-html-v1/
├── index.html                    # 总览页（学习路径 + 知识地图）
├── nav.html                      # 导航页（左侧菜单 + iframe 内容区）
├── assets/
│   └── style.css                 # 全局样式
├── chapter-01~19.html            # LangChain4j 教程章节
├── langgraph4j-chapter-01~07.html # langGraph4j 教程章节
└── README.md                     # 本文件
```

---

## 技术栈

- **核心框架**: LangChain4j, langGraph4j
- **AI 模型**: OpenAI GPT, 阿里通义千问, 智谱 GLM
- **运行环境**: JDK 8+, Spring Boot 2.7+
- **教程格式**: HTML5 + CSS3 + Vanilla JavaScript

---

## 适合人群

- ✅ 有 Java 基础的开发者
- ✅ 希望快速上手 LLM 应用开发
- ✅ 需要构建 RAG 或 Agent 系统的工程师
- ✅ 对 AI 工程化感兴趣的团队

---

## 参考资料

- [LangChain4j 官方文档](https://docs.langchain4j.dev/)
- [langGraph4j 官方文档](https://langchain-graalvm.github.io/langgraph4j/)
- [LangChain4j GitHub](https://github.com/langchain4j/langchain4j)

---

## 贡献指南

欢迎提交 Issue 或 Pull Request！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

---

## 许可证

本项目采用 [MIT License](LICENSE) 许可证。

---

<div align="center">

如果这个项目对你有帮助，请点个 ⭐ Star！

</div>