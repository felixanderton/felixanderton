# Felix Anderton
 
AI Engineer. Previously AI student at King's College London. I like building things.
---
 
## Featured project
 
### [rl-portfolio-agent](https://github.com/felixanderton/rl-portfolio-agent)
PPO agent for dynamic capital allocation across 5 US sector ETFs. The interesting part is the reward function: instead of raw returns or a sparse terminal Sharpe, it uses the **Differential Sharpe Ratio** (Moody & Saffell, 1998) — a dense, differentiable approximation that gives a risk-adjusted gradient at every timestep via EMA accumulators. Includes a full ablation study, written falsification criteria, ClearML experiment tracking, and post-hoc statistical analysis of results.
 
`PPO` `Differential Sharpe` `Gymnasium` `ClearML` `Modal` `Docker`

### [running-ai](https://github.com/felixanderton/running-ai)
An AI running coach you talk to in Claude: it designs your training program, pushes structured workouts to your **Garmin**, and analyses each completed run to adjust the plan — with a Google Sheet as the living program plus a performance dashboard. The interesting part is the architecture: **Claude** is the reasoning layer, and the whole thing ships as a remote MCP server on Cloud Run that Claude connects to as an OAuth-secured custom connector** — the server is pure plumbing (Garmin + Sheets tools), so all the coaching logic lives in the conversation, not in code. It translates natural-language sessions into Garmin's workout DTO schema with real on-watch **pace targets**, and works around the absence of an official Garmin API via the community library + a one-time MFA token bootstrap.

  `MCP` `FastMCP` `Claude` `Cloud Run` `Google Sheets`
 
---
 
## Other work
 
| Repo | What it is |
|---|---|
| [5CCSANLP-Coursework](https://github.com/felixanderton/5CCSANLP-Coursework) | NLP coursework — KCL final year |
| [ML-CW-2](https://github.com/felixanderton/ML-CW-2) | Machine learning coursework — KCL final year |
| [AI-Notes](https://github.com/felixanderton/AI-Notes) | Running notes from my AI degree |
 
---
 
## Stack
 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
