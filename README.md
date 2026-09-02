

# wlccc13452-bit

**Earthquake Research · Structural Design · Architecture · BIM · Quant · LLM**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-4FC08D?logo=vuedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?logo=threedotjs&logoColor=white)
![IFC/BIM](https://img.shields.io/badge/IFC%2FBIM-0055A4)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)



---



## About

A cross-disciplinary engineer working at the intersection of structural engineering, computational design, and applied AI, focused on:

- **Earthquake Research** — seismic analysis and structural response.
- **Structural Design & Architecture** — analysis-driven design workflows.
- **BIM & Computational Design** — a Rhino/Grasshopper → ETABS → Revit structural pipeline built on IFC/FEM for parametric modeling and structural analysis.
- **Quantitative Trading** — AI-agent-driven A-share quant research, strategy development, and trading practice.
- **LLM** — training and fine-tuning GPT-class models, exploring their application in engineering and finance.

---



## Featured Projects



### [vinchi-hub](https://github.com/wlccc13452-bit/vinchi-hub)

A unified BIM integration platform bridging Rhino/Grasshopper, ETABS, and Revit through an intermediate format and orchestration layer, delivering a complete structural design workflow: parametric geometry generation → structural analysis → AI-assisted correction → BIM delivery.

Cross-stack handoff uses versioned floor snapshots (`sph.v2`) between Morph and Flow; production BIM delivery builds IFC/GLB/GLTF and Revit models from the planar geometry authority payload (not live ETABS edits). Optional AI Chat bridge coordinates Flow and Morph agents over HTTP.


| Subproject      | Role                                                                    |
| --------------- | ----------------------------------------------------------------------- |
| `aether_switch` | Rhino/Grasshopper geometry generation and ETABS bridge                  |
| `vinchi-flow`   | Visual node-based workflow orchestration and ETABS analysis (MCP tools) |
| `vinchi-morph`  | ReAct-based structural correction and model checking                    |
| `sync-hub`      | Multi-device coordination and message relay center                      |




### [ifc_projects](https://github.com/wlccc13452-bit/ifc_projects)

IFC/BIM engineering practice hub for structural analysis, design visualization, and computational geometry — Blender/Sverchok integration, desktop post-processing, and parametric engineering apps, plus **adapy (ADA - Assembly for Design & Analysis)** for FE model I/O, STEP/IFC CAD/BIM formats, and CSG boolean operations.

#### [building-x](https://github.com/wlccc13452-bit/building-x) (EPAD)

Structural engineering desktop application for ETABS/YJK/PKPM post-processing:

- FEM visualization and IFC/GLTF export with embedded IFClite VIEW
- Report Orchestrator — Compose Markdown → interactive Report HTML, browser export, DOC/PDF
- Sibling tools: VS Code/Cursor report preview extension, standalone report-viewer app, XTRACT section FEM batch automation



#### [vizion_ai](https://github.com/wlccc13452-bit/vizion-ai)

Independent pure-Python engineering app platform aiming for feature parity with leading parametrization platforms (Build / Run workflows):

- Native SDK (`import vizion`) — Parametrization, Controller, Fields, Views, Results
- Platform stack — FastAPI sessions/jobs/artifacts, React editor UI, Docker/Compose/K8s deploy
- Developer CLI (`vizion-cli`) — create-app, start, smoke, publish; Connect workers for external tools (e.g. ETABS)



#### [sverchok](https://github.com/wlccc13452-bit/sverchok)

Blender node-based parametric geometry toolkit (fork with engineering extensions):

- 600+ nodes for meshes, curves, surfaces, fields, solids, and geometric analysis
- Optional IfcSverchok extension for IFC exchange in node trees
- EPAD bridge nodes (e.g. column viewer from analysis Excel) for structural visualization in Blender



### [geopile_agent](https://github.com/wlccc13452-bit/geopile_agent)

Geotechnical and pile foundation engineering toolkit with interactive UIs (Streamlit / Dash / Gradio):

- IFC parsing, mesh/property extraction, and Speckle cloud model upload/viewing
- Borehole & pile Excel I/O, 2D/3D Plotly visualization, and IFC export of processed results
- Multi-IFC merge with transforms for combined geotechnical–structural model delivery



### [ai-stock-quant](https://github.com/wlccc13452-bit/ai-stock-quant)

An AI-agent-driven A-share quantitative trading workspace:

- `stock-peg` — intelligent stock analysis platform (FastAPI + React + Feishu bot)
- `trading-practices` — trading automation (Wenhua/TongdaXin)
- `miniqumt-server` — full-stack MiniQMT simulated trading environment
- `knowledge-brain` — market research and AI learning knowledge base



### [LLM_Projects](https://github.com/wlccc13452-bit/LLM_Projects)

LLM learning and experimentation, including nanoGPT — a minimal implementation for training and fine-tuning medium-sized GPT models, used to understand and reproduce GPT-class models.

---



## GitHub Stats



![GitHub stats](https://github-readme-stats.vercel.app/api?username=wlccc13452-bit&show_icons=true&theme=default)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=wlccc13452-bit&layout=compact)



---



## Contact

- GitHub: [@wlccc13452-bit](https://github.com/wlccc13452-bit)

