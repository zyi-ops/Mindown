# 🧠 Mindown - A Knowledge Base Tool Combining Mind Maps and Notes

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/zyi-ops/Mindown)   [![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/zyi-ops/Mindown/blob/main/LICENSE)  [![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-orange)](https://github.com/zyi-ops/Mindown)

---

## 📌 Overview  
**MindNote** is an open-source knowledge base tool that integrates **mind maps** with note management.  
- **Core Philosophy**: Organize knowledge through nodes, visually demonstrating connections between notes via a graphical structure.  
- **Target Users**: Students, developers, researchers, and others needing efficient management of fragmented knowledge.  
- **Features**:  
  - Node-based note management (each node binds to a Markdown/text file).  
  - Drag-and-drop, zooming, and color tagging for interactive operations.  
  - Data persistence (JSON storage structure, file system for note content).  
  - Cross-platform support (Windows/macOS/Linux).

---

## 🚀 Core Features  
| Feature | Description |
|--------|-------------|
| **Mind Map Editing** | Create, delete, and drag nodes; supports parent-child hierarchies and free layouts. |
| **Note Binding** | Associate each node with a note file; supports Markdown and rich-text editing. |
| **Data Persistence** | Save/load mind map structures (JSON format) and note content (local files). |
| **Search Navigation** | Quickly locate nodes or note content by keyword. |
| **Export Functionality** | Export mind maps to PNG/SVG images or PDF documents (planned). |

---

## 🛠️ Technology Stack  
- **Languages & Frameworks**: C++ + Qt 6.  
- **Data Storage**:  
  - Mind map structure: JSON files (lightweight and extensible).  
  - Note content: Local Markdown files.  
- **Third-party Libraries**:  
  - [QMarkdown](https://github.com/bananaacid/qmarkdown) (Markdown rendering support).  

---

## 📦 Installation Guide  
### Windows/macOS/Linux  
1. **Install Dependencies**:  
   - Install [Qt 6](https://www.qt.io/download) (select the platform-specific installer).  
   - Install CMake (for building).  
2. **Clone the Project**:  
   ```bash
   git clone https://github.com/zyi-ops/Mindown.git  
   cd Mindown
   ```
3. **Build & Run**:  
   ```bash
   mkdir build && cd build
   cmake ..
   make  # Windows: Use Qt Creator for building
   ./Mindown
   ```

---

## 📖 Usage Instructions  
1. **Create a New Node**: Right-click on empty space and select "New Node".  
2. **Bind a Note**: Double-click a node, enter a title, and link to a Markdown file.  
3. **Save the Project**: Click "File > Save" in the menu bar to export JSON structure and note files.  
4. **Search Function**: Press `Ctrl+F` to input keywords and auto-locate matching nodes.  

---

## 🤝 Contribution Guidelines  
Welcome Pull Requests!  
1. Fork this repository and create your branch (`git checkout -b feature/your-feature`).  
2. Commit changes with descriptive messages (`git commit -m "Add feature"`).  
3. Push your branch (`git push origin feature/your-feature`).  
4. Submit a Pull Request with detailed improvement descriptions.  

---

## 📅 TODO List  
| Priority | Feature | Status |
|--------|---------|--------|
| 🔥 High | Node Drag-and-Drop & Parent-Child Relationships | 🟡 In Progress |
| 🔥 High | Note Binding & Markdown Editor | 🟢 Not Started |
| 🟡 Medium | JSON Data Persistence & Loading | 🟢 Not Started |
| 🟡 Medium | Export Mind Maps to Images/PDF | 🟢 Not Started |
| 🟢 Low | Cloud Sync (Integrate OneDrive) | 🟢 Not Started |
| 🟢 Low | Plugin System (Math Formulas, Charts) | 🟢 Not Started |

---

## 📜 License  
This project uses the MIT License. Details available at [LICENSE](https://github.com/zyi-ops/Mindown/blob/main/LICENSE).

---

## 📬 Contact  
- **Author**: [Yi](https://github.com/zyi-ops)  
- **Feedback**: Submit Issues or email aarch4082@outlook.com

---

### 🎯 Inspiration Sources  
- [Freeplane](https://www.freeplane.org/)  
- [Obsidian](https://obsidian.md/) 
---

**Star ⭐ if you like this project!**  
**Fork 🍴 Welcome to contribute!**

### Roadmap  
- **v1.0**: Complete core features (node editing, note binding, data persistence).  
- **v1.5**: Add export functionality and advanced search.
