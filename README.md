# Canvas Gemini 示例项目集

这个仓库包含了使用 Canvas 和 Gemini 构建的各种示例和工具。

## 项目列表

### Gemini 图像分析工具
一个基于网页的工具，使用 Google 的 Gemini AI 来分析和总结图片。功能包括：
- 支持拖放或文件选择上传图片
- AI 驱动的图像分析和描述
- 实时反馈和结果显示
- 响应式设计的现代界面

使用方法：
1. 在网页浏览器中打开 `gemini-image-summary/index.html`
2. 通过拖放或文件选择上传图片
3. 等待 AI 分析并提供总结
4. 查看图片的详细描述

**在线演示：** [Gemini 图像分析工具](https://gemini.google.com/share/72f0e7a4896e)

### 盲盒邮件生成器
一个基于网页的工具，用于生成笔友之间的盲盒邮件配对。功能包括：
- 简洁的参与者信息输入界面
- 可自定义的邮件模板
- 自动生成配对邮件
- 一键复制功能
- 使用 Tailwind CSS 构建的现代界面

使用方法：
1. 在网页浏览器中打开 `mail-generater/index.html`
2. 输入参与者信息（笔名和邮箱）
3. 根据需要自定义邮件模板
4. 点击"生成"创建配对邮件

### 其他项目
- RL-tutorial（强化学习教程）
- body-health-detection（体态健康检测）
- finger-joint-detection（手指关节检测）

## 手指关节检测

这个项目使用 TensorFlow.js 和预训练的手部姿态检测模型（MediaPipe Hands）来识别上传图片中伸出的手指数量。

### 运行方法

1. 在网页浏览器中打开 `finger-joint-detection/index.html` 文件
2. 等待模型加载完成
3. 点击"上传图片"按钮并选择一张手部图片
4. AI 将分析图片，绘制手部骨架，并显示检测到的手指数量

## 体态健康检测

这个项目使用 TensorFlow.js 和 MoveNet 姿态检测模型来实时监控你的坐姿，并提供符合人体工程学的反馈。

### 运行方法

1. 在网页浏览器中打开 `body-health-detection/index.html` 文件
2. 允许访问摄像头
3. 坐在摄像头前，系统将追踪你的姿势
4. 当你驼背、歪头或保持不良姿势时间过长时，系统会发出提醒

## 强化学习教程

一个 Q-Learning 的交互式可视化演示，展示 AI 智能体如何通过试错来寻找宝藏。

### 运行方法

1. 在网页浏览器中打开 `RL-tutorial/index.html` 文件
2. 点击"开始训练"观看智能体学习过程
3. 切换显示选项查看 Q 表（智能体的记忆）和决策日志
4. 查看理论页面了解 Q-Learning 的基本原理