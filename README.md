# 🚀 IB CS 复习小测验 🚀

[![状态](https://img.shields.io/badge/状态-活跃-brightgreen.svg)](https://github.com/your-username/your-repo) [![版本](https://img.shields.io/badge/版本-1.1.0-blue.svg)](https://github.com/your-username/your-repo) [![许可证](https://img.shields.io/badge/许可证-MIT-yellow.svg)](LICENSE)

这是一个为 IB 计算机科学 (IB Computer Science) 学生设计的在线复习小测验应用，旨在帮助他们巩固和测试课程关键概念的掌握程度。该项目包含 **Paper 1 综合知识** 和 **Paper 2 Java 面向对象编程 (OOP)** 两个独立的测验。该项目由 **Jason Wang** 创建。
本说明文件为AI生成。

---

## ✨ 核心功能

* **📚 全面的知识点覆盖**: 包含两个独立的测验模块：
    * **Paper 1 测验 (`index.html`)**: 包含 **183 道**精心设计的选择题，涵盖 IB CS 课程的多个核心主题，包括：
        * 计算思维 (Computational Thinking)
        * 算法基础 (Algorithms - Searching, Sorting, Big O)
        * 数据结构 (Data Structures)
        * 计算机系统基础 (Computer Systems)
        * 网络基础 (Networking)
        * 系统生命周期 (System Life Cycle)
        * 数据表示 (Data Representation)
        * 布尔逻辑 (Boolean Logic)
    * **Paper 2 OOP 测验 (`p2_oop.html`)**: 包含 **50 道** 针对 Java 面向对象编程的选择题，涵盖：
        * 访问修饰符 (Access Modifiers: `public`, `private`, `protected`)
        * `static`, `final` 关键字
        * 类与对象 (Class vs Object), 实例化 (Instantiation)
        * UML 关系: 聚合 (Aggregation), 组合 (Composition), 依赖 (Dependency), 继承 (Inheritance)
        * 参数传递 (按值传递) (Parameter Passing by Value)
        * 变量作用域 (Variable Scopes: Instance, Local, Parameter)
        * 方法签名与重载 (Method Signature, Overloading)
        * OOP 核心原则: 封装 (Encapsulation), 继承 (Inheritance), 多态 (Polymorphism) (包括方法覆盖 Overriding)
        * 模块化 (Modularity)
        * 访问器/设置器 (Getters/Setters)
        * 构造器 (Constructors), `this`, `super`
        * 抽象类与接口 (Abstract Classes, Interfaces)
        * 类型转换 (Upcasting, Downcasting, `instanceof`)
        * `ArrayList` 常用操作
        * 异常处理 (Exception Handling: `try`, `catch`, `finally`, `throw`, `throws`, Checked vs Unchecked)
        * 递归 (Recursion)
        * `String` 不可变性, `StringBuilder`/`StringBuffer`
        * 包装类与自动装/拆箱 (Wrapper Classes, Autoboxing/Unboxing)
        * 基础设计原则 (如迪米特法则, 开闭原则, 单一职责, 里氏替换)
* **🎮 互动式测验体验**:
    * 问题与选项**随机排序**，增加重复练习的挑战性。
    * 实时追踪问题进度 (`问题 X / 总数`)。
    * 动态计算并显示得分与正确率 (`得分: Y / Z (P%)`)。
    * 清晰的**进度条**可视化测验完成度。
* **💡 即时反馈与学习**:
    * 选择答案后**立即**获得视觉反馈（正确/错误高亮）。
    * ✅ Paper 1 & 2: 正确答案附带**五彩纸屑动画**，增加趣味性。
    * ❌ Paper 1 & 2: 错误答案清晰标示，并**显示正确选项**。
    * 📝 **Paper 2 特有**: 回答问题后，提供该题目的**详细文字解释**，帮助理解概念。
* **🏆 结果总结与个性化鼓励**:
    * 测验结束后，提供详细的**最终得分**和**正确率**。
    * 根据得分百分比，生成**个性化的鼓励评语**。
    * 高分可触发特殊的**庆祝背景动画**。
* **🔄 轻松切换与重置**:
    * 在 Paper 1 和 Paper 2 测验页面之间可通过**按钮轻松跳转**。
    * 提供“重新开始”按钮，方便用户随时进行新一轮测验。
* **📱 用户友好与响应式设计**:
    * 采用 **Tailwind CSS** 构建现代化、简洁美观的界面。
    * **完全响应式**布局，在桌面和移动设备上均能良好显示。

## 🛠️ 技术栈解析

* **前端核心**: `HTML5`, `CSS3`, `JavaScript (ES6)`
    * *理由*: 使用 Web 标准技术构建，无需复杂环境，跨平台兼容性好。
* **UI 框架**: `Tailwind CSS v3`
    * *理由*: 提供原子类 CSS，能够快速构建定制化且响应式的用户界面，保持代码简洁。
* **视觉效果**: `Canvas Confetti`
    * *理由*: 轻量级库，用于在用户答对题目时添加有趣的庆祝动画，提升用户体验。
* **字体**: `Inter` (via Google Fonts)
    * *理由*: 现代、清晰易读的无衬线字体，适合界面显示。

## 🚀 快速开始

无需复杂安装，只需按以下步骤操作：

1.  **下载**: 获取项目中的 `index.html` 和 `p2_oop.html` 文件。
2.  **打开**:
    * 若要开始 **Paper 1 综合知识**测验，请使用现代网页浏览器（如 Chrome, Firefox, Safari, Edge 等）打开 `index.html` 文件。
    * 若要开始 **Paper 2 Java OOP** 测验，请使用浏览器打开 `p2_oop.html` 文件。
3.  **切换 (可选)**: 在任一测验页面顶部，都有一个按钮可以跳转到另一个测验。
4.  **开始测验**: 🎉 享受复习过程！

## 🤝 贡献指南

目前这是一个个人项目，但如果您有任何建议或发现错误，欢迎通过以下方式联系：

* 创建 GitHub Issue (如果项目托管在 GitHub 上)
* 直接联系开发者 Jason Wang

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)。 

## 🙏 致谢

* 感谢所有为 IB CS 课程提供教学资源和灵感的教育工作者。
* 感谢 [Tailwind CSS](https://tailwindcss.com/) 和 [Canvas Confetti](https://github.com/catdad/canvas-confetti) 的开发者。

---

希望这个小测验能成为您 IB CS 学习旅程中的得力助手！💪
