<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Amir Mohammadisarab: AI Engineer, Robotics Engineer, MLOps Engineer" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://m-amir1998.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-1e293b?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjkiLz48cGF0aCBkPSJNMyAxMmgxOE0xMiAzYzIuNSAyLjYgMy44IDUuNiAzLjggOXMtMS4zIDYuNC0zLjggOWMtMi41LTIuNi0zLjgtNS42LTMuOC05UzkuNSA1LjYgMTIgM3oiLz48L3N2Zz4="></a>
  <a href="https://www.linkedin.com/in/amir-mohamadisarab-63737b173/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-1e293b?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTQgOWgzLjZ2MTFINHpNNS44IDMuNWEyLjEgMi4xIDAgMSAxIDAgNC4yIDIuMSAyLjEgMCAwIDEgMC00LjJ6TTkuOCA5aDMuNHYxLjVoLjA1Yy40OC0uOSAxLjY0LTEuODUgMy4zNy0xLjg1IDMuNiAwIDQuMjcgMi4zNyA0LjI3IDUuNDVWMjBoLTMuNTV2LTUuM2MwLTEuMjctLjAyLTIuOS0xLjc3LTIuOS0xLjc3IDAtMi4wNCAxLjM4LTIuMDQgMi44VjIwSDkuOHoiLz48L3N2Zz4="></a>
  <a href="https://scholar.google.com/scholar?q=Amir+Mohammadisarab"><img alt="Google Scholar" src="https://img.shields.io/badge/Google%20Scholar-1e293b?style=for-the-badge&logo=googlescholar&logoColor=white"></a>
  <a href="mailto:amohammadisarab@umh.es"><img alt="Email" src="https://img.shields.io/badge/Email-1e293b?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

<p align="center">
  PhD researcher at the <b>UWICORE Lab, Universidad Miguel Hernández de Elche</b> (Spain).
  I build perception and reasoning systems for <b>connected automated vehicles</b>: fusing onboard sensors with V2X data,
  catching the ghost objects that fusion creates with fine-tuned LLMs, and running it all as tested, reproducible pipelines.
</p>

<p align="center">
  🎯 <b>Open to</b> &nbsp;AI Engineer · Robotics Engineer · MLOps Engineer roles
</p>

## What I do

<table>
<tr>
<td width="33%" valign="top">

**🧠 AI Engineering**<br>
LLMs as reliable system components: agents with guardrails, LoRA/QLoRA fine-tuning, RAG, evaluation harnesses, GNNs.

</td>
<td width="33%" valign="top">

**🤖 Robotics**<br>
Perception for autonomous driving: multisensor and V2X fusion, Kalman tracking, data association, SUMO and CARLA simulation, deep RL.

</td>
<td width="33%" valign="top">

**⚙️ MLOps / LLMOps**<br>
Research code that survives production: Docker sandboxes, CI/CD, DVC and MLflow, large sweeps on GPU servers and HTCondor.

</td>
</tr>
</table>

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### OCTOPUS
<p><img alt="Robotics" src="https://img.shields.io/badge/Robotics-0891b2?style=flat-square"> <img alt="MLOps" src="https://img.shields.io/badge/MLOps-9333ea?style=flat-square"></p>

A simulator for onboard and V2X data fusion that runs online with SUMO: occlusion-aware sensing, Kalman tracking, Collective Perception Messages, S2S/S2G fusion and parameter sweeps on HTCondor.

<sub>Python · SUMO · DuckDB · mypy strict · pytest</sub>

</td>
<td width="50%" valign="top">

### AgentEnvForge
<p><img alt="MLOps" src="https://img.shields.io/badge/MLOps-9333ea?style=flat-square"> <img alt="AI" src="https://img.shields.io/badge/AI-4f46e5?style=flat-square"></p>

Define a coding task once, run any AI agent against it in a locked-down Docker sandbox, grade it with tests the agent never saw, and reproduce every run. Batch experiments with parallel workers.

<sub>Python · Docker · Typer · Pydantic · GitHub Actions</sub>

</td>
</tr>

<!-- Hidden until finished: move a <td> block above (or delete these comment markers) to show it again.
<tr>
<td width="50%" valign="top">

### LLM Ghost Object Mitigation
<p><img alt="AI" src="https://img.shields.io/badge/AI-4f46e5?style=flat-square"> <img alt="Robotics" src="https://img.shields.io/badge/Robotics-0891b2?style=flat-square"></p>

Fine-tuned LLMs (LoRA/QLoRA) act as verifiers inside a V2X cooperative-perception pipeline, filtering, repairing and preventing ghost objects at three intervention points. Benchmarked against gradient-boosting and GNN policies.

<sub>Python · PyTorch · PEFT · Ollama · scikit-learn</sub>

</td>
<td width="50%" valign="top">

### CoPerceptionOps
<p><img alt="MLOps" src="https://img.shields.io/badge/MLOps-9333ea?style=flat-square"> <img alt="Robotics" src="https://img.shields.io/badge/Robotics-0891b2?style=flat-square"></p>

Data platform for cooperative perception: a DVC pipeline turns ~196 GB of raw OPV2V into a versioned Parquet + DuckDB feature store with difficulty-stratified benchmark splits (226K objects, zero ETL failures).

<sub>Python · DVC · DuckDB · Polars · Pydantic</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### E2E Driving under Perception Errors
<p><img alt="Robotics" src="https://img.shields.io/badge/Robotics-0891b2?style=flat-square"> <img alt="AI" src="https://img.shields.io/badge/AI-4f46e5?style=flat-square"></p>

Closed-loop study in CARLA of how ghost and missed objects degrade end-to-end driving models (MindDrive, TransFuser): Bench2Drive routes, collision forensics, phantom-braking checks and annotated driving videos.

<sub>Python · PyTorch · CARLA · Bench2Drive</sub>

</td>
<td width="50%" valign="top">

### Agentic NFV/SDN Orchestration
<p><img alt="AI" src="https://img.shields.io/badge/AI-4f46e5?style=flat-square"></p>

A safety-wrapped agent for a 5G industrial drone network: an LLM proposes where to compute each task, while guardrails, a network digital twin, a validator and a critic decide what is applied. Compared head-to-head with classical schedulers.

<sub>Python · LangGraph · Ollama · FastAPI</sub>

</td>
</tr>
-->

</table>

<sub>🔒 The code for these projects is private for now. I'm happy to walk you through either of them.</sub>

## Toolbox

<p align="center">
  <img alt="Python, C++, PyTorch, scikit-learn, Docker, GitHub Actions, FastAPI, Linux, Git, Bash, SQLite, LaTeX" src="https://skillicons.dev/icons?i=python,cpp,pytorch,sklearn,docker,githubactions,fastapi,linux,git,bash,sqlite,latex&perline=12">
  <br>
  <sub>Also: Hugging Face Transformers · PEFT · LangGraph · Ollama · MLflow · DVC · DuckDB · SUMO · CARLA · HTCondor</sub>
</p>

## Selected publications

- [**Fusion or Confusion? Potential and Challenges in Fusion of Onboard Sensors and V2X Data in Cooperative Perception**](https://ieeexplore.ieee.org/abstract/document/11230764/) · *IEEE CSCN 2025*
- [**How the Fusion of Onboard Sensors and V2X Data can improve (or not) the Cooperative Perception of Connected Automated Vehicles**](https://ieeexplore.ieee.org/abstract/document/11174443/) · *IEEE VTC 2025-Spring*
- [**Disaster Relief in Industrial IoT: UAV Trajectory Design and Resource Allocation in 6G Non-Terrestrial Networks**](https://ieeexplore.ieee.org/document/10468637) · *IEEE Open Journal of the Communications Society, 2024*

<sub>→ [All publications on Google Scholar](https://scholar.google.com/scholar?q=Amir+Mohammadisarab)</sub>
