# Miya · 三三的小手机

*A little digital world, growing one piece at a time.*

> **私人开发中 · WorkBuddy 工程待迁移**
>
> 当前仓库保留的是已有 GitHub 代码快照，不代表 WorkBuddy 本地开发的最新版本。迁移、差异核验和回归测试完成前，请勿将它视为最终发布版。

## 关于项目

Miya 是一个浏览器中的交互式「小手机」项目，包含桌面与系统界面、聊天与角色互动、个性化设置以及场景化应用。现有快照使用 HTML、CSS 和原生 JavaScript，并包含 PWA 相关文件。

项目最初基于 [lixooo00-lab/mingruis-miya](https://github.com/lixooo00-lab/mingruis-miya) 开始探索。此后，三三在 WorkBuddy 本地环境中进行了持续开发，包括关系真实感、娱乐模块与 PC 体验等协作方向。相关成果尚未完整迁移到本仓库。

## 当前状态

- **GitHub 快照**：作为迁移基线保留。
- **WorkBuddy 本地工程**：待完整备份与迁移。
- **历史测试**：交流板记录了 main 398、sansan 368、pc-agent 30，以及娱乐模块 E2E 132 passed / 0 failed。这些均为历史记录，**尚未在新环境重新验证**。
- **发布状态**：暂无经迁移验收的正式版本。

## 迁移清单

- [ ] 完整备份 WorkBuddy 工程及开发日志
- [ ] 核对 main / sansan / pc-agent 历史分支与分叉点
- [ ] 保全未合并改动，逐文件检查冲突
- [ ] 核对 `sw.js`、`index.html`、lazy-boot、`app.js` 和 `store.js`
- [ ] 迁移本地模块与必要资源
- [ ] 恢复测试环境，运行回归及端到端测试
- [ ] 在实际设备上验收后建立新的开发基线

## 协作约定

开发前先阅读最新交流板、其他工作线的改动与上一轮留痕；开发后记录变更、测试和待办。冲突按**文件与行区**判断，先比较方案和依据，不对其他 Agent 归责；无法达成一致时，由项目所有者裁决。

未经核验，不覆盖原始工程、不丢弃分支、不将历史测试报告冒充当前测试结果。

## 来源与许可

本项目源自 [lixooo00-lab/mingruis-miya](https://github.com/lixooo00-lab/mingruis-miya)，感谢原作者的开源工作。

仓库保留原有 `LICENSE`（AGPL-3.0）。保留或衍生自原项目的代码仍须遵守适用的版权声明和许可义务；私人开发及解除 Fork 关联不会自动取消这些义务。后续公开分发前将另行核对代码来源和许可。

## Maintainer

**3William33**

*Some little worlds take time to grow. This one is worth keeping.*
