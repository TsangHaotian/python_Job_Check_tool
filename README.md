# 作业管理系统 📂✅

![GitHub stars](https://img.shields.io/github/stars/TsangHaotian/python_Job_Check_tool?style=social)
![GitHub forks](https://img.shields.io/github/forks/TsangHaotian/python_Job_Check_tool?style=social)

一套自动化作业管理工具组合，包含文件批量提取器和作业检查工具，专为教育场景设计的效率解决方案


## 🚀 核心功能

### 文件批量提取器
- 智能识别文件名关键词/后缀
- 批量移动指定类型文件
- 支持正则表达式匹配
- 操作日志记录
- 可视化进度提示

### 作业检查工具
- Excel名单自动比对
- 提交状态实时统计
- 未交名单生成
- 多班级管理支持
- 智能重名检测
- 数据可视化报表

## ⚙️ 工作流程
1. **文件提取** ➡️ 2. **名单比对** ➡️ 3. **结果导出**
```mermaid
graph LR
    A[杂乱文件夹] --> B{文件提取器}
    B --> C[整理后的作业]
    C --> D{作业检查工具}
    D --> E[已提交名单]
    D --> F[未提交名单]



##📦 安装指南

### 直接使用（推荐）
1. 下载最新release的exe文件
2. 双击运行对应工具：
   - `文件批量提取器.exe`
   - `作业检查工具.exe`