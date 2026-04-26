<h1 align="center">Hi, I'm Sathish 👋</h1>

<p align="center">
  <em>Building agentic AI systems and the platforms they run on.</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/satykrish"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
  <img alt="Focus" src="https://img.shields.io/badge/focus-agentic%20AI-D97757">
  <img alt="Cloud" src="https://img.shields.io/badge/cloud-AKS%20%2B%20EKS-1B6EC2">
  <img alt="Data" src="https://img.shields.io/badge/data-Databricks-FF3621?logo=databricks&logoColor=white">
</p>

---

### 🤖 What I'm building

- **Agentic AI systems** — production agents with retrieval, tools, governance, and eval gates.
- **Agent harnesses** — built on the **Claude Agents SDK** and the **OpenAI Agents SDK**, picking the right primitives for the job (subagents, tool use, structured outputs, long-running tasks).
- **Data integration on Databricks** — Mosaic AI Agent Framework, Vector Search, Lakeflow SDP, Unity Catalog, Lakebase. Where the agents get their grounded context.
- **AI-assisted coding workflows** — **Claude Code** and **Codex** as the implementation surface, **Spec-Kit** + constitutions as the design surface, eval suites as the merge gate.
- **Container platforms** — **AKS** (Azure) and **EKS** (AWS). Kubernetes-native deployment for everything that doesn't live inside Databricks.

### 🔭 Where I go deep

- **Agent SDKs** — Claude Agents SDK, OpenAI Agents SDK, Mosaic AI Agent Framework. Comparative strengths: subagent isolation vs. handoffs, tool-use ergonomics, OBO identity, latency under realistic loads.
- **Document intelligence** — `ai_parse_document`, layout-aware section explosion, typed KPI extraction, quality rubrics that decide what reaches the index.
- **AI-native developer tooling** — Spec-Kit constitutions, Claude Code skill bundles, Codex orchestration, CLEARS eval gates as deploy promoters.
- **Cloud-native platforms** — AKS / EKS, Helm, Terraform, identity federation, secrets management. Boring, load-bearing.

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

**Agent SDKs & runtimes**
<p>
  <img alt="Claude Agents SDK" src="https://img.shields.io/badge/Claude%20Agents%20SDK-D97757">
  <img alt="OpenAI Agents SDK" src="https://img.shields.io/badge/OpenAI%20Agents%20SDK-412991?logo=openai&logoColor=white">
  <img alt="Anthropic SDK" src="https://img.shields.io/badge/Anthropic%20SDK-D97757">
  <img alt="OpenAI SDK" src="https://img.shields.io/badge/OpenAI%20SDK-412991?logo=openai&logoColor=white">
  <img alt="Mosaic AI" src="https://img.shields.io/badge/Mosaic%20AI%20Agent%20Framework-1B3139">
</p>

**AI-assisted development**
<p>
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude%20Code-D97757">
  <img alt="Codex" src="https://img.shields.io/badge/Codex-412991?logo=openai&logoColor=white">
  <img alt="Spec-Kit" src="https://img.shields.io/badge/Spec--Kit-6E5494">
</p>

**Data & lakehouse**
<p>
  <img alt="Databricks" src="https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white">
  <img alt="MLflow" src="https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white">
  <img alt="Unity Catalog" src="https://img.shields.io/badge/Unity%20Catalog-1B3139">
  <img alt="Vector Search" src="https://img.shields.io/badge/Vector%20Search-FF3621">
  <img alt="Lakebase" src="https://img.shields.io/badge/Lakebase-336791?logo=postgresql&logoColor=white">
</p>

**Platform & cloud**
<p>
  <img alt="Azure AKS" src="https://img.shields.io/badge/Azure%20AKS-0078D4?logo=microsoftazure&logoColor=white">
  <img alt="AWS EKS" src="https://img.shields.io/badge/AWS%20EKS-FF9900?logo=amazoneks&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white">
  <img alt="Helm" src="https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=white">
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white">
</p>

**Languages**
<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white">
</p>

### 💡 What I think about

> The interesting question for the next few years isn't "which agent SDK wins" or "Claude Code vs. Codex." It's: **what's the smallest, most testable unit of intent we can hand an AI implementer**, and **what's the eval surface that decides whether their output ships?** The SDKs are tactical; specifications, constitutions, and eval gates are the actual leverage.

### 🤝 Let's talk

- 💼 [LinkedIn](https://www.linkedin.com/in/satykrish) — best for collaboration / consulting
- 🐙 Open issues on any of my repos
- 🌱 Always open to: multi-SDK agent patterns, AI-assisted dev workflows, governed retrieval on Databricks, AKS/EKS at scale

<!---
SatyKrish/SatyKrish is a ✨ special ✨ repository because its `README.md` (this file)
appears on your GitHub profile. You can click the Preview link to see your changes.
--->
