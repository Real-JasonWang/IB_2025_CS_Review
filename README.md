<h1 align="center">🚀 IB Revision Toys 🚀</h1>

<p align="center">
  <a href="#-版本印记"><img src="https://img.shields.io/badge/版本-v0.1.1%20Tiny%20Mouse-dodgerblue?style=for-the-badge&logo=github" alt="版本 v0.1.1 Tiny Mouse"></a>
  <a href="#"><img src="https://img.shields.io/badge/状态-积极迭代中-brightgreen?style=for-the-badge" alt="状态：积极迭代中"></a>
  <a href="LICENSE.md"><img src="https://img.shields.io/badge/许可-MIT-green?style=for-the-badge" alt="许可 MIT"></a>
  <a href="#"><img src="https://img.shields.io/badge/平台-Web-orange?style=for-the-badge&logo=html5" alt="平台 Web"></a>
</p>

<p align="center">
  <em>专为IB学子打造的趣味复习工具集，让备考之路不再枯燥，高效且充满乐趣！</em>
</p>

<p align="center">
  <a href="#-核心特性">核心特性</a> •
  <a href="#-技术栈">技术栈</a> •
  <a href="#-模块概览">模块概览</a> •
  <a href="#-快速上手">快速上手</a> •
  <a href="#-开发者">开发者</a> •
  <a href="#-未来展望">未来展望</a>
</p>

---

## 🎯 项目简介 (Project Overview)

**IB Revision Toys** 并非寻常的复习软件，它是一系列精心设计的交互式测验应用，旨在革新IB学生的备考体验。我们致力于将复杂的知识点转化为引人入胜的挑战，帮助学生在轻松愉快的氛围中巩固记忆、查漏补缺，最终自信满满地走向考场。

> **“学海无涯，玩亦有道。”** —— 这正是本项目的核心理念。

---

## ✨ 核心特性 (Core Features)

本应用集包含了一系列旨在提升学习效率与趣味性的高级功能：

* 🎨 **现代化用户界面 (Modern UI):** 基于 TailwindCSS 构建，界面清爽、响应迅速，适配各类设备。
* 🧠 **交互式测验引擎 (Interactive Quiz Engine):** 提供动态题目加载、选项随机化及即时反馈机制。
* 📊 **实时进度与得分 (Real-time Progress & Scoring):** 直观展示当前进度、已答题目数量及准确率。
* 💡 **详尽答案解析 (Detailed Explanations):** （部分模块）提供错误题目解析，深化理解，巩固知识点。
* 🎉 **趣味激励机制 (Gamified Motivation):** 正确作答或完成测验时的“五彩纸屑”庆祝动画，增添学习乐趣。
* 🔄 **可重复练习 (Repeatable Practice):** 支持无限次重新开始测验，助力反复巩固。
* 🌐 **纯前端实现 (Client-Side Rendering):** 无需后端支持，轻松部署，即开即用。

---

## 🛠️ 技术栈 (Tech Stack)

本项目采用了业界前沿且稳定可靠的技术栈，确保了应用的性能与可维护性：

| 类别         | 技术                                                                                           |
| :----------- | :--------------------------------------------------------------------------------------------- |
| **核心语言** | `HTML5`, `CSS3`, `JavaScript (ES6+)`                                                             |
| **CSS框架** | `TailwindCSS v3.x` (实用程序优先的CSS框架)                                                       |
| **字体** | `Google Fonts (Inter)` (提升阅读体验)                                                            |
| **动画库** | `canvas-confetti.js` (用于庆祝动画)                                                              |
| **代码规范** | (推荐 ESLint, Prettier - 未在文件中直接体现，但为良好实践)                                           |
| **版本控制** | `Git` (通过README版本号体现)                                                                      |

---

## 📚 模块概览 (Quiz Modules Overview)

截至 `v0.1.1 "Tiny Mouse"` 版本，我们已精心准备了以下复习模块：

| 模块名称 (Subject & Paper)          | 题目数量 (Questions) | 内部版本 (Internal Ver.) | 主要内容 (Focus Area)                                  | 访问链接 (Link)                         |
| :---------------------------------- | :------------------- | :----------------------- | :----------------------------------------------------- | :-------------------------------------- |
| 💼 **English B SL Paper 2** | ~50                  | `v2505a`                 | 听力与阅读理解技巧及主题知识                             | `p2_eng_randl.html`                     |
| 🖋️ **English B SL Paper 1** | ~120                 | `v2505b`                 | 写作文本类型、IB主题认知、评分标准理解                   | `p1_eng_writing.html`                   |
| 💻 **CS SL Paper 2 (OOP 专项)** | 110+                 | `v2505a`                 | Java 面向对象编程核心概念 (P2 重点)                      | `p2_oop.html`                           |
| 🧠 **CS SL Paper 1 (全覆盖)** | 180+                 | `v2504a`                 | Paper 1 计算机科学理论知识综合复习                     | `p1_cs.html`                            |
| ⏳ **敬请期待 (Coming Soon)** | N/A                  | N/A                      | 更多科目与主题的测验正在紧锣密鼓地开发中！             | `index.html` (占位)                     |

---

## 🚀 快速上手 (Getting Started)

轻松开启您的IB复习之旅：

1.  **导航至主页:** 打开项目根目录下的 `index.html` 文件，即可看到所有可用的测验模块。
    ```bash
    # 假设您已下载项目文件
    # 只需在浏览器中打开 index.html
    ```
2.  **选择模块:** 点击您希望进行的测验模块卡片。
3.  **开始挑战:** 仔细阅读题目，选择您认为正确的答案。
4.  **即时反馈:** 提交答案后，系统将立即判断对错，并（在支持的模块中）展示相关解析。
5.  **追踪表现:** 界面上方会显示您的实时得分、答题进度百分比。
6.  **温故知新:** 完成测验后，可以选择“重新开始”进行新一轮的练习。

## 📄 开源许可 (License)

本项目遵循 **MIT License** 开源许可协议。

---

## 🔮 未来展望 (Future Roadmap)

**IB Revision Toys** 的征途才刚刚开始，我们对未来充满期待并规划了以下发展方向：

* ✅ **新增测验模块:** 持续扩充更多IB科目（如数学、物理、化学、经济等）及特定主题的复习测验。
* ✨ **功能增强:**
    * 用户账户系统，用于保存学习进度与错题本。
    * 更详细的统计分析与学习建议。
    * 自定义测验模式（如按主题选定题目、错题重练等）。
* 🎨 **UI/UX 优化:** 根据用户反馈持续打磨用户界面和交互体验。
* 🌐 **多语言支持:** 考虑为界面提供更多语言选项。
* 🤝 **社区贡献:** 探索开放题目贡献与审核机制。

我们坚信，通过不断的迭代与创新，**IB Revision Toys** 将成为IB学生不可或缺的备考伙伴。

---

<p align="center">
  感谢您的关注与使用！祝您在IB的征途上一帆风顺，金榜题名！ 🎉
</p>
<p align="center">
  <em>&copy; 2024-2025 IB Revision Toys. Design & Made with Love by Jason Wang.</em>
</p>
