<h1 align="center">Jere Salonen</h1>

<p align="center">
  <a href="https://www.jersal.net">jersal.net</a> &middot;
  <a href="https://www.linkedin.com/in/jeresalonen/">LinkedIn</a>
</p>

---

### About me

Ever since agentic workflows appeared I have been pushing automation even slightly unreasonably. I trust the agents sometimes too much, but with intention.

The Jersal repository family is my personal framework for keeping up with the changing world of AI, understanding the capabilities firsthand, and testing where the limits actually are. Consider it a not so serious playground to push and benchmark AI assisted development, while keeping strict processes and manual workflows in place elsewhere. The goal is to find out just how far this can go.

I am a full stack developer and infrastructure engineer from Turku, Finland. This ecosystem reflects my current interests: agentic workflows, AI assisted development, infrastructure as code, and practical automation that actually ships.

---

### Current stack

**PI** ![PI](https://img.shields.io/badge/PI-000?style=flat-square)
Workflow harness for agentic development. It connects model providers to development tasks and orchestrates the entire AI assisted workflow. I chose it because it gives me direct control over how agents operate while staying out of the way.

**DeepSeek V4 Flash** ![DeepSeek V4 Flash](https://img.shields.io/badge/DeepSeek_V4_Flash-4F6BFF?style=flat-square)
My goto model for day to day AI assisted development. Extremely cheap per token while still delivering quality results. It is the default model I reach for when working through the harness.

**OpenCode GO** ![OpenCode GO](https://img.shields.io/badge/OpenCode_GO-000?style=flat-square)
Model provider that handles API access to DeepSeek and other models. It slots into the PI workflow seamlessly without extra friction.

**Azure** ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
Deployment infrastructure for everything that needs to run. Reliable, has good Terraform support, and covers the full stack from databases to container hosting.

Everything else depends on what fits the project.

### Repositories

**Core**

| Name | Repository | Visibility | Description |
|---|---|---|---|
| Core Infrastructure | jersal-projects-core | Public | Shared Azure infrastructure, PostgreSQL, RBAC, portfolio site |
| Project Template | jersal-project-template | Public | Project scaffolding, planning first workflow, CI templates |

Infrastructure managed with Terraform, deployed via GitHub Actions with OIDC and isolated state backends.

**Projects**

| Name | Repository | Visibility | URL |
|---|---|---|---|
| Stock Analyst | jersal-stock-analyst | Private | Coming soon |
| Fitness Assistant | jersal-fitness-assistant | Private | Coming soon |
