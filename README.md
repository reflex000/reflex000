# Hi, I'm Sidharath 👋

**Site Reliability Engineer** — I keep a large-scale digital platform running, and I build
**AI agents that make the whole team faster at it**.

🚗 **[Drive through my 3D portfolio → reflex000.github.io/portfolio](https://reflex000.github.io/portfolio/)**

My focus for the last two years: taking the toil out of production operations — alert chaos,
incident triage, log spelunking — by pairing solid SRE fundamentals (Azure, KQL, Grafana,
Logic Apps, Terraform) with agentic AI that's actually safe to run inside an enterprise.

---

## 🔭 What I've built

| Project | What it is |
|---------|-----------|
| 🤖 [**agentic-sre**](https://github.com/reflex000/agentic-sre) | **"Jarvis"** — an agentic SRE teammate in Microsoft Teams. Managed-identity auth (zero stored secrets), version-controlled read-only *skills*, a grounded knowledge base, and a senior-SRE persona. It traces customer incidents across platform logs in chat, so any engineer triages like the most experienced one. |
| 🚨 [**alerting-lmf**](https://github.com/reflex000/alerting-lmf) | **Logic Module Framework** — one alerting pipeline for *any* source (Splunk, Okta, Veeam, Control-M, Twilio…). Receivers normalize to one contract; one processor correlates, opens/auto-resolves ServiceNow incidents, and routes adaptive cards to the right Teams channel. New source = one small receiver. |
| 📊 [**observability**](https://github.com/reflex000/observability) | Grafana dashboards over Azure Monitor/KQL that follow a request across every platform layer — API-to-Core journey, surge detection, customer-UUID incident investigation, session tracing. Built from real incident patterns. |

> All three repos are real production work, published with every company-specific identifier
> fictionalized (invented company "Nexora", randomly generated IDs). The architecture and code
> are the real thing.

---

## 🤝 How I help others with AI

The pattern behind Jarvis is the part I care about most: **skills, not prompts**.

- Every capability is a self-contained, version-controlled runbook a reviewer can audit *before*
  the agent runs it.
- Everything is **read-only by construction** — the agent investigates, humans decide.
- Knowledge is **grounded**: service maps and metrics catalogs the LLM can't hallucinate around.
- Secret-safety is designed in: managed identity end-to-end, safe-identifier-only output.

The result: on-call engineers who used to grep logs for an hour now ask a bot in Teams and get a
root-cause handoff in two minutes — with every step auditable.

---

## 🛠️ Toolbox

`Azure` · `Azure Monitor / KQL` · `Grafana` · `Logic Apps` · `Azure Functions` · `AKS / Kubernetes`
· `Terraform` · `Node.js` · `Python` · `PowerShell` · `ServiceNow` · `MuleSoft (observing it, anyway)`
· `Bot Framework` · `LLM agents & skills`

---

## 📫 Reach me

- ✉️ ss.sidharath@gmail.com
- 💼 LinkedIn: *(link coming soon)*
