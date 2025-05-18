# 🧠 Mindown - 思维导图与笔记结合的知识库工具

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/zyi-ops/Mindown)   [![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/zyi-ops/Mindown/blob/main/LICENSE)  [![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-orange)](https://github.com/zyi-ops/Mindown)

### 🌍 Language Versions  
- [中文文档](README.md)  
- [English Document](README_EN.md)

---

## 📌 概述  
**MindNote** 是一款将 **思维导图（Mind Map）与笔记管理** 结合的开源知识库工具。  
- **核心理念**：以节点为单位组织知识，通过图形化结构直观展示笔记间的关联性。  
- **目标用户**：学生、开发者、研究人员等需要高效管理碎片化知识的群体。  
- **特点**：  
  - 节点化笔记管理（每个节点绑定一个 Markdown/文本文件）。  
  - 支持拖拽、缩放、颜色标记等交互操作。  
  - 数据持久化（JSON 存储结构，文件系统存储笔记内容）。  
  - 跨平台支持（Windows/macOS/Linux）。

---

## 🚀 核心功能  
| 功能             | 描述                                                       |
| ---------------- | ---------------------------------------------------------- |
| **思维导图编辑** | 创建、删除、拖拽节点，支持父子层级关系和自由布局。         |
| **笔记绑定**     | 每个节点关联一个笔记文件，支持 Markdown 和富文本编辑。     |
| **数据持久化**   | 保存/加载思维导图结构（JSON 格式）和笔记内容（本地文件）。 |
| **搜索导航**     | 按关键字快速定位节点或笔记内容。                           |
| **导出功能**     | 导出思维导图为 PNG/SVG 图片或 PDF 文档（待实现）。         |

---

## 📅TODO
- [ ] 节点拖拽与父子关系实现（高优先级）
- [ ] 笔记绑定与 Markdown 编辑器（高优先级）
- [ ] JSON 数据持久化与加载（中优先级）
- [ ] 导出思维导图为图片/PDF（中优先级）
- [ ] 云同步功能（集成 OneDrive）（低优先级）
- [ ] 插件系统（支持数学公式、图表插入）（低优先级）

---

## 🛠️ 技术选型  
- **语言与框架**：C++ + Qt 6。  
- **数据存储**：  
  - 思维导图结构：JSON 文件（轻量级且易于扩展）。  
  - 笔记内容：本地 Markdown。 
---

## 📦 安装指南  
### Windows/macOS/Linux  
1. **依赖安装**：  
   - 安装 [Qt 6](https://www.qt.io/download)（选择对应平台的安装包）。  
   - 安装 CMake（用于构建）。  
2. **克隆项目**：  
   ```bash
   git clone https://github.com/zyi-ops/Mindown.git
   cd Mindown
   ```
3. **构建与运行**：  
   ```bash
   mkdir build && cd build
   cmake ..
   make  # Windows: 使用 Qt Creator 构建
   ./Mindown
   ```

---

## 📖 使用说明  
1. **创建新节点**：右键点击空白区域，选择“新建节点”。  
2. **绑定笔记**：双击节点，输入标题并关联一个 Markdown 文件。  
3. **保存项目**：点击菜单栏“文件 > 保存”，导出 JSON 结构和笔记文件。  
4. **搜索功能**：按 `Ctrl+F` 输入关键字，自动定位匹配节点。  

---

## 🤝 贡献指南  
欢迎提交 Pull Request！  
1. Fork 本仓库，创建自己的分支（`git checkout -b feature/your-feature`）。  
2. 提交代码并描述改动（`git commit -m "Add feature"`）。  
3. 推送分支（`git push origin feature/your-feature`）。  
4. 创建 Pull Request，描述改进内容。  

---

## 📜 许可证  
本项目采用 MIT License，详情见 [LICENSE](https://github.com/zyi-ops/Mindown/blob/main/LICENSE)。

---

## 📬 联系方式  
- **作者**：[Yi](https://github.com/zyi-ops)  
- **反馈**：提交 Issue 或发送邮件至 aarch4082@outlook.com

---

### 🎯 灵感来源  
- [Freeplane](https://www.freeplane.org/)  
- [Obsidian](https://obsidian.md/)  
---

**Star ⭐ 如果你喜欢这个项目！**  
**Fork 🍴 欢迎参与开发！**

### 后续计划  
- **v1.0**：完成核心功能（节点编辑、笔记绑定、数据持久化）。  
- **v1.5**：新增导出功能和高级搜索。  
