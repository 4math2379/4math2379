<p align="center">
  <img src="assets/banner.svg" alt="4Math, AI architect: open-source MCP servers, agents and models, from the GPU to the cloud" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jonathansinien/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Let's%20talk-0A66C2?style=for-the-badge"></a>
  <a href="https://huggingface.co/4math"><img alt="Hugging Face" src="https://img.shields.io/badge/Hugging%20Face-4math-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"></a>
  <a href="https://x.com/Vesuviian"><img alt="X" src="https://img.shields.io/badge/X-@Vesuviian-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://www.youtube.com/@professorchain"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-professorchain-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>
</p>

<h3 align="center">I design AI systems that agents can rely on:<br>MCP servers, open models on GPUs you control, and the cloud underneath.</h3>

<p align="center"><sub>Paris, France · AI architecture · Model Context Protocol · NVIDIA · Hugging Face · AWS · DevSecOps</sub></p>

---

## 🧭 What I do

<table>
<tr>
<td width="50%" valign="top">

### 🔌 MCP servers and agent tools
I turn an API, a product or a workflow into tools any AI agent can call: typed inputs, guard rails that explain how to fix a bad call, stdio and HTTP transports, tests and docs.

</td>
<td width="50%" valign="top">

### 🟩 Open models on your GPUs
Open models such as Nemotron, Mistral and gpt-oss, served with vLLM or managed inference, from serverless GPUs to on-prem clusters linked by InfiniBand, and wired into the agents and editors your team already uses.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🇪🇺 Sovereign AI
Architectures that keep your data where you decide: European cloud, on-prem AI factories, RAG over your own documents, with a cost model for each option.

</td>
<td width="50%" valign="top">

### ☁️ Cloud and DevSecOps foundations
AWS multi-account platforms, Terraform, Kubernetes, CI/CD, Security Hub and FinOps: the ground an AI system needs to run safely and at a known cost.

</td>
</tr>
</table>

## 🚀 Flagship: Tiled Map Builder MCP

<a href="https://github.com/4math2379/Tiled-MCP-Server"><img src="https://raw.githubusercontent.com/4math2379/Tiled-MCP-Server/main/docs/assets/banner.svg" alt="Tiled Map Builder MCP: an isometric crypt room built from the project's sprites" width="100%"></a>

**An MCP server that lets AI agents build isometric [Tiled](https://www.mapeditor.org) maps**: rooms, corridors, doors, traps, chests and spawns, validated and saved as files that open directly in Tiled.

- 🗺️ **30 MCP tools**, 3 one-call layout presets and 20 themes, 12 of them with bundled isometric sprites.
- 🛡️ **Built for agents**: an invalid placement fails with a message that says how to fix it, and `validate_map` checks the map before export.
- 🔌 Works with **any MCP client**: Claude Code, Claude Desktop, Cursor, VS Code, Zed, OpenCode, and agents running NVIDIA Nemotron.
- 🤗 **Live on Hugging Face**: describe a map in any language and download it, or connect your agent to the hosted MCP endpoint. Paid model calls run on the visitor's own Hugging Face account.

<p>
  <a href="https://huggingface.co/spaces/4math/tiled-map-builder"><img alt="Open in Hugging Face Spaces" src="https://huggingface.co/datasets/huggingface/badges/resolve/main/open-in-hf-spaces-md.svg"></a>
  <a href="https://github.com/4math2379/Tiled-MCP-Server"><img alt="Source on GitHub" src="https://img.shields.io/badge/Source-Tiled--MCP--Server-181717?style=for-the-badge&logo=github"></a>
</p>

```bash
claude mcp add --transport http tiled-map-builder https://4math-tiled-map-builder.hf.space/mcp \
  --header "Authorization: Bearer hf_YOUR_TOKEN"
```

## 🧪 More open work

| Project | What it is | Built with |
|---|---|---|
| **[nvidia-coding-agent-lab](https://github.com/4math2379/nvidia-coding-agent-lab)**<br><sub>[▶ animated architecture](https://4math2379.github.io/nvidia-coding-agent-lab/)</sub> | An NVIDIA-specialised coding agent: Nemotron served with vLLM on serverless GPUs, wired into Zed and OpenCode, with NVIDIA's docs available over MCP. The same container runs on-prem, and a multi-node InfiniBand lab rehearses the cluster. | Nemotron · vLLM · Modal · MCP |
| **[Recherches-IA-Souveraine](https://github.com/4math2379/Recherches-IA-Souveraine)** 🇫🇷 | Research reports and Terraform templates for hosting generative AI while keeping control of your data: Mistral on Scaleway, NVIDIA InfiniBand AI factories, GPU clusters with Slurm. | Mistral · Scaleway · NVIDIA · Terraform |
| **[FAB_Prediction_Model](https://huggingface.co/4math/FAB_Prediction_Model)** 🤗 | An open model (MIT) that predicts the win rate of custom decks for the Flesh and Blood card game, trained on simulated games. An educational project on machine learning for game balance. | scikit-learn · Hugging Face |
| **[aws-security-hub-soc](https://github.com/4math2379/aws-security-hub-soc)** | Security assessment across AWS accounts for SOC and audit teams: Security Hub findings plus Prowler audits. | AWS · Prowler · Shell |
| **[aws-finops-tools](https://github.com/4math2379/aws-finops-tools)** | A Docker-based toolkit for AWS cost management and optimisation. | AWS · Docker |

## 🔭 Now

I'm moving my agent work into the open. The MCP servers and models behind my projects are being published here and on [Hugging Face](https://huggingface.co/4math), one at a time, each with docs, tests and a live demo.
**⭐ Star or follow to get them first.**

## 🧱 Toolbox

| | |
|---|---|
| **AI and agents** | ![Model Context Protocol](https://img.shields.io/badge/MCP-8B5CF6?style=for-the-badge&logo=modelcontextprotocol&logoColor=white) ![NVIDIA](https://img.shields.io/badge/NVIDIA%20Nemotron-76B900?style=for-the-badge&logo=nvidia&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge) ![Mistral AI](https://img.shields.io/badge/Mistral%20AI-FA520F?style=for-the-badge&logo=mistralai&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white) ![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-01A88D?style=for-the-badge) |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Shell](https://img.shields.io/badge/Shell-121011?style=for-the-badge&logo=gnubash&logoColor=white) |
| **Cloud and platform** | ![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge) ![Scaleway](https://img.shields.io/badge/Scaleway-4F0599?style=for-the-badge&logo=scaleway&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) |
| **Delivery and security** | ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white) ![AWS Security Hub](https://img.shields.io/badge/Security%20Hub-DD344C?style=for-the-badge) |

## 📈 Track record

<table>
<tr>
<td align="center" width="25%"><h3>100+</h3><sub>AWS resources automated<br>across multiple accounts</sub></td>
<td align="center" width="25%"><h3>20+</h3><sub>applications shipped<br>through CI/CD pipelines I built</sub></td>
<td align="center" width="25%"><h3>−40%</h3><sub>cloud infrastructure costs<br>after optimisation</sub></td>
<td align="center" width="25%"><h3>10+</h3><sub>AWS accounts covered<br>by Security Hub</sub></td>
</tr>
</table>

<sub>Most of my professional work lives in private repositories; what you see here is the open part.</sub>

## 🤝 Let's work together

Building an AI agent, an MCP server for your product, or a private AI platform? I can help with **architecture reviews**, **MCP server design and builds**, and **open-model deployments** on cloud or on-prem GPUs.

<a href="https://www.linkedin.com/in/jonathansinien/"><img alt="Message me on LinkedIn" src="https://img.shields.io/badge/Message%20me%20on%20LinkedIn-0A66C2?style=for-the-badge"></a>

---

<p align="center">
  <i>"Between AI, DevOps and game design, I share my creations and take you behind the scenes of how they're made."</i>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=4math2379&color=8B5CF6&style=flat-square" alt="Profile views">
</p>
