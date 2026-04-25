<h1 align="center">Hi, I'm Sathish 👋</h1>

<p align="center">
  <em>Engineering agentic AI on the data lakehouse.</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/satykrish"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
  <img alt="Focus" src="https://img.shields.io/badge/focus-agentic%20AI-FF3621">
  <img alt="Platform" src="https://img.shields.io/badge/platform-Databricks-FF3621?logo=databricks&logoColor=white">
</p>

---

### 🤖 What I'm building

Production-grade **agentic AI systems** on Databricks Mosaic AI — document intelligence pipelines, retrieval-grounded agents, eval-gated MLOps, and the developer workflows that let AI coding agents (Claude Code + Spec-Kit) actually ship them. I care about the boring parts: governance, identity passthrough, deploy ordering, evaluation gates, and the small architectural decisions that decide whether a demo becomes a production system.

### 🔭 Where I go deep

- **Agent frameworks** — Mosaic AI Agent Framework, MLflow `auth_policy` + `ModelServingUserCredentials`, end-to-end OBO so user identity flows through retrieval, SQL, and downstream serving calls.
- **Document intelligence** — `ai_parse_document`, layout-aware section explosion, typed KPI extraction, quality rubrics that decide what reaches the index.
- **AI-native developer tooling** — Spec-Kit constitutions, Claude Code skill bundles, CLEARS eval gates as deploy promoters.
- **Cloud-native data platforms** — Databricks Asset Bundles, Unity Catalog, Lakeflow SDP, Mosaic AI Vector Search, Lakebase, AI Gateway, Databricks Apps.

### 🌟 Recent open-source work

<table>
<tr>
<td width="60%" valign="top">

#### 📄 [databricks-document-intelligence-agent](https://github.com/SatyKrish/databricks-document-intelligence-agent)

A Databricks-native document intelligence + agent **reference implementation**. Lakeflow SDP pipeline (`ai_parse_document` → typed KPIs → 5-dim quality rubric) → Mosaic AI Vector Search → cited-answer agent on Model Serving (with end-to-end OBO) → Streamlit app on Databricks Apps → MLflow CLEARS eval gate. Built end-to-end with Spec-Kit and Claude Code. MIT-licensed.

</td>
<td width="40%" valign="top">

```
PDF ─▶ Bronze ─▶ Silver
                  │
                  ▼
             Gold + quality
                  │
                  ▼
          Vector Search index
                  │
                  ▼
          Cited-answer agent
                  │
                  ▼
            Analyst chat
```

</td>
</tr>
</table>

### 🛠️ Tooling I reach for

<p>
  <img alt="Databricks" src="https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white">
  <img alt="Mosaic AI" src="https://img.shields.io/badge/Mosaic%20AI-1B3139">
  <img alt="MLflow" src="https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white">
  <img alt="Unity Catalog" src="https://img.shields.io/badge/Unity%20Catalog-1B3139">
  <img alt="Vector Search" src="https://img.shields.io/badge/Vector%20Search-FF3621">
  <img alt="Lakebase" src="https://img.shields.io/badge/Lakebase-336791?logo=postgresql&logoColor=white">
</p>
<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white">
  <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white">
</p>
<p>
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude%20Code-D97757">
  <img alt="Spec-Kit" src="https://img.shields.io/badge/Spec--Kit-6E5494">
  <img alt="Anthropic SDK" src="https://img.shields.io/badge/Anthropic%20SDK-D97757">
</p>

### 💡 What I think about

> The next decade of software engineering isn't "AI writes the code for you." It's **specifications becoming first-class artifacts**, **constitutions gating decisions**, and **eval suites replacing human approval at the merge boundary**. AI coding agents are the implementation surface, not the brains.

### 🤝 Let's talk

- 💼 [LinkedIn](https://www.linkedin.com/in/satykrish) — best for collaboration / consulting
- 🐙 Open issues on any of my repos
- 🌱 Always open to: agentic AI patterns, governed retrieval, MLOps for LLMs, AI-native developer workflows

<!---
SatyKrish/SatyKrish is a ✨ special ✨ repository because its `README.md` (this file)
appears on your GitHub profile. You can click the Preview link to see your changes.
--->
