# 贡献指南

感谢你关注本项目！欢迎提交 Issue 和 Pull Request。

## 如何贡献

### 报告 Bug
1. 在 [Issues](https://github.com/your-repo/salary-calculator/issues) 中搜索是否已存在类似问题
2. 如果不存在，新建 Issue，描述：
   - 问题现象
   - 复现步骤
   - 期望行为
   - 浏览器版本
   - 截图（如适用）

### 提出新功能
1. 先讨论后实现：在 Issue 中说明功能需求和价值
2. 遵循 KISS 原则：保持简单，拒绝过度设计
3. 确保不破坏现有功能

### 提交代码
1. Fork 本仓库
2. 创建特性分支：`git checkout -b feature/amazing-feature`
3. 提交更改：`git commit -m 'Add some amazing feature'`
4. 推送到分支：`git push origin feature/amazing-feature`
5. 开启 Pull Request，描述变更内容和动机

---

## 开发规范

### 代码风格
- 使用 2 空格缩进（HTML/CSS/JS）
- 遵循现有代码风格
- 保持函数短小单一职责
- 添加必要注释（但代码应自解释）

### 提交信息规范
```
类型(范围): 简要描述

详细说明（如需要）

类型：feat, fix, docs, style, refactor, test, chore
范围：可选，如 ui, calc, storage 等
```

示例：
```
feat(ui): 添加全屏显示功能

- 点击金额数字可全屏展示
- 使用 ESC 或点击退出全屏
- 全屏金额强制不换行并自适应字号
```

### 测试
- 修改后手动测试核心流程
- 确保 LocalStorage 功能正常
- 验证移动端兼容性

---

## 项目原则

- **零依赖**：保持纯前端，不引入任何外部库
- **隐私优先**：所有数据只存在本地，不收集用户信息
- **性能第一**：保持轻量快速，100ms 刷新频率
- **用户体验**：界面简洁，操作直观

---

有问题欢迎随时讨论！🚀