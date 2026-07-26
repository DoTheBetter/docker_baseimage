# Copilot 使用说明

## 语言要求

- 所有回答、解释和讨论请使用**简体中文**。
- 代码注释请使用中文编写。
- 如果用户用中文提问，必须用中文回答。

## 项目背景

本仓库用于构建和维护多个 Docker 基础镜像，仓库主要包含：

- `dockerfiles/`：各镜像的 Dockerfile
- `build_files/`：构建所需的资源文件
- `versions/`：各组件版本号记录
- `.github/workflows/`：GitHub Actions 自动化构建工作流

## 回答风格

- 简洁直接，优先给出可执行的命令或代码。
- 涉及 Dockerfile、Shell 脚本、GitHub Actions 时，说明变更原因和影响范围。
- 涉及版本更新时，说明需要同步修改的文件（如 versions/ 下的对应文件）。
- 当 GitHub Actions 运行失败时，先分析失败日志中的关键错误信息，再给出排查步骤；如需重新触发构建，说明可用的手动触发方式或需要推送的变更。
