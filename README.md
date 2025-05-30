# 个人助手全栈开发系统

🥳本项目是一个集成多种实用功能的个人助手应用，旨在提升日常学习与生活效率。系统采用全栈开发，界面友好，功能丰富。

## 主要功能

- **背单词**🎒：
  - 提供单词记忆、复习与测试功能，助力英语学习。
- **音乐播放**：🎶
  - 支持本地音乐播放，界面简洁，操作便捷。
- **天气预报**：🌈
  - 实时获取天气信息，支持多城市查询，数据来源权威。
- **AI 查询**：🤖
  - 集成AI助手，支持智能问答、知识查询等。

## 快速上手

### 环境要求
- .NET 8.0 及以上
- 推荐使用 Windows

### 安装与运行
1. 克隆项目：
   ```bash
   git clone <你的仓库地址>
   cd PPH
   ```
2. 还原依赖：
   ```bash
   dotnet restore
   ```
3. 编译项目：
   ```bash
   dotnet build
   ```
4. 运行主程序：
   ```bash
   dotnet run --project PPH/PPH.csproj
   ```

### 功能入口
- 启动后，主界面可访问所有功能模块。
- 各功能均有独立页面，按需切换。

## 目录结构说明

- `PPH/`：主程序及前端界面
- `PPH.Library/`：通用库与数据模型
- `PPH.UnitTest/`：单元测试代码

## 常见问题与支持

- 如遇依赖问题，请确保已安装 .NET 8.0 及以上版本。
- 反馈问题或建议，请通过 issue 提交。

---

欢迎使用和贡献本项目！
