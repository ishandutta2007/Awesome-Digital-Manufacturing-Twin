# Awesome-Digital-Manufacturing-Twin

# Top Digital Manufacturing Twin Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Factory Digital Twins, Production Simulation, Industrial IoT Twins, Shop-Floor Virtualization & Closed-Loop Manufacturing*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Manufacturing Twins**. These systems mirror production lines, equipment, and processes—combining 3D/physics models, IoT data, and simulation—so manufacturers can optimize throughput, quality, and maintenance.

**Examples** include Dassault 3DEXPERIENCE, Siemens Xcelerator, PTC ThingWorx, Ansys Twin Builder, Bentley iTwin, Azure Digital Twins, Altair Twin Activate, AVEVA CONNECT, C3 AI Digital Twin, and Unity Industry (the category leaders).

**Open-source emphasis**: Manufacturing twins build on **Eclipse Ditto**, **Asset Administration Shell (BaSyx)**, **Open Factory Twin**, **ROS 2**, and industrial simulation stacks. This section is heavily expanded with every major relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Dassault 3DEXPERIENCE, Siemens Xcelerator, PTC ThingWorx](https://www.3ds.com/)**  
  Leading industrial platforms spanning design, manufacturing execution context, and live digital twins of products and plants.

- **[Ansys Twin Builder, Altair Twin Activate, Unity Industry](https://www.ansys.com/)**  
  Simulation-centric twin tools for multi-physics models and real-time visualization of manufacturing systems.

- **[Azure Digital Twins, AVEVA CONNECT, C3 AI, Bentley iTwin](https://azure.microsoft.com/en-us/products/digital-twins)**  
  Cloud and industrial data platforms for asset graphs, historians, and AI-driven operational twins.

- **[Other commercial manufacturing twin platforms](https://www.siemens.com/xcelerator)**  
  Additional MES-adjacent and factory-virtualization solutions.

## Open-Source GitHub Projects

- **[Eclipse Ditto](https://github.com/eclipse-ditto/ditto)**  
  Open digital twin framework for industrial IoT—API-centric twins of machines and lines with broad Eclipse IoT adoption.

- **[Eclipse BaSyx (Asset Administration Shell)](https://github.com/eclipse-basyx)**  
  Open Industry 4.0 AAS implementation—standardized digital representations of manufacturing assets and components.

- **[Open Factory Twin (OFacT)](https://openfactorytwin.github.io/ofact/)**  
  Open digital twin framework for production and logistics—state models, planning, and closed-loop work instructions.

- **[ROS 2 / industrial robotics stacks](https://github.com/ros2)**  
  Open robotics middleware frequently used as the live control and twin layer for flexible manufacturing cells.

- **[FIWARE Industrial Data Space patterns](https://github.com/FIWARE)**  
  Open context-broker approaches adapted for factory data fabrics and multi-source twins.

- **[Apache StreamPipes / industrial analytics](https://github.com/apache/streampipes)**  
  Open self-service industrial IoT toolbox for stream processing and operational dashboards feeding twins.

- **[OpenPLC / OPC-UA open stacks](https://github.com/openplcproject)**  
  Open automation and OPC-UA tooling used to connect physical lines to digital twin backends.

- **[Simulation & discrete-event open tools](https://github.com/search?q=manufacturing+simulation+OR+discrete+event+factory+open+source)**  
  Community DES and factory simulation projects for offline manufacturing twin experiments.

### Additional Strong Open-Source Options

- **Twin API layer**: Eclipse Ditto for machine/line shadows.
- **Industrie 4.0 standard**: BaSyx AAS for interoperable asset twins.
- **Production logistics**: Open Factory Twin for material-flow oriented twins.
- **Composable stacks**: PLC/OPC-UA → Ditto/BaSyx → time-series DB → Grafana + optional physics sim.
- Commercial platforms still lead in CAD/PLM integration, multi-physics fidelity, and enterprise MES coupling.

**Frameworks for building custom systems**:  
**Eclipse Ditto** + **BaSyx AAS** for the twin application layer; **ROS 2** / **Open Factory Twin** for cells and logistics; open OPC-UA for connectivity.  
Commercial platforms (Siemens, Dassault, PTC, Ansys, Azure Digital Twins, etc.) deliver integrated design-to-operations twins.  
Advanced manufacturers often prototype on open IoT twin stacks and run production twins on commercial suites. Fully open manufacturing twins are viable for monitoring and research; high-fidelity closed-loop optimization usually mixes both.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Manufacturing twins that influence live equipment require strict OT cybersecurity, change control, and safety validation. Incorrect models or commands can damage assets or endanger people. Follow industrial safety standards and segregate advisory vs. closed-loop control.
- Open-source frameworks offer standards alignment and data ownership but demand integration expertise. Commercial platforms shift product depth and support to the vendor. Prefer open models (AAS, DTDL, OPC-UA) to reduce lock-in.

---

**Made for manufacturing IT/OT teams, industrial engineers, and factory digitalization leaders.**  
Let's expand open industrial twin frameworks while recognizing the simulation and PLM depth that leading commercial manufacturing twin platforms deliver.
