# GitHub Achievement Lab

> A sandbox repository for safely testing GitHub profile achievement workflows.
> 用来安全测试 GitHub 成就解锁流程的实验场。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Sandbox](https://img.shields.io/badge/purpose-sandbox-blue)](https://github.com/491034170/github-achievement-lab)

## 为什么 / Why

GitHub profile 上的 achievement badge(Pull Shark、Quickdraw、YOLO、Galaxy Brain、Pair Extraordinaire 等)触发规则并不完全公开。在生产仓库里尝试,会把测试用的 PR / Issue 留在主项目中,破坏作品集观感。

本仓库是一个 **完全隔离的沙箱**:所有触发实验都发生在这里,既能解锁 achievement,又不污染正经项目。

The unlock rules for GitHub achievements aren't fully documented — and testing them in production clutters your portfolio. This repo is a contained sandbox where experiments happen safely.

## 目标徽章 / Achievement Targets

| Badge | 触发条件 / Trigger |
|---|---|
| 🦈 **Pull Shark** | 合并 N 个 PR / Merge N pull requests |
| ⚡ **Quickdraw** | 5 分钟内关闭 Issue 或 PR / Close within 5 min |
| 🎰 **YOLO** | 不经 review 合并 PR / Merge without review |
| 🧠 **Galaxy Brain** | 2+ 个被接受的 discussion 答案 / 2+ accepted answers |
| 👥 **Pair Extraordinaire** | co-author 提交 / Co-authored commit |
| 🚀 **Starstruck** | 仓库获 16+ star |

## 目录结构 / Structure

- `notes/` — 每个 achievement 的观察笔记与触发方式记录
- test issues / PRs / discussions — 真实的触发载体

## License

MIT © 天智工坊 · Tianmind Studio
