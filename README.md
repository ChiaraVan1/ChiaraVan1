# 👋 Hi, I'm Wenjia Fan · 樊文佳

Data Scientist with 5 years of experience, focused on LLM applications, AI product analytics, and applied ML. My projects cluster into three tracks — each one solving a real problem I ran into at work or in life.

数据科学家，5 年一线实战经验，专注大模型应用、AI 产品效果分析与应用机器学习。所有项目分布在三条主线上，每一个都源于工作或生活中真实遇到的问题。

---

## 🗺️ Project Map · 项目全图

```
金融量化线  equity-risk-premium-monitor ──► ETF_data_project ──► stock_Valuation_bot
职场 AI 线  smart-insight-chrome-ai ──────────────────────────► remote_job_monitor
ML 工具线   classifier ──────────────────► city_forecast ───────► diet-app
```

---

## 📈 Track 1 · 金融量化 Financial Quant

> From macro risk signals → systematic screening → valuation with LLM push  
> 从宏观风险信号 → 系统化筛选 → LLM 估值推送

### [equity-risk-premium-monitor](https://github.com/ChiaraVanl/equity-risk-premium-monitor)
Daily tracker for equity risk premium (ERP) across **16 global indices**, with a win-rate / odds position-sizing framework.  
覆盖 **16 个全球指数**的股权风险溢价每日监控，内置胜率/赔率仓位框架。  
`Python` `pandas` `scheduled jobs`

### [ETF_data_project](https://github.com/ChiaraVanl/ETF_data_project)
Automated ETF screening and monitoring pipeline with scheduled inference — runs fully unattended.  
全自动 ETF 筛选与监控流水线，支持定时推理，无需人工干预。  
`Python` `ETF screening` `automation`

### [stock_Valuation_bot](https://github.com/ChiaraVanl/stock_Valuation_bot)
Dual-track stock valuation system: quantitative model + LLM narrative analysis, results pushed via **WeChat**.  
双轨估值系统：量化模型 + LLM 叙事分析，结果通过**微信**推送。  
`LLM` `valuation` `WeChat push`

---

## 💼 Track 2 · 职场 AI Workplace AI

> Chrome-side career intelligence → automated remote job discovery  
> 浏览器端职场智能 → 自动化远程岗位发现

### [smart-insight-chrome-ai](https://github.com/ChiaraVanl/smart-insight-chrome-ai)
Chrome extension powered by **Chrome built-in AI** (Gemini Nano) — analyzes LinkedIn profiles and job pages in-browser, no API calls needed.  
基于 **Chrome 本地 AI**（Gemini Nano）的浏览器扩展，在本地直接分析 LinkedIn 主页与职位页面，无需调用外部 API。  
`Chrome AI` `Gemini Nano` `LinkedIn` `career assistant`

### [remote_job_monitor](https://github.com/ChiaraVanl/remote_job_monitor)
Crawls career pages of **worldwide/global** companies daily, matches Python / Data Analyst openings, and publishes a searchable results page to **GitHub Pages** automatically.  
每日爬取 **全球远程友好**公司的招聘页面，自动匹配 Python / Data Analyst 岗位，结果发布至 **GitHub Pages** 可搜索页面。  
`BeautifulSoup` `GitHub Actions` `GitHub Pages` `scheduled scraping`

---

## 🧠 Track 3 · ML 工具 ML Tooling

> Text classification for ops → time-series forecasting → everyday utility  
> 运营文本分类 → 时序预测 → 日常工具

### [classifier](https://github.com/ChiaraVanl/classifier)
Hybrid NLP pipeline for classifying messy **refund-reason** text: rule-based triage splits logs from free-text reasons, BERT fine-tunes on the latter, BERTopic clusters residual semantics.  
针对杂乱**退费原因**文本的混合 NLP 流水线：规则分流将操作日志与自由文本分离，BERT 对后者进行微调分类，BERTopic 处理剩余语义聚类。  
`BERT` `BERTopic` `SentenceTransformers` `sklearn`

### [city_forecast](https://github.com/ChiaraVanl/city_forecast)
Multi-city **enrollment revenue forecasting** app: KMeans city clustering → LightGBM with time-series CV → Streamlit dashboard with Plotly interactive charts.  
多城市**报名收入增幅预测**应用：KMeans 城市聚类 → LightGBM 时序交叉验证 → Streamlit + Plotly 可交互仪表盘。  
`LightGBM` `KMeans` `TimeSeriesSplit` `Streamlit` `Plotly`

### [diet-app](https://github.com/ChiaraVanl/diet-app)
Streamlit app that randomly suggests today's meals (breakfast / lunch / dinner), calculates calorie intake, and compares against your personal BMR + activity expenditure.  
Streamlit 小工具，随机推荐今日三餐，计算总热量摄入，并与个人基础代谢 + 活动消耗对比，显示热量盈余/缺口。  
`Streamlit` `calorie tracking` `fun side project`

---

## 🛠️ Tech Stack · 技术栈

| Area 方向 | Tools 工具 |
|-----------|-----------|
| Data & ML | pandas · LightGBM · scikit-learn · BERT · BERTopic |
| Finance 金融 | ERP modelling · ETF screening · DCF / relative valuation |
| Automation 自动化 | GitHub Actions · scheduled scraping · WeChat push |
| Frontend 前端 | Streamlit · Chrome Extensions · GitHub Pages |
| Languages 语言 | Python · JavaScript |

---

*All projects are built around real workflows — financial monitoring I actually use, NLP pipelines from production ops data, and tools that save me time every day.*

*所有项目均来自真实工作流——我自己在用的金融监控、生产环境的 NLP 流水线，以及真正帮我节省时间的小工具。*
