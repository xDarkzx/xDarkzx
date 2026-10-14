<p align="center">
  <img src="assets/banner.svg" alt="Dan: AI Software Engineer, Azure, MCP and agents" width="100%">
</p>

<p align="center">
  <a href="mailto:dkstudiosnz@gmail.com"><img src="https://img.shields.io/badge/Email-dkstudiosnz%40gmail.com-0b1020?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://discord.gg/BGn8Ujh37m"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://x.com/daehonz1"><img src="https://img.shields.io/badge/X-@daehonz1-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
  <img src="https://img.shields.io/badge/Open%20to-AI%20engineering%20roles-22c55e?style=for-the-badge" alt="Open to AI engineering roles">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/stars%20across%20my%20projects-233-f59e0b?style=flat-square&logo=github" alt="233 stars">
  <img src="https://img.shields.io/badge/outside%20contributors-10-38bdf8?style=flat-square" alt="10 outside contributors">
  <img src="https://img.shields.io/badge/MCP%20tools%20shipped-500%2B-818cf8?style=flat-square" alt="500+ MCP tools shipped">
  <img src="https://img.shields.io/badge/based%20in-New%20Zealand-e879f9?style=flat-square" alt="New Zealand">
</p>

I build AI systems that do real work and can be trusted with it: agents that operate desktop
software through the Model Context Protocol, and document pipelines on Azure that only report
what they can point to. Everything ships with tests, CI and evaluation, the way a team would
build it.

## Featured: Azure AI engineering

<table>
<tr>
<td width="50%" valign="top">

### [Revisa](https://github.com/xDarkzx/Revisa)
**Document AI on Azure.** Reads construction-drawing title blocks into a drawing register.

- Azure Document Intelligence OCR, then a gpt-4.1-mini reader that may only cite text the OCR found
- Review routing with reasons, and a register in Cosmos DB
- Measured on 200 labelled drawings, reported on a held-out half
- Deployed with Bicep and managed identity, run once, then torn down, with the [evidence committed](https://github.com/xDarkzx/Revisa/tree/main/docs/azure-proof)

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![OpenAI](https://img.shields.io/badge/Azure%20OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Cosmos DB](https://img.shields.io/badge/Cosmos%20DB-0078D4?style=flat-square)
![Bicep](https://img.shields.io/badge/Bicep-0078D4?style=flat-square)

</td>
<td width="50%" valign="top">

### [Escalon](https://github.com/xDarkzx/Escalon)
**Grounded IT-support agent.** Built on Microsoft Agent Framework.

- Hybrid search over Microsoft support docs
- MCP tools exposed to Copilot Studio
- Entra ID authentication and ticketing integration
- Evaluation suite for answer quality

![Agent Framework](https://img.shields.io/badge/Agent%20Framework-5C2D91?style=flat-square)
![Copilot Studio](https://img.shields.io/badge/Copilot%20Studio-0078D4?style=flat-square)
![Entra ID](https://img.shields.io/badge/Entra%20ID-0078D4?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-111827?style=flat-square)

</td>
</tr>
</table>

## Featured: robotics and AI vision

### [Companion](https://github.com/xDarkzx/Companion)
**A ROS 2 robot brain that finds what you ask for.** Ask "where is the mug?" and it answers in metres.

- Open-vocabulary detection (OWLv2, Grounding DINO) plus depth, placing objects in 3D for a voice agent on ROS 2 Jazzy with Nav2
- Measured on public data: 43.6 AP on COCO, and a 5.4 cm median 3D error on NYU Depth V2 with a depth camera
- Typed topic and service contracts checked in CI, launch tests of the full voice-to-answer path, and a one-command Docker gate

![ROS 2](https://img.shields.io/badge/ROS%202-Jazzy-22314E?style=flat-square&logo=ros)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-0b1020?style=flat-square)
![Nav2](https://img.shields.io/badge/Nav2-1d76db?style=flat-square)

## MCP servers used in the wild

| Project | Stars | What it does |
|---|---|---|
| **[Audacity-MCP](https://github.com/xDarkzx/Audacity-MCP)** | ![stars](https://img.shields.io/github/stars/xDarkzx/Audacity-MCP?style=flat-square&label=%E2%98%85&color=f59e0b) | 144 tools and 9 end-to-end pipelines for AI-driven audio editing: cleanup, effects, mastering, transcription, podcasts. |
| **[Reaper-MCP](https://github.com/xDarkzx/Reaper-MCP)** | ![stars](https://img.shields.io/github/stars/xDarkzx/Reaper-MCP?style=flat-square&label=%E2%98%85&color=f59e0b) | 181 tools for music production in REAPER: composition, mixing, mastering, batch editing and ReaScript automation. |
| **[OBS-MCP](https://github.com/xDarkzx/OBS_MCP)** | ![stars](https://img.shields.io/github/stars/xDarkzx/OBS_MCP?style=flat-square&label=%E2%98%85&color=f59e0b) | 148 tools over obs-websocket: scenes, audio, filters, streaming, recording and stream-health diagnostics. |
| **[FMOD Studio MCP](https://github.com/xDarkzx/Dans_Fmod_Studio_MCP)** | ![stars](https://img.shields.io/github/stars/xDarkzx/Dans_Fmod_Studio_MCP?style=flat-square&label=%E2%98%85&color=f59e0b) | Game-audio authoring through FMOD's scripting terminal: events, parameters, mixer, banks, interactive music. |
| **[SongForge-MCP](https://github.com/xDarkzx/SongForge-MCP)** | ![stars](https://img.shields.io/github/stars/xDarkzx/SongForge-MCP?style=flat-square&label=%E2%98%85&color=f59e0b) | Local AI music generation (ACE-Step) with stem splitting and reference-style matching, driven from Claude Desktop. |

### See it in action

| Audacity-MCP | Reaper-MCP |
|:---:|:---:|
| [![Audacity-MCP demo](https://img.youtube.com/vi/xiMh3d97QtQ/hqdefault.jpg)](https://youtu.be/xiMh3d97QtQ) | [![Reaper-MCP demo](https://img.youtube.com/vi/F0i5njHaMXQ/hqdefault.jpg)](https://youtu.be/F0i5njHaMXQ) |

## Tech stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure">
  <img src="https://img.shields.io/badge/Azure%20OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="Azure OpenAI">
  <img src="https://img.shields.io/badge/MCP-111827?style=for-the-badge" alt="Model Context Protocol">
  <img src="https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS 2">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama">
</p>

## How I build

- **Grounded, not guessed.** Model output has to point at its evidence; MCP tools are checked against each application's real protocol and source.
- **Measured.** Labelled evaluation sets, held-out results, and numbers reported as they are.
- **Production hygiene.** Protected branches, pull requests, CI with lint, types, tests and security scanning, changelogs and ADRs.
- **Maintained in public.** Issues triaged, outside pull requests reviewed and merged, releases documented.

## Also built

- **[GigChain-Keys](https://github.com/xDarkzx/GigChain-Keys)**: a C++ live-performance rig for keyboard players, with VST3 hosting, setlists, chord charts and a stage-ready Perform mode.
- **[The Last Bastion](https://github.com/xDarkzx/TheLastBastion)**: trust infrastructure for autonomous AI agents, with Ed25519 challenge-response identity, signed agent passports and tamper-evident audit trails.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/xDarkzx/xDarkzx/output/github-contribution-grid-snake-dark.svg">
    <img alt="Contribution graph animation" src="https://raw.githubusercontent.com/xDarkzx/xDarkzx/output/github-contribution-grid-snake.svg">
  </picture>
</p>

<p align="center"><b>Hiring for AI engineering in New Zealand or remote?</b> <a href="mailto:dkstudiosnz@gmail.com">Get in touch</a>. I also take contract work building MCP servers and AI integrations.</p>
