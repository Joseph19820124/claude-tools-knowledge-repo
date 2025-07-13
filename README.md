# Claude Tools Knowledge Repository

这是一个用于记录和分享 Claude 工具相关知识的仓库。

## 目录

- [工具列表](#工具列表)
- [使用指南](#使用指南)
- [最佳实践](#最佳实践)
- [常见问题](#常见问题)

## 工具列表

### 1. 内置工具
- **Web Search**: 网络搜索功能
- **Analysis Tool (REPL)**: JavaScript 代码执行环境
- **Artifacts**: 创建和管理代码片段、文档等

### 2. GitHub 集成
- 仓库管理
- 代码提交
- Issue 管理
- Pull Request 操作

### 3. Google 服务集成
- Gmail
- Google Drive
- Google Calendar

### 4. 其他集成
- Zapier
- Notion
- Airtable
- 更多...

## 使用指南

### 快速开始
1. 了解可用工具
2. 学习工具调用语法
3. 实践常见场景

### 示例代码
```javascript
// Analysis Tool 示例
const data = [1, 2, 3, 4, 5];
const sum = data.reduce((a, b) => a + b, 0);
console.log(`Sum: ${sum}`);
```

## 最佳实践

1. **明确需求**: 清楚地描述你想要完成的任务
2. **选择合适的工具**: 根据任务类型选择最合适的工具
3. **分步执行**: 复杂任务分解为小步骤
4. **验证结果**: 始终检查输出是否符合预期

## 常见问题

### Q: 如何查看所有可用的工具？
A: 使用 `zen:listmodels` 命令查看所有可用的 AI 模型和工具。

### Q: 如何使用 GitHub 集成？
A: Claude 可以直接帮你创建仓库、提交代码、管理 Issue 等。只需描述你的需求即可。

### Q: Analysis Tool 支持哪些库？
A: 支持 lodash、papaparse、xlsx、mathjs、d3 等常用库。

## 贡献

欢迎提交 Issue 或 Pull Request 来完善这个知识库！

## 许可证

MIT License

---

*最后更新: 2025年7月13日*
