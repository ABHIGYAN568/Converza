# Converza 🚀
### An Autonomous, Serverless AI News Curation Engine Driven through Multi-Agent LLMs

**Converza** is an advanced, completely automatic intelligence pipeline designed to combat facts overload. Every few hours, it aggregates over 1,000 raw generation and AI articles, filtering them thru a sophisticated multi-agent LLM community. The stop end result is a highly delicate feed of 25 fact-checked, premium insights. 

By leveraging GitHub Actions for compute and GitHub Pages for distribution, Converza operates absolutely on a serverless architecture—turning in countless scalability at certainly zero infrastructure price.

---

## 🛑 The Information Bottleneck

Today's tech specialists are drowning in noise:
- A day by day flood of thousands of low-effort, repetitive articles.
- Zero reliable metrics for detecting media bias or actual credibility.
- Traditional RSS feeds and keyword aggregators simply generate extra muddle.
- Hours wasted manually sifting via feeds to locate real precious insights.

**The end result:** High volume, low cost.

---

## 💡 The Converza Approach

Converza flips the traditional information aggregator model the wrong way up:
- **Multi-Agent Evaluation:** Instead of counting on a unmarried AI model, a network of LLMs debate and rating articles.
- **Transparent Scoring:** Every curated piece is graded on novelty, factual accuracy, impact, and relevance.
- **Zero-Server Ecosystem:** Eliminates steeply-priced cloud backends and databases.
- **Static Delivery:** Outputs are compiled into static JSON APIs and dispensed globally thru CDN, making it uncrashable.

---

## ⚙️ Architecture &amp; Data Flow


**Ingestion:** 30+ Tech & Academic Sources (APIs/RSS)  
&nbsp;&nbsp;&nbsp;&nbsp;⏬  
**Phase 1: High-Speed Triage** (Fast LLMs instantly discard 70% of irrelevant data)  
&nbsp;&nbsp;&nbsp;&nbsp;⏬  
**Phase 2: Deep Analysis** (Fact-checking, bias detection, and credibility scoring)  
&nbsp;&nbsp;&nbsp;&nbsp;⏬  
**Phase 3: The Consensus Engine** (Final selection of the top 25 insights)  
&nbsp;&nbsp;&nbsp;&nbsp;⏬  
**Generation:** Static JSON Feeds + AI-Voiced Audio Digests  
&nbsp;&nbsp;&nbsp;&nbsp;⏬  
**Distribution:** Cached globally via GitHub Pages  

---

## ✨ Platform Highlights

- **Multi-Tiered AI Vetting:** Bulk filtering followed by deep intelligence exams.
- **Explainable AI Curation:** Know exactly *why* an editorial became decided on.
- **Broad Source Spectrum:** Monitors enterprise blogs, open-supply repos, academic journals, and authorities tech updates.
- **Audio Digests:** Automated text-to-speech news summaries using Gemini TTS.
- **Self-Sustaining CI/CD:** Scheduled workflows execute robotically each four hours.
- **Auditable Logic:** Completely transparent decision-making system.

---

## 🛠️ Technology Stack

Our guiding principle: **Maximum processing intelligence with minimal infrastructure overhead.**

- **Core Engine:** Python 3.Eleven  
- **AI Models:** Groq API (LLaMA, Gemma)  
- **Client Side:** Vanilla JavaScript &amp; HTML5  
- **Pipeline Orchestration:** GitHub Actions  
- **Hosting &amp; CDN:** GitHub Pages  
- **Database:** Static JSON files  
- **Voice Synthesis:** Gemini TTS  

---

## 📊 Economics &amp; Performance Metrics

- **Input:** ~1,000 uncooked links in line with cycle  
- **Output:** The absolute pleasant ~25 articles  
- **Processing Time:** ~forty five minutes per execution  
- **Operating Cost:** **$0.00 / month** (Fraction of conventional cloud setups)  
- **Scalability:** Static JSON APIs mean tens of millions of users can fetch facts with out increasing backend load.

---

## 💻 Running the Engine Locally

Want to test the pipeline on your personal gadget? Follow those steps:

```bash
git clone [https://github.Com/AbhigyanRaj/Converza.Git](https://github.Com/AbhigyanRaj/Converza.Git)
cd Converza
python3 -m venv venv
supply venv/bin/activate  # Use `venvScriptsactivate` on Windows
pip deploy -r necessities.Txt
python src/backend/orchestrator.Py
