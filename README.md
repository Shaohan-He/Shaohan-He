# Hi, I'm Shaohan He 👋

- 我是一名初级 DevOps / 云原生运维方向学习者，关注 Linux、容器化、Kubernetes 运维和自动化工具建设。
- I am an entry-level DevOps and cloud-native operations learner, focusing on Linux, containerization, Kubernetes operations, and automation tooling.

我的项目主要围绕以下几个方向展开：
My projects are organized around the following areas:

- Linux & 基础运维 / Linux & System Operations
- Kubernetes & 云原生运维 / Kubernetes & Cloud Native Operations
- 监控告警与故障排查 / Observability & Troubleshooting
- 发布工程与 GitOps / Release Engineering & GitOps
- 业务系统与游戏运维场景 / Business and Game Ops Scenarios
- 自动化工具与 AI 辅助工具 / Automation and AI-assisted Tools

---

## 🧭 Project Portfolio

### 1. Linux & System Operations

| Project | Description | Tech Stack |
| --- | --- | --- |
| `tyro_linux` | Linux 服务器初始化、系统加固、防火墙配置、基础监控和审计脚本库。 | Bash, Linux, Firewall, SSH, Cron |
| `node-guardian` | 面向 Kubernetes 节点的预检、诊断、安全审计和配置备份工具。 | Bash, Kubernetes, ShellCheck, BATS |

---

### 2. Kubernetes & Cloud Native Operations

| Project | Description | Tech Stack |
| --- | --- | --- |
| `node-health-watcher` | 基于 SSH 的 Kubernetes 节点巡检和告警工具，支持磁盘、内存、conntrack、kubelet 和内核日志检查。 | Python, SSH, Kubernetes, DingTalk, Feishu |
| `fleet-gitops` | 基于 Argo CD、Argo Rollouts 和 Kustomize 的 Kubernetes GitOps 交付配置仓库。 | Argo CD, Argo Rollouts, Kustomize, Kubernetes |
| `k8s-healing-agent` | 实验性的 Kubernetes 告警诊断与辅助修复服务，接收 Alertmanager Webhook 并收集故障上下文。 | Python, FastAPI, Kubernetes, Alertmanager |

---

### 3. Observability & Troubleshooting

| Project | Description | Tech Stack |
| --- | --- | --- |
| `fleet-observability` | Kubernetes 可观测性配置仓库，覆盖 Prometheus、Loki、Grafana、Alertmanager、SLO 告警和日志查询。 | Prometheus, Loki, Grafana, Alertmanager |
| `node-guardian` | 节点故障场景下的信息收集、诊断和变更前配置备份。 | Bash, Linux, Kubernetes |

---

### 4. Release Engineering & DevOps

| Project | Description | Tech Stack |
| --- | --- | --- |
| `fleet-gitops` | 使用 Git 管理多环境 Kubernetes 配置，支持 dev、staging、production 环境差异管理。 | GitOps, Argo CD, Kustomize |
| `game-release-pipeline` | 计划中的业务服务发布流水线项目，覆盖镜像构建、测试环境发布、灰度发布、健康检查和回滚流程。 | GitHub Actions, Docker, Kubernetes, Shell |

---

### 5. Business & Game Ops Scenarios

| Project | Description | Tech Stack |
| --- | --- | --- |
| `game-k8s-ops-practice` | 游戏业务系统容器化部署与运维实践，覆盖网关、登录、匹配、房间服务、MySQL、Redis、Kafka、监控告警、日志排查和版本回滚。 | Docker, Kubernetes, FastAPI, MySQL, Redis, Kafka, Prometheus |
| `game-server-ops-toolkit` | 计划中的游戏区服运维工具箱，覆盖开服、停服维护、配置更新、备份、合服前检查和操作记录。 | Bash, Linux, MySQL, Nginx |
| `game-fleet-director` | 游戏服生命周期管理实践，关注玩家数伸缩、优雅排水、暖池和节点健康感知。 | Go, Kubernetes Operator, CRD |

---

### 6. Automation & AI-assisted Tools

| Project | Description | Tech Stack |
| --- | --- | --- |
| `deepseek-eyes` | 为文本模型补充视觉理解能力的 MCP 工具，通过截图、剪贴板和视觉模型生成图片描述。 | Python, MCP, Qwen-VL, ModelScope |

---

## 🛠️ Skills / 技术栈

- 操作系统 / Operating Systems: Linux, CentOS, Ubuntu, Rocky Linux, systemd, crontab, journalctl, sysctl, firewalld, iptables, SELinux, SSH
- 网络基础 / Networking: TCP/IP, DNS, HTTP, HTTPS, NAT, SSL/TLS, Load Balancing, Routing, Firewall, Port, Nginx Reverse Proxy, Packet Capture
- Web 服务 / Web Services: Nginx, Tomcat, Apache, Virtual Host, Static File Hosting, Reverse Proxy, Access Log, Error Log
- 数据库与缓存 / Databases and Cache: MySQL, PostgreSQL, MongoDB, Redis, Backup and Recovery, Replication, Slow Query, Data Migration
- 容器化 / Containerization: Docker, Dockerfile, Docker Compose, Container Network, Volume, Image Build, Image Tag, Image Push, Harbor
- Kubernetes / Kubernetes: Kubernetes, kubectl, YAML, Pod, Deployment, StatefulSet, DaemonSet, Service, Ingress, ConfigMap, Secret, PVC, PV, StorageClass, Namespace, RBAC, Helm, Kustomize
- GitOps / GitOps: Argo CD, Argo Rollouts, App of Apps, Helm Chart, Kustomize Overlay, Rollout, AnalysisTemplate
- CI/CD / CI/CD: Git, GitHub, GitLab, GitLab CI/CD, Jenkins, Jenkins Pipeline, GitHub Actions, CI Pipeline, CD Pipeline, Build, Test, Release, Rollback
- 监控告警 / Monitoring and Alerting: Prometheus, Grafana, Alertmanager, Zabbix, Node Exporter, kube-state-metrics, MySQL Exporter, Redis Exporter, PromQL, Dashboard, Alert Rule
- 日志与排查 / Logging and Troubleshooting: Loki, Promtail, Container Logs, Application Logs, Nginx Logs, system logs, Event, Metrics, Tracing Basics
- 自动化运维 / Operations Automation: Ansible, Playbook, Inventory, Shell Script, Batch Operations, Configuration Distribution, Service Check, Environment Initialization
- 脚本与编程 / Scripting and Programming: Shell, Bash, Python, Go, Java, FastAPI, REST API, JSON, YAML
- 云平台 / Cloud Platforms: Alibaba Cloud, Tencent Cloud, Huawei Cloud, AWS, ECS, VPC, SLB, RDS, OSS, CDN, DNS, Cloud Monitor, Container Service
- 基础设施与存储 / Infrastructure and Storage: Terraform, IaC, Ceph, Object Storage, Block Storage, File Storage, NFS
- 消息队列与中间件 / Message Queue and Middleware: Kafka, Redis, Nginx, Tomcat
- 开发与协作工具 / Development and Collaboration: VS Code, Markdown, GitHub Issues, Pull Request, README, Technical Documentation

## GitHub 数据 / GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=290298661-pixel&show_icons=true&hide_border=true&theme=default" alt="GitHub Stats" />
</p>

<p>
  <img src="https://streak-stats.demolab.com?user=290298661-pixel&hide_border=true&theme=default" alt="GitHub Streak" />
</p>
