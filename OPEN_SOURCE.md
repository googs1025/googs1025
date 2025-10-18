# Open Source Contributions

> 本页汇总我在云原生与大模型推理方向的开源贡献，涵盖 Kubernetes 核心、调度生态及 Aibrix 项目。

---

## Kubernetes (Org Member)

- **Focus Areas**: sig-scheduler, sig-cli (kubectl)
- **Contributions**:
    - 提交 60+ PRs，涵盖小特性开发、边界 case 修复、单元测试增强；
    - 参与社区 Issue 讨论与 PR Review，协助新贡献者入门；
    - 关注调度器扩展性与 CLI 工具易用性。
- [View my PRs](https://github.com/kubernetes/kubernetes/pulls?q=is%3Amerged+is%3Apr+author%3Agoogs1025+)

---

## Aibrix (Maintainer)

- **Project**: 云原生大模型推理平台
- **Key Contributions**:
    - 聚焦大模型在线推理场景，协同设计与实现包括PD分离(StormService [#1229](https://github.com/vllm-project/aibrix/pull/1229))、动态扩缩容(PodAutoScaler [#1422](https://github.com/vllm-project/aibrix/issues/1422))等核心能力
    - 特性开发([#1601](https://github.com/vllm-project/aibrix/pull/1601) [#1448](https://github.com/vllm-project/aibrix/pull/1448) [#1457](https://github.com/vllm-project/aibrix/pull/1457) [#1403](https://github.com/vllm-project/aibrix/pull/1403))、bugfix([#1662](https://github.com/vllm-project/aibrix/pull/1662))
- [View my PRs](https://github.com/vllm-project/aibrix/pulls?q=is%3Apr+author%3Agoogs1025+is%3Aclosed)

---

## Koordinator (Member)

- **Project**: 资源调度与 QoS 保障，面向混部与大模型场景
- **Key Contributions**:
    - 关注资源预占（Resource Reservation）能力（[#2368](https://github.com/koordinator-sh/koordinator/pull/2368), [#2390](https://github.com/koordinator-sh/koordinator/pull/2390), [#2402](https://github.com/koordinator-sh/koordinator/pull/2402), [#2533](https://github.com/koordinator-sh/koordinator/pull/2533)）；
    - 重调度器（Rescheduler）增强（[#2566](https://github.com/koordinator-sh/koordinator/issues/2566)）。
- [View my PRs](https://github.com/koordinator-sh/koordinator/pulls?q=is%3Apr+author%3Agoogs1025+is%3Aclosed)

---

## Volcano (Member)

- **Project**: 批处理与 AI 作业调度
- **Key Contributions**:
    - 增强 `vcctl` 命令行工具，支持作业状态过滤、事件查看等实用功能([issue](https://github.com/volcano-sh/volcano/issues/3495))；
    - 对 scheduler 中插件进行代码重构
    - 在社区中主动认领 Issue 并 Review 社区 PR。
- [View my PRs](https://github.com/volcano-sh/volcano/pulls?q=is%3Amerged+is%3Apr+author%3Agoogs1025+)

---

## Descheduler (Reviewer)

- **Project**: 集群资源优化与 Pod 驱逐策略
- **Key Contributions**:
    - 特性开发([#1603](https://github.com/kubernetes-sigs/descheduler/pull/1603) [#1665](https://github.com/kubernetes-sigs/descheduler/pull/1665))
    - bugfix([#1629](https://github.com/kubernetes-sigs/descheduler/pull/1629))
    - 获社区信任，成为 Reviewer，参与 PR 质量把控。
- [View my PRs](https://github.com/kubernetes-sigs/descheduler/pulls?q=is%3Amerged+is%3Apr+author%3Agoogs1025+)

---
