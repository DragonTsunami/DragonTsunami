<img src="https://capsule-render.vercel.app/api?type=waving&height=200&section=header&text=%E9%9D%92%E8%A1%AB%20%C2%B7%20DevOps%20%E8%BF%90%E7%BB%B4&desc=%E6%8A%8A%E7%9C%9F%E5%AE%9E%E7%B3%BB%E7%BB%9F%E5%81%9A%E5%88%B0%20%E5%8F%AF%E9%83%A8%E7%BD%B2%20%C2%B7%20%E5%8F%AF%E8%A7%82%E6%B5%8B%20%C2%B7%20%E5%8F%AF%E6%81%A2%E5%A4%8D&fontSize=42&descSize=16&fontColor=ffffff&descAlignY=72&color=0:0ea5e9,100:6366f1" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=38BDF8&center=true&vCenter=true&width=640&height=50&lines=%E5%B7%A5%E5%8D%95%E5%88%B6%E6%8C%87%E6%8C%A5%20AI%20Agent%EF%BC%8C%E4%BA%BA%E5%B7%A5%E9%80%90%E9%A1%B9%E9%AA%8C%E6%94%B6;%E4%B8%80%E4%B8%AA%E7%9C%9F%E5%AE%9E%E7%B3%BB%E7%BB%9F%EF%BC%9A%E5%8F%AF%E9%83%A8%E7%BD%B2%20%C2%B7%20%E5%8F%AF%E8%A7%82%E6%B5%8B%20%C2%B7%20%E5%8F%AF%E6%81%A2%E5%A4%8D;%E6%AF%8F%E4%B8%AA%E6%95%B0%E5%AD%97%E9%83%BD%E6%9D%A5%E8%87%AA%E7%9C%9F%E5%AE%9E%E5%AE%9E%E6%93%8D%20%C2%B7%20%E5%8F%AF%E5%A4%8D%E7%8E%B0%20%C2%B7%20%E5%8F%AF%E8%BF%BD%E9%97%AE;%E6%B1%82%E8%81%8C%E4%B8%AD%EF%BC%9A%E5%88%9D%E7%BA%A7%20DevOps%20%2F%20%E8%BF%90%E7%BB%B4%E5%B7%A5%E7%A8%8B%E5%B8%88%20%C2%B7%20%E6%B7%B1%E5%9C%B3" alt="Typing SVG" />

## 🎯 关于我

转行 DevOps，以**工单制指挥 AI Agent + 人工逐项验收**的方式，把一套真实业务系统（12 服务医疗预约平台）从零做到生产级。信奉一条铁律：**AI 提假设，我出裁决**——每个结论必须经 `docker logs` / `nginx -t` / `promtool` / `--check` 干跑验证后才采纳。

## 📌 项目

### [clinic-ops](https://github.com/DragonTsunami/clinic-ops) — 医疗·诊所预约平台（生产级运维）

FastAPI + Vue + MySQL/Redis + Nginx，全容器化 12 服务

- ✅ **E2E 验收 14/14** 全绿（含 AI 组件 selftest 6/6）
- ✅ **监控栈**：Prometheus 7 采集源全 up · 告警链路 Telegram 实收（probe_success=1）
- ✅ **AI 运维四件套**：告警 AI 分诊 / 每日巡检 / CI AI 评审 / runbook 起草——LLM 只接收运维指标，业务数据不出境
- ✅ **删库恢复演练 RTO 125 秒**：真实 DROP → 备份件恢复 → 行数比对 + 业务闭环全过，金丝雀数据消失实证 RPO
- ✅ **CI/CD**：GitHub Actions（compose 校验 · 镜像构建 · 测试门禁 + AI 评审）

### [devops-lab-junior](https://github.com/DragonTsunami/devops-lab-junior) — DevOps 学习实验室

9 服务 Compose 学习栈 + Ansible 双容器靶场，每个坑都有根因分析与验证命令

- ✅ **Ansible 工单制真跑**：ok=24 / changed=19 / failed=0 · 幂等二跑 changed=0
- ✅ **verify.sh 验收 10/10**（含 root 被禁反向验证——加固不靠自觉靠验证）
- ✅ GitHub Actions CI 全绿 · 踩坑文档全程留痕

## 🔧 技术栈

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![AI / MCP](https://img.shields.io/badge/AI_·_MCP-8B5CF6?style=for-the-badge&logo=openai&logoColor=white)

## 📊 GitHub 统计

<img height="160" src="https://streak-stats.demolab.com?user=DragonTsunami&theme=tokyonight&hide_border=true&locale=zh_CN" alt="GitHub streak" />

## 🐍 活跃曲线

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DragonTsunami/DragonTsunami/output/github-snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/DragonTsunami/DragonTsunami/output/github-snake.svg" />
</picture>

## 📫 联系

[![Gmail](https://img.shields.io/badge/Gmail-xiaolong0485%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xiaolong0485@gmail.com)
![深圳](https://img.shields.io/badge/现居-深圳龙华-0ea5e9?style=for-the-badge&logo=location&logoColor=white)
![到岗](https://img.shields.io/badge/到岗-随到随入-22c55e?style=for-the-badge)

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&text=%E6%84%9F%E8%B0%A2%E9%98%85%E8%AF%BB%20%C2%B7%20%E6%AC%A2%E8%BF%8E%E4%BA%A4%E6%B5%81&fontSize=18&fontColor=ffffff&color=0:6366f1,100:0ea5e9" width="100%" />
