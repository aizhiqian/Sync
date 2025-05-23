# GitHub 同步工具

这是一个用于自动同步 GitHub 仓库和文件的工具集。通过 GitHub Actions 实现自动化同步操作，支持仓库和单文件的定时同步及手动触发。

## 功能特性

### 1. 仓库同步
- 每月 1 号 1 点自动同步一次
- 支持手动触发同步
- 当前同步的仓库：
  - [IDM-Activation-Script](https://github.com/lstprjct/IDM-Activation-Script)

### 2. 文件同步
- 每天凌晨 2 点自动同步一次
- 支持手动触发同步
- 当前同步的文件：
  - [jd.txt](https://raw.githubusercontent.com/WeiGiegie/vpm/main/lq.snippet)


## 自动化特性

- **文档同步**：工作流会自动更新此 README.md 的仓库和文件列表
- **智能提交**：仅在发现更改时才创建新的提交
- **提交信息**：自动生成包含更新项目的提交信息

## 注意事项

- 所有同步操作都会自动提交并推送更改
- 仓库同步会保持目标目录的完整性（删除不存在的文件）
- 文件同步会直接覆盖本地文件