<div align="center">

```
runcat@dsh:~$ whoami
 /\ /\
( -.- )
 > ^ <
> coder & pytorcher
runcat@dsh:~$ _
```

`./dev --whoami`

**兴趣驱动的开源爱好者** · DeepSeek Harness 插件开发 · PyTorch · Backend · Data

*中文：一个把代码当爱好的普通人，正在 DeepSeek Harness 生态里写插件。*
*EN: An open-source hobbyist building plugins for the DeepSeek Harness ecosystem.*

</div>

---

## 🔌 whoami

```text
$ whoami
> 开源爱好者 / Open-source hobbyist
> DeepSeek Harness (dsh) 插件作者 / DSH plugin author
> 后端 · 数据 · AI  (Backend · Data · AI)
> 状态: 自研 10 个 DSH 插件（9 个已发布 npm）+ 1 个 PyTorch 项目 / 10 DSH plugins (9 on npm) + 1 PyTorch project
```

## 🧰 stack.txt

```text
$ cat ~/stack.txt
├── 主力 Shipped   : JavaScript · TypeScript · Node.js · React
├── 平台 Platform  : DeepSeek Harness (dsh) · cordis · npm
├── 界面 UI        : Web GUI 插件 · 会话视图标签 · 设置页 · 主题与样式 · 中英双语 i18n
├── AI / ML        : PyTorch · MobileNetV3 · MTCNN · MediaPipe · Gradio  (纯 CPU 推理)
└── 背景 Background: Python · Java · SQL  (后端 / 数据方向)
```

## 📂 ls -la ~/projects

```text
$ ls -la ~/projects      # 自研项目，全部开源（MIT）
```

### 🖥️ 会话视图标签（会话页头新增一页）

| 插件 | 说明 |
|---|---|
| **`dsh-unitverse`** | 单位换算：长度 / 面积 / 体积 / 时间 / 角度 / 速度 / 温度 / 压力 / 热量 / 功率 十大类 **80+ 单位**，`convert` 工具 + Web 视图，中英单位名与温差 Δ 双模式 |
| **`dsh-panda-calendar`** | 熊猫日历：公历 / 农历 / 干支 / 生肖 / 节气 / 节日、法定节假日与调休、多城市天气、时间戳转换、历史上的今天 |
| **`dsh-chinese-poetry`** | 中国古典诗词：37 万首搜索筛选、飞花令、每日一诗、收藏、AI 讲解 |

> 这三个都是**免 token** 的数据型标签页：不建后端、不申请 Key，AI 解释直接走你自己的 dsh 会话。

### 🎨 界面与外观

| 插件 | 说明 |
|---|---|
| **`dsh-theme-manager`** | 两级主题管理：先选文化 / 场景，再选风格，58 款内置样式（中国·水墨、日本·浮世绘、开发者·Catppuccin、国旗…），点「使用」实时生效 |
| **`dsh-view-manager`** | 视图标签管理：启用 / 隐藏、排序、重命名（对话 / 轨迹 / 任意视图插件） |

### ⚙️ 设置页（与「插件」同级）

| 插件 | 说明 |
|---|---|
| **`dsh-plugin-runcat-inventory`** | 逃咪-插件总览：表格视图、状态过滤、启用停用热生效、卸载、更新提醒、配置查看与复制 |
| **`dsh-mcp-mini-manager`** | MCP 极简管理：列出当前 DSH 实际装载的每个 MCP 服务器、简介与运行状态，并可逐个移除（写入可恢复的停用补丁） |
| **`dsh-skill-mini-manager`** | skill 极简管理：列出全部已装 skill 的简介、来源与体积，可逐个移除（可恢复回收站） |

### 🧰 专项工具

| 插件 | 说明 |
|---|---|
| **`dsh-windows-c-cleanup`** | Windows C 盘清理：把清理拆成一条**可审计流水线**——扫描 → 五级分级（可安全删除 / 谨慎删除 / 建议迁移 / 保护名单 / 长期防护）→ 可视化报告 → 用户确认 → 分层执行、暂存区与迁移（需管理员权限的项走 UAC 提权）|
| **`dsh-netscope`** | 网络全景观测仪：只读、零依赖、零权限的本机网络观测仪，为每条结论标注**可信度与来源**并与历史基线比对。`⏸ 已暂停（2026-09）`，代码完整可用、未发布 npm |

### 🤖 PyTorch / AI

| 项目 | 说明 |
|---|---|
| **`pytorch_face_scoring`** | 人脸颜值趣味评分：MobileNetV3 + MTCNN 回归总分（SCUT-FBP5500 训练、5500 张参考分布做分位校准）、MediaPipe FaceMesh 478 关键点的几何美学引擎出五维分项、瞳色/眼神光/肤色冷暖/微笑弧度等趣味检测、气质标签与幽默文案，输出 HTML 报告 + 五维雷达图（Gradio 展示）。纯 CPU 推理，单张约 0.25 秒 |

> 非 dsh 插件：独立的 Python / PyTorch 项目，本地推理、无需 GPU。

### 📦 一键安装

```sh
# 全部已发布到 npm 的插件（安装后重启 DSH Web）
dsh plugin --profile web add dsh-unitverse
dsh plugin --profile web add dsh-panda-calendar
dsh plugin --profile web add dsh-chinese-poetry
dsh plugin --profile web add dsh-theme-manager
dsh plugin --profile web add dsh-view-manager
dsh plugin --profile web add dsh-plugin-runcat-inventory
dsh plugin --profile web add dsh-mcp-mini-manager
dsh plugin --profile web add dsh-skill-mini-manager
dsh plugin --profile web add dsh-windows-c-cleanup

# dsh-netscope 暂未发布 npm，从源码安装：git clone 后 dsh plugin --profile web add ./dsh-netscope
```

## 📚 awesome 清单（fork 维护）

```text
$ ls -la ~/awesome
```

| 清单 | 内容 | 上游 |
|---|---|---|
| **`awesome-deepseek-harness`** | DSH 生态精选索引：插件、工具与基础设施，按 20+ 分类整理 | fork 自 `0xsline/awesome-deepseek-harness` |
| **`awesome-dsh-plugin`** | 社区插件清单：官方站 [awesome-dsh-plugin.com](https://awesome-dsh-plugin.com)、插件计数徽章、评论讨论区，并推荐内置市场插件 `dsh-market` | fork 自 `awesome-dsh-plugin/awesome-dsh-plugin` |
| **`awesome-deepseek-harness-plugins`** | 社区插件目录：收录 1.3 万+ 插件，配自动收集与格式校验流水线、公开查询 API | fork 自 `imsai-sh/awesome-deepseek-harness-plugins` |

> 这三个是上游**社区清单仓库的 fork**，用于跟踪与取用生态目录；原创代码在上面「自研插件」里。

> 全部仓库见 [github.com/runcat-tommy?tab=repositories](https://github.com/runcat-tommy?tab=repositories)

## 📡 contact

```text
$ cat ~/contact.md
Email   : xujingyu123456@gmail.com yeyu1899@163.com 99148430@qq.com
GitHub  : github.com/runcat-tommy
Blog    : www.fastformat.cn
```

---

<div align="center">

*Thanks for visiting! 感谢来访 🖖*

![visitors](https://komarev.com/ghpvc/?username=runcat-tommy&color=green)

</div>

<!-- ================ 可选增强（需要时取消注释，均无需维护） ================ -->
<!--
## 📈 stats（可选：贡献统计卡，自动更新，无需维护）

```text
$ github-stats --theme terminal
```

![GitHub stats](https://github-readme-stats.vercel.app/api?username=runcat-tommy&show_icons=true&theme=dark&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=runcat-tommy&layout=compact&theme=dark&hide_border=true)

## ⌨️ typing（可选：打字机效果，无需维护）

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=500&color=00FF66&lines=Hello!+I+am+a+dev;Backend+%26+Data+lover;Welcome+to+my+profile)](https://git.io/typing-svg)
-->
