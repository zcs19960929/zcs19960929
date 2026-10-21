<div align="center">

# Hi, I'm zcs19960929 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=0E75B6&center=true&vCenter=true&width=760&lines=Java+Backend+Developer;AI+Explorer;Open+Source+Enthusiast" alt="Java Backend Developer · AI Explorer · Open Source Enthusiast" />

Building reliable backend systems and turning ideas into practical experiments.

<img src="https://komarev.com/ghpvc/?username=zcs19960929&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />

</div>

<!-- WEEKLY-DEVELOPMENT:START -->
## 本周开发记录 · 2026.10.21

> 写代码，让想法落地。记录正在构建的工具，以及每周向前的一小步。

**统计区间：2026.10.14 15:17 — 2026.10.21 15:17（北京时间，最近 7 天）**

| 个人提交 | 活跃仓库 | 非合并提交 | 有提交的日期 |
| :---: | :---: | :---: | :---: |
| **4**（含 1 条合并） | **2** | **3** | **1** |

### 01 · 让 NAS 代理的会话更可靠

[**uglink-worker-nas**](https://github.com/zcs19960929/uglink-worker-nas) · TypeScript / Cloudflare Workers / Durable Objects

- 将代理会话交给 SQLite Durable Object 协调，同一 NAS 凭据的并发请求复用已建立的会话。
- 瞬时认证网络错误、超时及认证接口 HTTP 429/5xx 采用 30 秒退避；账号拒绝继续保留相应保护时间。
- 无请求体的 GET、HEAD、OPTIONS 可在上游 HTTP 502/503/504 时重试一次；写入请求与 WebSocket 升级不会自动重放。

本周 2 条提交（含 1 条合并）。[修复提交 `ec40222`](https://github.com/zcs19960929/uglink-worker-nas/commit/ec4022237d8ff193e25eb44f4d77f00a0f6833b4) 涉及 26 个文件，新增 621 行、删除 89 行。

### 02 · 把媒体整理流程做成插件

[**MoviePilot-Plugins**](https://github.com/zcs19960929/MoviePilot-Plugins) · Python / MoviePilot V2 & V3

- 新增 MetaTube 元数据刮削插件，兼容 MoviePilot V2/V3，生成 NFO、海报和背景图。
- 支持可视化目录选择、本地 STRM 目录映射、增量跳过、写入限速与任务互斥。
- 提供可配置定时任务、数据源自检和手动停止；后续提交将首发版本统一整理为 **v1.0.0**。

本周 2 条提交。[功能提交 `a50f977`](https://github.com/zcs19960929/MoviePilot-Plugins/commit/a50f977cf7603117e43d57d7484f19bdd3206591) 的原始说明标记为 v1.3.0，随后通过 [`a019bda`](https://github.com/zcs19960929/MoviePilot-Plugins/commit/a019bda1bf2a5abcd3d3d25fa014969db18f5ff1) 整理为首发版本 v1.0.0。

<details>
<summary>查看本期全部提交与统计范围</summary>

| 时间（北京时间） | 仓库 | 改动 | 提交 |
| --- | --- | --- | --- |
| 10.20 21:54 | uglink-worker-nas | 协调代理会话，并从瞬时故障中恢复 | [`ec40222`](https://github.com/zcs19960929/uglink-worker-nas/commit/ec4022237d8ff193e25eb44f4d77f00a0f6833b4) |
| 10.20 13:26 | MoviePilot-Plugins | 整理首个发布版本 v1.0.0，移除本地调试版本历史 | [`a019bda`](https://github.com/zcs19960929/MoviePilot-Plugins/commit/a019bda1bf2a5abcd3d3d25fa014969db18f5ff1) |
| 10.20 13:09 | MoviePilot-Plugins | 新增 MetaTube 刮削插件，兼容 V2/V3 | [`a50f977`](https://github.com/zcs19960929/MoviePilot-Plugins/commit/a50f977cf7603117e43d57d7484f19bdd3206591) |
| 10.20 11:25 | uglink-worker-nas | 合并上游 Leonis-Q-F:main 分支 | [`81c2f5c`](https://github.com/zcs19960929/uglink-worker-nas/commit/81c2f5c4ee2d8c61a493e1a74cd4d229b2619f5e) |

- 检索当前 GitHub 连接列出的 47 个仓库，其中 44 个可读取，3 个受 GitHub 访问限制而未纳入。
- 只统计各仓库默认分支上、关联作者为 `zcs19960929` 且作者时间在区间内的提交；不覆盖其他分支、未授权仓库和本地未推送记录，不代表全站贡献总数。
- 本期展示的提交均来自公开仓库。摘要依据提交说明和代码差异整理；本次未执行这些项目的测试，也不据此宣称部署或运行效果。
- 本区块记录本期快照；页面其他项目为长期项目展示，不计入本周活跃仓库。

</details>
<!-- WEEKLY-DEVELOPMENT:END -->

## About Me

```java
import java.util.List;

public final class Zcs19960929 {
    private final String role = "Java Backend Developer";
    private final List<String> interests = List.of(
        "Backend Architecture",
        "AI-assisted Engineering",
        "Open Source"
    );

    public String currentlyExploring() {
        return "Reliable services, developer tools, and practical AI applications";
    }
}
```

- ☕ I build maintainable backend services in the Java ecosystem.
- 🤖 I explore how AI can improve engineering workflows and real-world products.
- 🧩 I enjoy learning in public through open-source projects and experiments.

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/MyBatis-DC382D?style=for-the-badge&logoColor=white" alt="MyBatis" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" alt="Maven" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

## Projects & Experiments

| Project | What it explores |
| --- | --- |
| [`dynamic-datasource`](https://github.com/zcs19960929/dynamic-datasource) | Dynamic datasource routing, transactions, SQL observability, and sharding in Spring Boot. |
| [`daily_stock_analysis`](https://github.com/zcs19960929/daily_stock_analysis) | AI-assisted multi-market stock analysis and automated reporting workflows. |
| [`danmu_api`](https://github.com/zcs19960929/danmu_api) | A deployable danmaku API experiment spanning serverless and container platforms. |
| [`raycast_api_proxy`](https://github.com/zcs19960929/raycast_api_proxy) | API proxy experiments for Raycast-related workflows. |

## GitHub Analytics

<div align="center">
  <a href="https://github.com/zcs19960929">
    <img height="180" src="https://ghstats.dev/api/card?username=zcs19960929&theme=tokyonight&hide_border=true&show_icons=true" alt="GitHub Stats" />
  </a>
  <a href="https://github.com/zcs19960929">
    <img height="180" src="https://streak-stats.demolab.com?user=zcs19960929&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
  </a>
</div>

<div align="center">
  <a href="https://github.com/zcs19960929">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=zcs19960929&theme=tokyonight" alt="GitHub Activity Overview" />
  </a>
</div>

---

<div align="center">
  Thanks for stopping by — feel free to explore the repositories and connect through open source.
</div>
