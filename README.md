<div align="center">

# wlccc13452-bit

**Earthquake Research · Structural Design · Architecture · BIM · Quant · LLM**

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-4FC08D?logo=vuedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?logo=threedotjs&logoColor=white)
![IFC/BIM](https://img.shields.io/badge/IFC%2FBIM-0055A4)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)

<br/>

[Featured Projects](#featured-projects) · [GitHub Stats](#github-stats) · [Contact](#contact)

</div>

---

## About

Cross-disciplinary engineer at the intersection of structural engineering, computational design, and applied AI:

| Focus | Scope |
| --- | --- |
| **Earthquake Research** | Seismic analysis and structural response |
| **Structural Design & Architecture** | Analysis-driven design workflows |
| **BIM & Computational Design** | Rhino/Grasshopper → ETABS → Revit pipeline on IFC/FEM |
| **Quantitative Trading** | AI-agent A-share research, strategy, and trading practice |
| **LLM** | GPT-class training/fine-tuning for engineering and finance |

---

## Featured Projects

### Structural · BIM · Engineering

#### [vinchi-hub](https://github.com/wlccc13452-bit/vinchi-hub)

Unified BIM integration platform bridging Rhino/Grasshopper, ETABS, and Revit through an intermediate format and orchestration layer — parametric geometry → structural analysis → AI-assisted correction → BIM delivery.

Cross-stack handoff uses versioned floor snapshots (`sph.v2`) between Morph and Flow; production delivery builds IFC/GLB/GLTF and Revit models from the planar geometry authority payload. Optional AI Chat bridge coordinates Flow and Morph agents over HTTP.

| Subproject | Role |
| --- | --- |
| `aether_switch` | Rhino/Grasshopper geometry generation and ETABS bridge |
| `vinchi-flow` | Visual node-based workflow orchestration and ETABS analysis (MCP tools) |
| `vinchi-morph` | ReAct-based structural correction and model checking |
| `sync-hub` | Multi-device coordination and message relay center |

#### [CsiDigitalTwin](https://github.com/wlccc13452-bit/CsiDigitalTwin)

AutoCAD plugin that keeps CAD drawings in sync with CSI analysis models (ETABS / SAP2000) — a CAD↔analysis digital twin for structural geometry.

- Bidirectional commands: `PullEtabs` / `PushEtabs`, `PullSap` / `PushSap`
- Chunked geometry push/pull with progress feedback and model scale configuration
- Targets AutoCAD 2021+ (.NET 4.8) with ETABS 19–21 and SAP2000 24

#### [SSW](https://github.com/wlccc13452-bit/SSW)

**SpearFish Structure Widget** — AutoCAD LISP/VLX toolkit for reinforced-concrete structural detailing and drawing production (historically branded SSW / SpearFish).

- Column and beam rebar detailing workflows driven by analysis output (SATWE / YJK / JCCAD)
- Drawing aids for layers, styles, axes, walls, foundations, and batch plotting
- Bridges to CSI SAFE floor analysis, ETABS post-processing, and XTRACT section tools
- Config-driven setup (`INIT` / `INIT_CONFIG.ini`) for firm standards and layer schemes

#### [ifc_projects](https://github.com/wlccc13452-bit/ifc_projects)

IFC/BIM engineering hub for structural analysis, design visualization, and computational geometry — Blender/Sverchok, desktop post-processing, parametric apps, plus **adapy (ADA)** for FE model I/O, STEP/IFC, and CSG.

<details>
<summary><strong>Subprojects</strong></summary>

<br/>

##### [building-x](https://github.com/wlccc13452-bit/building-x) (EPAD)

Structural engineering desktop app for ETABS/YJK/PKPM post-processing:

- FEM visualization and IFC/GLTF export with embedded IFClite VIEW
- Report Orchestrator — Compose Markdown → interactive Report HTML, browser / DOC / PDF export
- Sibling tools: editor report-preview extension, standalone report-viewer, XTRACT section FEM automation

##### [vizion_ai](https://github.com/wlccc13452-bit/vizion-ai)

Independent pure-Python engineering app platform (Build / Run workflows):

- Native SDK (`import vizion`) — Parametrization, Controller, Fields, Views, Results
- Platform stack — FastAPI sessions/jobs/artifacts, React editor UI, Docker/Compose/K8s
- Developer CLI (`vizion-cli`) — create-app, start, smoke, publish; Connect workers (e.g. ETABS)

##### [sverchok](https://github.com/wlccc13452-bit/sverchok)

Blender node-based parametric geometry toolkit (fork with engineering extensions):

- 600+ nodes for meshes, curves, surfaces, fields, solids, and geometric analysis
- Optional IfcSverchok extension for IFC exchange in node trees
- EPAD bridge nodes (e.g. column viewer from analysis Excel) for structural visualization in Blender

</details>

#### [geopile_agent](https://github.com/wlccc13452-bit/geopile_agent)

Geotechnical and pile foundation toolkit with Streamlit / Dash / Gradio UIs:

- IFC parsing, mesh/property extraction, Speckle cloud upload/viewing
- Borehole & pile Excel I/O, 2D/3D Plotly visualization, IFC export
- Multi-IFC merge with transforms for combined geotechnical–structural delivery

---

### Quantitative Trading

#### [ai-stock-quant](https://github.com/wlccc13452-bit/ai-stock-quant)

AI-agent-driven A-share quantitative trading workspace spanning research, data services, automation, and knowledge tooling.

| Component | Role |
| --- | --- |
| [`stock-peg`](https://github.com/wlccc13452-bit/stock-peg) | Intelligent stock analysis platform |
| [`akshare_service`](https://github.com/wlccc13452-bit/miniqumt-server/tree/main/akshare_service) | MiniQMT market-data service (AkShare → SQLite) |
| `trading-practices` | Trading automation (Wenhua / TongdaXin) |
| `miniqumt-server` | Full-stack MiniQMT simulated trading environment |
| `knowledge-brain` | Market research and AI learning knowledge base |

##### [stock-peg](https://github.com/wlccc13452-bit/stock-peg)

Data-driven portfolio analysis platform (FastAPI + React + Feishu PegBot):

- Holdings managed via Markdown + local DB cache; quote service with async refresh and fallback
- Fundamentals, market outlook, sector rotation, and international linkage analysis
- Feishu PegBot — card interactions, event push, session registry, scheduled price alerts

##### [akshare_service](https://github.com/wlccc13452-bit/miniqumt-server/tree/main/akshare_service)

Three-node MiniQMT data system: **Data Server** (authority) + **Data Frontend** (Vue admin) + **Data Client Test**:

- FastAPI + SQLite ingest from AkShare (prices, financials, A-share / US indices)
- Async task queue, APScheduler jobs, WebSocket live updates
- Watchlist load from Markdown/JSON; integrity stats and industry classification APIs

---

### LLM

#### [LLM_Projects](https://github.com/wlccc13452-bit/LLM_Projects)

LLM learning and experimentation, including **nanoGPT** — a minimal implementation for training and fine-tuning medium-sized GPT models.

---

## GitHub Stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=wlccc13452-bit&show_icons=true&theme=default&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=wlccc13452-bit&layout=compact&hide_border=true)

</div>

---

## Contact

- GitHub: [@wlccc13452-bit](https://github.com/wlccc13452-bit)
