# Project Portfolio / 项目作品集

[返回个人主页 / Back to Profile](README.md)

## 1. Linux & System Operations

| Project | Description | Tech Stack |
| --- | --- | --- |
| [`tyro_linux`](https://github.com/Shaohan-He/tyro_linux) | Linux 服务器初始化、系统加固、防火墙配置、基础监控和审计脚本库。 | Bash, Linux, Firewall, SSH, Cron |
| [`node-guardian`](https://github.com/Shaohan-He/node-guardian) | 面向 Kubernetes 节点的预检、诊断、安全审计和配置备份工具。 | Bash, Kubernetes, ShellCheck, BATS |

---

## 2. Kubernetes & Cloud Native Operations

| Project | Description | Tech Stack |
| --- | --- | --- |
| [`node-health-watcher`](https://github.com/Shaohan-He/node-health-watcher) | 基于 SSH 的 Kubernetes 节点巡检和告警工具，支持磁盘、内存、conntrack、kubelet 和内核日志检查。 | Python, SSH, Kubernetes, DingTalk, Feishu |
| [`fleet-gitops`](https://github.com/Shaohan-He/fleet-gitops) | 基于 Argo CD、Argo Rollouts 和 Kustomize 的 Kubernetes GitOps 交付配置仓库。 | Argo CD, Argo Rollouts, Kustomize, Kubernetes |
| [`k8s-healing-agent`](https://github.com/Shaohan-He/k8s-healing-agent) | 实验性的 Kubernetes 告警诊断与辅助修复服务，接收 Alertmanager Webhook 并收集故障上下文。 | Python, FastAPI, Kubernetes, Alertmanager |

---

## 3. Observability & Troubleshooting

| Project | Description | Tech Stack |
| --- | --- | --- |
| [`fleet-observability`](https://github.com/Shaohan-He/fleet-observability) | Kubernetes 可观测性配置仓库，覆盖 Prometheus、Loki、Grafana、Alertmanager、SLO 告警和日志查询。 | Prometheus, Loki, Grafana, Alertmanager |
| [`node-guardian`](https://github.com/Shaohan-He/node-guardian) | 节点故障场景下的信息收集、诊断和变更前配置备份。 | Bash, Linux, Kubernetes |

---

## 4. Release Engineering & DevOps

| Project | Description | Tech Stack |
| --- | --- | --- |
| [`fleet-gitops`](https://github.com/Shaohan-He/fleet-gitops) | 使用 Git 管理多环境 Kubernetes 配置，支持 dev、staging、production 环境差异管理。 | GitOps, Argo CD, Kustomize |
| [`game-release-pipeline`](#game-release-pipeline) | 计划中的业务服务发布流水线项目，覆盖镜像构建、测试环境发布、灰度发布、健康检查和回滚流程。 | GitHub Actions, Docker, Kubernetes, Shell |

---

## 5. Business & Game Ops Scenarios

| Project | Description | Tech Stack |
| --- | --- | --- |
| [`game-k8s-ops-practice`](#game-k8s-ops-practice) | 游戏业务系统容器化部署与运维实践，覆盖网关、登录、匹配、房间服务、MySQL、Redis、Kafka、监控告警、日志排查和版本回滚。 | Docker, Kubernetes, FastAPI, MySQL, Redis, Kafka, Prometheus |
| [`game-server-ops-toolkit`](#game-server-ops-toolkit) | 计划中的游戏区服运维工具箱，覆盖开服、停服维护、配置更新、备份、合服前检查和操作记录。 | Bash, Linux, MySQL, Nginx |
| [`game-fleet-director`](#game-fleet-director) | 游戏服生命周期管理实践，关注玩家数伸缩、优雅排水、暖池和节点健康感知。 | Go, Kubernetes Operator, CRD |

---

## 6. Automation & AI-assisted Tools

| Project | Description | Tech Stack |
| --- | --- | --- |
| [`deepseek-eyes`](https://github.com/Shaohan-He/deepseek-eyes) | 为文本模型补充视觉理解能力的 MCP 工具，通过截图、剪贴板和视觉模型生成图片描述。 | Python, MCP, Qwen-VL, ModelScope |

---

## Planned Projects / 计划项目

### game-release-pipeline

计划中的业务服务发布流水线项目。
Planned release pipeline project for business services.

### game-k8s-ops-practice

游戏业务系统容器化部署与运维实践。
Containerized deployment and operations practice for game services.

### game-server-ops-toolkit

计划中的游戏区服运维工具箱。
Planned operations toolkit for game server management.

### game-fleet-director

游戏服生命周期管理实践。
Game server lifecycle management practice.

[返回个人主页 / Back to Profile](README.md)
