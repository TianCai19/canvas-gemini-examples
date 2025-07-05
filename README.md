# Canvas Gemini 示例项目集

## 🌐 在线演示入口

| 项目名称                 | 在线演示链接 |
|------------------------|:---------------------------------------------------------------:|
| 文章转图片生成器        | [点击访问](https://g.co/gemini/share/18fa96a05aa3)              |
| Gemini 图像分析工具     | [点击访问](https://gemini.google.com/share/72f0e7a4896e)        |
| 人脸检测计时器          | [点击访问](https://g.co/gemini/share/442fea86860f)              |
| 盲盒邮件生成器          | [点击访问](https://g.co/gemini/share/ab7e35732f53)              |
| 强化学习教程            | [点击访问](https://gemini.google.com/share/ea41cb14967b)        |
| 强化学习教程 V2         | [点击访问](https://g.co/gemini/share/b922541eaa03)              |
| 吃什么转盘              | [点击访问](https://g.co/gemini/share/bcd66c1c158b)              |

> 其余 demo（如体态健康检测、手指关节检测）暂未提供在线演示链接，可本地运行体验。

这个仓库包含了使用 Canvas 和 Gemini 构建的各种示例和工具。每个项目都展示了不同的 AI 应用场景，从图像分析到强化学习，帮助开发者更好地理解和应用这些技术。

## 🚀 快速开始

### 本地运行方式

所有项目都是基于HTML的独立应用，可以通过以下两种方式运行：

#### 方法一：使用Python HTTP服务器（推荐）
```bash
# 在项目根目录下运行
python3 -m http.server 8000

# 如果8000端口被占用，可以使用其他端口
python3 -m http.server 8080
```

然后在浏览器中访问：
- **项目总览：** http://localhost:8000/
- **Gemini图像分析：** http://localhost:8000/gemini-image-summary/index.html
- **人脸检测计时器：** http://localhost:8000/face-detection-timer/index.html
- **盲盒邮件生成器：** http://localhost:8000/mail-generater/index.html
- **强化学习教程：** http://localhost:8000/RL-tutorial/index.html
- **体态健康检测：** http://localhost:8000/body-health-detection/index.html
- **手指关节检测：** http://localhost:8000/finger-joint-detection/index.html
- **文章转图片生成器：** http://localhost:8000/article2picture-generater/index.html
- **吃什么转盘：** http://localhost:8000/eatWhat/index.html

#### 方法二：直接在浏览器中打开
直接双击各个项目文件夹中的 `index.html` 文件，浏览器会自动打开。

> **注意：** 某些功能（如摄像头访问、文件上传）可能需要HTTPS环境才能正常工作，建议使用HTTP服务器方式运行。

## 项目列表

### 📝 文章转图片生成器
一个强大的内容可视化工具，可以将文章内容转换为精美的图片格式。功能包括：
- 多页面内容编辑和预览
- 多种宽高比选择（自动、1:1方形、4:5竖屏、9:16故事）
- 智能缩放规则（平衡、宽度优先、高度优先、极简稳定）
- 实时编辑模式，支持内容自定义
- 单页下载和批量打包下载（ZIP格式）
- 响应式设计和现代化UI

使用方法：
1. 在网页浏览器中打开 `article2picture-generater/index.html`
2. 选择合适的内容比例和缩放规则
3. 开启编辑模式自定义内容
4. 预览效果后下载单页或全部页面

**在线演示：** [文章转图片生成器](https://g.co/gemini/share/18fa96a05aa3)

### 🖼️ Gemini 图像分析工具
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

### ⏰ 人脸检测计时器
这个项目结合了AI人脸检测和时间追踪功能，可以记录用户在摄像头前的总时长。特点：
- 实时人脸检测（基于COCO-SSD模型）
- 精确的时长累计和显示
- 数据本地持久化存储
- 用户友好的重置确认机制
- 现代化的UI设计和动画效果

使用方法：
1. 在网页浏览器中打开 `face-detection-timer/index.html`
2. 允许摄像头访问权限
3. 站在摄像头前，应用会自动检测并累计时长
4. 即使关闭页面，时长数据也会被保存
5. 可以通过"重置时长"按钮清除记录

**技术亮点：** 展示了完整的前端数据持久化解决方案

**在线演示：** [人脸检测计时器](https://g.co/gemini/share/442fea86860f)

### ✉️ 盲盒邮件生成器
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

**在线演示：** [盲盒邮件生成器](https://g.co/gemini/share/ab7e35732f53)

### 🤖 强化学习教程
一个 Q-Learning 的交互式可视化演示，展示 AI 智能体如何通过试错来寻找宝藏。通过这个项目，你可以：
- 直观地理解强化学习的基本概念
- 观察智能体的学习过程
- 探索 Q-Learning 算法的核心原理
- 通过实践加深对强化学习的理解

**在线演示：** [强化学习教程](https://gemini.google.com/share/ea41cb14967b)

**版本2：** [强化学习教程 V2](https://g.co/gemini/share/b922541eaa03)

### 🍽️ 吃什么转盘
一个有趣的饮食决策工具，帮助用户通过旋转轮盘的方式决定今天吃什么。功能特色：
- 精美的旋转轮盘动画效果
- 多种国际美食选项（韩国料理、泰国料理、日本料理、印度料理、墨西哥菜、越南菜、中东菜）
- 流畅的旋转动画和悬停效果
- 结果弹窗展示
- 响应式设计，适配移动设备

使用方法：
1. 在网页浏览器中打开 `eatWhat/index.html`
2. 点击"开始旋转"按钮
3. 等待转盘停止旋转
4. 查看弹窗显示的随机选择结果

**技术亮点：** 使用 Canvas 绘制轮盘，结合 CSS 动画实现流畅的旋转效果

**在线演示：** [吃什么转盘](https://g.co/gemini/share/bcd66c1c158b)

### 🖐️ 手指关节检测
这个项目使用 TensorFlow.js 和预训练的手部姿态检测模型（MediaPipe Hands）来识别上传图片中伸出的手指数量。特点：
- 实时手部姿态检测
- 精确的手指数量识别
- 直观的可视化效果
- 轻量级的网页实现

### 💪 体态健康检测
这个项目使用 TensorFlow.js 和 MoveNet 姿态检测模型来实时监控你的坐姿，并提供符合人体工程学的反馈。功能包括：
- 实时姿势追踪
- 不良姿势提醒
- 人体工程学建议
- 长时间使用提醒

## 开发经验与技术指南

### HTML数据持久化最佳实践
在前端HTML应用中实现数据持久化是提升用户体验的关键技术。以`face-detection-timer`项目为例，展示了完整的本地数据存储方案：

#### 1. localStorage基础应用
```javascript
// 常量定义，避免键名错误
const LOCAL_STORAGE_KEY = 'aiFaceDetectionTotalDurationMs';

// 保存数据
function saveDurationToLocalStorage() {
    localStorage.setItem(LOCAL_STORAGE_KEY, totalDetectedDurationMs.toString());
}

// 加载数据
function loadDurationFromLocalStorage() {
    const savedDuration = localStorage.getItem(LOCAL_STORAGE_KEY);
    if (savedDuration !== null) {
        totalDetectedDurationMs = parseInt(savedDuration, 10);
    } else {
        totalDetectedDurationMs = 0; // 默认值
    }
    updateDurationDisplay(); // 立即更新界面
}
```

#### 2. 实时数据同步策略
- **频繁保存**：在每帧检测中都调用保存函数，确保数据不丢失
- **页面加载时恢复**：`window.onload`事件中首先执行数据加载
- **类型转换处理**：localStorage只存储字符串，需要适当的类型转换

#### 3. 用户友好的数据管理
```javascript
// 安全的数据重置，带确认提示
function resetDuration() {
    totalDetectedDurationMs = 0;
    localStorage.removeItem(LOCAL_STORAGE_KEY);
    updateDurationDisplay();
}
```

#### 4. 数据持久化的关键要点
- **错误处理**：localStorage可能在隐私模式下不可用
- **存储限制**：注意浏览器的存储配额限制
- **数据版本管理**：考虑应用更新时的数据兼容性
- **用户控制**：提供清除数据的选项

这种持久化方案特别适合单页面应用和AI工具，能够：
- 保持用户的使用状态和历史记录
- 提供离线使用能力
- 减少服务器依赖
- 改善整体用户体验

### Gemini Canvas 开发环境
在使用 Gemini Canvas 进行开发时，有一个重要的便利性特点需要了解：
- **Canvas 环境内置 API 支持**：在 Gemini Canvas 环境中开发时，Gemini API 是默认配置好的，无需手动设置 API 密钥或进行额外的环境配置
- **本地开发需要配置**：如果将项目下载到本地运行，则需要手动配置 Gemini API 密钥和相关环境变量
- **开发流程建议**：建议先在 Canvas 环境中进行原型开发和功能验证，确认效果后再迁移到本地环境进行进一步开发

### 大模型输出处理技巧
在处理大模型输出内容时，有一个重要的用户体验优化点：
- **Markdown 渲染优化**：大模型（如 Gemini）的输出通常采用 Markdown 格式，包含标题、列表、粗体等格式化内容
- **渲染库集成**：可以要求 AI 使用 Markdown 语法库（如 marked.js 或 markdown-it）来渲染这些文本，显著提升内容的可读性
- **实际应用案例**：在 `gemini-image-summary` 项目中，通过 Markdown 渲染可以让图像分析结果更加结构化和美观，包括：
  - 层次化的标题结构
  - 格式化的列表和要点
  - 强调文本和代码块
- **用户体验提升**：相比纯文本输出，Markdown 渲染能让用户更容易理解和浏览 AI 生成的内容

### 技术选型与能力边界
在开发这些项目的过程中，我们发现了解 HTML 和 JavaScript 的基础能力边界至关重要。例如：
- **轻量化模型的应用**：选择适合浏览器端运行的模型，如 YOLO 的轻量化版本，能够在保证性能的同时实现实时检测
- **Canvas API 的充分利用**：HTML5 Canvas 提供了强大的图形渲染能力，适合构建交互式的 AI 应用界面
- **模型加载与优化**：合理的模型加载策略和缓存机制能显著提升用户体验

### 现代 AI 开发范式
传统的前端开发思维需要在 AI 时代进行转变：
- **从功能导向到能力导向**：不再局限于传统的 DOM 操作，而是思考如何整合 AI 能力来解决实际问题
- **大模型 API 的深度集成**：通过 Gemini API 等大模型接口，可以快速实现复杂的 AI 功能，如图像理解、自然语言处理等
- **声明式 AI 编程**：直接向 AI 描述需求和期望的输出，让模型来处理复杂的逻辑实现
- **快速原型到产品**：利用 Canvas 和 Gemini 的组合，可以快速从概念验证发展到可用的产品

### 最佳实践建议
1. **渐进式增强**：从基础的 HTML 实现开始，逐步集成 AI 能力
2. **用户体验优先**：确保 AI 功能的响应速度和准确性满足实际使用需求
3. **错误处理与回退**：为 AI 调用失败的情况设计合理的降级方案
4. **性能监控**：关注模型加载时间、推理速度等关键性能指标
5. **环境适配**：考虑 Canvas 环境和本地环境的差异，做好相应的配置管理

## 技术栈
- TensorFlow.js
- MediaPipe
- Gemini AI
- HTML5 Canvas
- Tailwind CSS

## 贡献
欢迎提交 Issue 和 Pull Request 来帮助改进这些项目。如果你有任何问题或建议，请随时提出。

## 许可证
MIT License