# 青衫 · DevOps / 运维工程师

> 转行 DevOps，以「工单制指挥 AI Agent + 人工逐项验收」的方式，把一个真实业务系统从零做到**可部署、可观测、可恢复**。每个数字都来自真实实操，可复现、可追问。

**🎯 求职中：初级 DevOps / 运维工程师 ｜ 深圳（优先）· 广州**

## 🔧 技术栈

`Linux` `Docker / Compose` `GitHub Actions` `Ansible` `Prometheus + Grafana + Loki` `Nginx` `MySQL / Redis` `Python` `AI 工程化 (MCP)`

## 📌 项目

### [clinic-ops](https://github.com/DragonTsunami/clinic-ops) — 医疗·诊所预约平台（生产级运维）

FastAPI + Vue + MySQL/Redis + Nginx，全容器化 12 服务。目标不是「能跑」，而是生产级三件事：可部署、可观测、可恢复。

- ✅ **E2E 验收 14/14 全绿**（含 AI 组件 selftest 6/6）
- ✅ **监控**：Prometheus 7 采集源全 up；告警链路 Telegram 实收（probe_success=1）
- ✅ **AI 运维四件套**：告警 AI 分诊 / 每日巡检 / CI AI 评审 / runbook AI 起草——LLM 只接收运维指标，业务数据不出境
- ✅ **删库恢复演练：RTO 125 秒**——真实 DROP 后经备份件恢复，数据完整性比对 + 登录/预约/写入业务闭环全过；备份后写入的金丝雀数据消失，实证 RPO 边界
- ✅ **CI/CD**：GitHub Actions（compose 校验、镜像构建、测试门禁 + AI 评审）

### [devops-lab-junior](https://github.com/DragonTsunami/devops-lab-junior) — DevOps 学习实验室

9 服务 Docker Compose 学习栈 + Ansible 双容器靶场，转行练手的每一坑都沉淀了根因分析。

- ✅ **Ansible 工单制真跑**：ok=24 / changed=19 / failed=0；幂等二跑 changed=0
- ✅ **verify.sh 验收 10/10**（含 root 被禁反向验证——加固不靠自觉靠验证）
- ✅ GitHub Actions CI 全绿；requirepass 联动 healthcheck、Windows 挂载 0777 等踩坑全程留痕

## 🧭 工作方式

- **工单制**：每个任务有目标、技术点、可验证的验收命令——以验收关单，不以字数关单
- **AI 提假设，我出裁决**：排错走固定路径（进程→端口→日志→资源），喂证据不喂情绪；AI 结论必须经 `docker logs` / `nginx -t` / `promtool` / `--check` 干跑验证后采纳
- **一切留痕**：AI 协作全程文档化（docs/ai-collab）、故障演练手册 D1-D6、每个坑都有根因分析与验证命令

## 📫 联系

- 邮箱：xiaolong0485@gmail.com
- 现居：深圳龙华 · 期望：初级 DevOps / 运维岗 · 到岗：随到随入
