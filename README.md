# Hi, I'm **Yuan Yiqi** · 袁艺琪

<p>
  <a href="https://annakareninaof17.pages.dev/"><img src="https://img.shields.io/badge/Demo-Anna_Karenina-8B1E3F?style=flat-square" alt="Anna" /></a>
  <a href="https://2711editor.pages.dev"><img src="https://img.shields.io/badge/Demo-2711_Editor-2F5D50?style=flat-square" alt="2711" /></a>
  <a href="https://leping-stages-map.pages.dev/"><img src="https://img.shields.io/badge/Demo-Leping_Map-C4A35A?style=flat-square" alt="Leping" /></a>
  <img src="https://img.shields.io/badge/IELTS-7.0-1F4E79?style=flat-square" alt="IELTS" />
  <img src="https://img.shields.io/badge/GPA-3.74%2F4.0-444?style=flat-square" alt="GPA" />
</p>

**Tianjin University** · B.A. in Chinese Language & Literature (Class of 2027)  
**Incoming Graduate Applicant in Data Science, Business Statistics & Social Computing**

I turn literature, fieldwork, and language corpora into **small, inspectable AI + data tools** — with real demos, not slideware.  
DSBS-facing pipeline: **corpus construction → statistical testing → LLM evaluation → productised demos**.

📧 **yuanyiqi0422@163.com** · 🌐 [github.com/yuanyiqi422-byte](https://github.com/yuanyiqi422-byte)

---

## Featured projects

### 1. Reduplicated Adjectives · Sentiment Shift (Thesis)
**Problem → method → result:** Do AABB/ABB adjective forms shift sentiment vs base forms in informal Chinese? Built a Weibo corpus (**14,987** valid sentence instances across **22** pairs), scored polarity with DeepSeek-V3 (1–5), benchmarked against a three-annotator majority-vote gold standard (**Exact Match 97.11%** on **1,486** stratified samples), then tested base vs reduplicated scores with Welch's *t*-test.

- **Overall effect (base vs reduplicated, n = 14,987):** Welch's *t* = 2.49, **p = 0.013**, aggregate Δ ≈ −0.04, |*d*| ≈ 0.04; pair-level Δ ∈ [−0.66, +0.74].
- **Group-level AABB vs ABB (Fig.10; n = 11 pairs each):** AABB mean Δ ≈ +0.10 (**p ≈ 0.193**); ABB mean Δ ≈ −0.04 (p ≈ 0.744) — **not** the same contrast as the overall Welch test above.
- Repo: [reduplicated-adjectives-sentiment](https://github.com/yuanyiqi422-byte/reduplicated-adjectives-sentiment)

<p align="center">
  <img src="./assets/fig09_delta_heterogeneity.png" alt="Fig.9 pair-level Δ heterogeneity across 22 pairs" width="48%" />
  <img src="./assets/fig10_aabb_abb_group_comparison.png" alt="Fig.10 AABB vs ABB group comparison of pair-level mean Δ" width="48%" />
</p>
<p align="center"><em>Left — Fig.9: pair-level Δ across 22 reduplicated pairs (heterogeneity). Right — Fig.10: AABB vs ABB group comparison of pair-level mean Δ (AABB p≈0.193 ≠ overall Welch p=0.013).</em></p>

### 2. Anna Karenina · AI Literary Guide
**Problem → method → result:** Long-form literary reading needs grounded, persona-aware help without losing narrative voice. Built an interactive guide with **RAG-style** reading support and **7 persona agents** (sliding context: last **10** turns; reply length **40–90** characters), plus a live **System Architecture & Prompt Design** panel for context engineering.

- Demo: https://annakareninaof17.pages.dev/

### 3. 2711 Editor · Novel → Branching VN
**Problem → method → result:** Full novels overflow LLM context windows when generating branching visual novels. Designed a FastAPI pipeline with **heuristic context-window optimisation** (smart truncation + chapter-aware sampling): upload → story bible → outline → playable branching narrative.

- Demo: https://2711editor.pages.dev  
- Repo: [2711-editor](https://github.com/yuanyiqi422-byte/2711-editor)

### 4. Leping Ancient Stages · Digital Map
**Problem → method → result:** Stage heritage records were scattered across **400+** candidate sites and **103** sources. Curated and geocoded **28** mapped stages on Amap / Leaflet with fallback, and shipped **Export JSON / CSV** from cleaned `stages.json`.

- Demo: https://leping-stages-map.pages.dev/

### 5. More
| Project | Note | Link |
|--------|------|------|
| Foreign Literature Review | Gamified quiz / review site | [waiguo-wenxue-review.pages.dev](https://waiguo-wenxue-review.pages.dev) |
| Yuyun Jinhe (Grand Canal Corpus) | **National Undergraduate Innovation and Entrepreneurship Training Program** · multimodal canal language landscape & knowledge graph · **1,182** structured corpus entries (+128 field samples) | WeChat: 语韵津河 (NLP-based analysis & GIS maps) |

---

## What I work with

**Skills**
```text
Corpus crawl · clean · annotate · evaluate
Prompt engineering · RAG / multi-agent dialogue
Statistical testing (Welch's t, effect size reporting)
LLM evaluation against human gold standards
```

**Tools**
```text
Python · FastAPI · Pandas / NumPy / SciPy
JS · Cloudflare Pages · Netlify Functions
Leaflet / AMap · Git
```

---

<details>
<summary>中文</summary>

天津大学汉语言文学在读（2027 届）。拟申请方向：Data Science / Business Statistics / Social Computing。主线：语料构建 → 统计检验 → 大模型评测 → 可点击 Demo。文学 AI 导读、互动阅读生成、古戏台数字地图；叠词情感评测与大创语韵津河。邮件联系。

</details>

---

⭐ For DSBS-style review, start with **Reduplicated Adjectives** (stats + figures); for clickable demos, open **Anna** or **2711**.
