# 📈 The A-Share Quant Chronicle (A 股量化与板块轮动研究 Dashboard)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-success?style=flat-square&logo=github)](https://j1nkai.github.io/a-share-quant-dashboard/)
[![Update Cycle](https://img.shields.io/badge/Update%20Cycle-Daily%2017%3A00%20(GMT%2B8)-blue?style=flat-square)](https://j1nkai.github.io/a-share-quant-dashboard/)
[![Design Style](https://img.shields.io/badge/Design%20Style-Japanese%20Cyber--Core%20%2F%20Editorial%20Print-black?style=flat-square)](https://j1nkai.github.io/a-share-quant-dashboard/)

> **Project Mission**: 为 Master JK 提供的为期 15 天 A 股存量博弈、板块轮动规律及量化交易脚印（Algorithmic Footprints）自动化监测与社论级数据分析看板。

---

## 🏛️ 项目特色与设计美学 (Design & Architecture)

- **双端差异化布局 (Adaptive Responsive Layout)**：
  - **PC 宽屏端 (≥1024px)**：经典多栏报纸社论版面（Two-Column Editorial Grid），左侧为市场结构与算法微观归因，右侧为高频量化活跃板块表，充分发挥大屏阅读优势。
  - **移动手机端 (<1024px)**：纯净单列垂直流动布局（Single-Column Flow），包含 2×2 自适应数据网格与横向丝滑滑动表格。
- **纯白/复古纸张印迹 (Editorial Print Style)**：
  - 选用 `Newsreader` 与 `Noto Serif SC` 衬线字体排版，结合双粗线 Header 与 Drop Cap 首字母下沉，提供舒适不刺眼的纸张质感。
- **无依赖全自动化流水线**：
  - 每日 17:00 通过 `cron` 定时唤醒 `akshare` 采集引擎，对当日行业板块、换手率、主力资金与量化做 T 迹象进行多维归因，生成 HTML 并自动推送到 GitHub Pages 部署。

---

## 📊 数据分析维度 (Research Scope)

1. **板块轮动矢量 (Sector Rotations)**：追踪每日领涨/领跌行业及其换手率与领涨龙头。
2. **量化交易痕迹 (Quant Footprints)**：识别高换手率但中枢窄幅震荡的“网格算法做 T”与尾盘权重再平衡信号。
3. **流动性与资金归因 (Liquidity Balance)**：分析场内存量腾挪与主线资金偏好（如半导体/AI vs 红利防御）。

---

## 🌐 实时看板入口

👉 **[点击直接访问在线 Dashboard](https://j1nkai.github.io/a-share-quant-dashboard/)**

---
*Created with 💙 by Rem & Master JK*
