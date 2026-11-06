# Yuan Yiqi · 袁艺琪

<p>
  <a href="https://annakareninaof17.pages.dev/"><img src="https://img.shields.io/badge/Demo-Anna_Karenina-8B1E3F?style=flat-square" alt="Anna Karenina demo" /></a>
  <a href="https://2711editor.pages.dev"><img src="https://img.shields.io/badge/Demo-2711_Editor-2F5D50?style=flat-square" alt="2711 Editor demo" /></a>
  <a href="https://leping-stages-map.pages.dev/"><img src="https://img.shields.io/badge/Demo-Leping_Map-C4A35A?style=flat-square" alt="Leping map demo" /></a>
  <img src="https://img.shields.io/badge/GPA-3.74%2F4.0-444444?style=flat-square" alt="GPA 3.74 / 4.0" />
</p>

**Tianjin University** · B.A. Chinese Language & Literature · Class of 2027  
**Applied AI · NLP · Evaluation-First Systems**

I build end-to-end language systems: **corpus → LLM evaluation → statistical inference → shipped demos**.  
Live products, auditable metrics, and reproducible pipelines — not slideware.

📧 **3251224718@qq.com** · [GitHub](https://github.com/yuanyiqi422-byte)

---

## Featured

### 1. Reduplicated Adjectives · Sentiment Shift
**Academic Year Thesis** · NLP evaluation + inferential statistics

Do AABB / ABB adjective forms shift polarity vs base forms in informal Chinese? Built a Weibo corpus of **14,987** sentence instances (**22** pairs), scored polarity with DeepSeek-V3, validated against a three-annotator majority-vote gold set (**Exact Match 97.11%** on **1,486** stratified samples), and tested base vs reduplicated scores with Welch's *t*-test.

| Signal | Result |
|--------|--------|
| Overall (n = 14,987) | Welch's *t* = 2.49 · **p = 0.013** · Δ ≈ −0.04 · \|*d*\| ≈ 0.04 |
| Pair-level Δ | Range [−0.66, +0.74] — effect is heterogeneous across pairs |

**Repo:** [reduplicated-adjectives-sentiment](https://github.com/yuanyiqi422-byte/reduplicated-adjectives-sentiment)

<p align="center">
  <img src="./assets/fig09_delta_heterogeneity.png" alt="Pair-level Δ heterogeneity across 22 reduplicated pairs" width="48%" />
  <img src="./assets/fig10_aabb_abb_group_comparison.png" alt="AABB vs ABB group comparison of pair-level mean Δ" width="48%" />
</p>
<p align="center"><em>Fig.9 pair-level Δ heterogeneity · Fig.10 AABB vs ABB group comparison</em></p>

### 2. Interactive AI Narrative Systems
**Multi-agent discourse + latency-bounded generation**

| System | What it delivers | Links |
|--------|------------------|-------|
| **Anna Karenina · AI Literary Guide** | **7** persona agents · **10**-turn sliding context · **40–90**-char replies · live architecture / prompt panel for context control | [Demo](https://annakareninaof17.pages.dev/) |
| **2711 Editor · Novel → Branching VN** | FastAPI pipeline with chapter-aware sampling / truncation · story bible → outline → playable branches · **358** scene-matched assets · end-to-end under **3** minutes at fixed resources | [Demo](https://2711editor.pages.dev) · [Repo](https://github.com/yuanyiqi422-byte/2711-editor) |

### 3. Yuyun Jinhe · Grand Canal Linguistic Landscape
**National Undergraduate Innovation and Entrepreneurship Training Program** · core technical contributor (data & NLP pipeline)

Multimodal canal language-landscape corpus and knowledge graph: **1,182** structured entries (+128 field samples), NLP analysis, and GIS maps.  
**WeChat mini program:** 语韵津河

### 4. Leping Ancient Stages · Digital Map
Curated **400+** candidate sites / **103** sources → **28** geocoded stages on AMap / Leaflet, with JSON / CSV export from cleaned `stages.json`.  
**Demo:** [leping-stages-map.pages.dev](https://leping-stages-map.pages.dev/)

### Also
| Project | Note |
|---------|------|
| [Foreign Literature Review](https://waiguo-wenxue-review.pages.dev) | Interactive quiz / review site for exam prep |

---

## Stack

```text
Python · FastAPI · Pandas / NumPy / SciPy
Prompt engineering · RAG / multi-agent dialogue · LLM evaluation vs human gold
Welch's t · effect-size reporting · corpus crawl / clean / annotate
JavaScript · Cloudflare Pages · Leaflet / AMap · Git
```

---

<details>
<summary>中文简介</summary>

天津大学汉语言文学在读（2027 届）。方向：Applied AI / NLP / 评测驱动系统。主线：语料构建 → 大模型评测 → 统计推断 → 可点击 Demo。代表作：叠词情感评测（Exact Match 97.11%）、Anna / 2711 互动叙事、语韵津河大创、乐平古戏台数字地图。联系：3251224718@qq.com

</details>

---

**Start here:** [Thesis repo](https://github.com/yuanyiqi422-byte/reduplicated-adjectives-sentiment) for metrics · [Anna](https://annakareninaof17.pages.dev/) / [2711](https://2711editor.pages.dev) for live demos
