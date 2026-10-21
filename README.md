# Awesome-Electronic-Design-Automation-EDA

## Top Electronic Design Automation (EDA) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on PCB Design, Circuit Simulation & Open-Silicon Flows*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Electronic Design Automation (EDA)**. These tools enable engineers and hobbyists to design schematics, lay out printed circuit boards (PCBs), simulate circuit behavior, and increasingly, participate in open-silicon workflows from RTL to GDSII.



**Examples** include Altium Designer, Autodesk Eagle, Cadence Allegro, Mentor PADS, KiCad, OrCAD, Zuken CR-8000, EasyEDA, Proteus Design Suite, and Pulsonix (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom scripting, and transparent hardware design—ideal for hardware startups, students, and researchers building open, reproducible electronics. The open-source EDA landscape spans full PCB suites (KiCad, LibrePCB), SPICE simulators (ngspice, Xyce), and the rapidly maturing open-silicon toolchain (OpenROAD, Yosys, KLayout).



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Altium Designer](https://www.altium.com/)**  

  Industry-standard commercial PCB design suite with unified schematic, layout, and 3D viewing. Known for its active routing engine and extensive component library ecosystem. Pricing is subscription-based and enterprise-tier.



- **[Autodesk Eagle](https://www.autodesk.com/products/eagle/)**  

  Commercial PCB design software popular among hobbyists and small teams, tightly integrated with Autodesk's Fusion 360 for mechanical co-design. Subscription-based with limited free tier for personal use.



- **[Cadence Allegro](https://www.cadence.com/en_US/home/tools/pcb-design-and-analysis/allegro.html)**  

  Enterprise-grade PCB design platform for complex, high-speed, and high-density boards. The standard in many large electronics organizations, with advanced constraint management and signal integrity tools.



- **[Mentor PADS (Siemens)](https://eda.sw.siemens.com/en-US/pcb/pads/)**  

  Siemens' PCB design suite aimed at small-to-medium businesses. Offers a balance of usability and advanced features, with tiers from standard to professional.



- **[OrCAD (Cadence)](https://www.orcad.com/)**  

  Long-standing commercial EDA suite for schematic capture and PCB design. The X and Standard tiers are widely used in education and small business, with tight integration into Cadence's broader ecosystem.



- **[Zuken CR-8000](https://www.zuken.com/en/product/cr-8000/)**  

  Enterprise PCB design platform with strong multi-board and system-level design capabilities. Popular in Japan and among companies with complex product structures.



- **[EasyEDA (Pro)](https://easyeda.com/)**  

  Browser-based EDA tool from JLCPCB/LCSC with tight integration into their fabrication and parts catalog. The free tier is popular for hobbyist projects; Pro adds advanced features.



- **[Proteus Design Suite](https://www.labcenter.com/)**  

  Commercial EDA tool combining schematic capture, PCB layout, and microcontroller simulation. Widely used in education for its integrated simulation capabilities.



- **[Pulsonix](https://www.pulsonix.com/)**  

  Commercial PCB design software from the UK, offering a mid-range alternative to enterprise suites with strong usability and a loyal user base.



## Open-Source GitHub Projects



- **[KiCad](https://github.com/KiCad/kicad-source-mirror)**  

  The world's leading open-source EDA suite. Version 10 (March 2026) added design variants, a graphical DRC rule editor, importers for Allegro/PADS/gEDA, dark mode on Windows, lasso selection, and step-only 3D libraries. 7,609 commits and 952 new symbols in the v10 cycle alone . GPLv3. Cross-platform (Windows/macOS/Linux) with Python scripting.



- **[LibrePCB](https://github.com/LibrePCB/LibrePCB)**  

  A modern, intuitive EDA suite focused on a clean user experience and strict design-rule enforcement. Version 2.1.1 (June 2026). Centralized library manager and open file formats. GPLv3. Best for beginners and small projects that want structure without KiCad's complexity .



- **[ngspice](https://github.com/ngspice/ngspice)**  

  The open-source SPICE standard for circuit simulation. Supports transient, AC, DC, noise, and Monte Carlo analysis. BSD licensed. The de facto simulator for open-source electronics work, with `.cir` netlist compatibility from commercial tools like OrCAD PSpice .



- **[Xyce (Sandia National Labs)](https://github.com/Xyce/Xyce)**  

  High-performance parallel SPICE simulator designed for large mixed-signal circuits. GPL-3.0. Scales across HPC clusters, making it suitable for simulation-heavy research and large-scale circuit analysis .



- **[OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD)**  

  End-to-end RTL-to-GDSII flow for open-silicon design. Integrates synthesis, placement, routing, and sign-off. A cornerstone of the open-silicon movement, enabling fully open ASIC flows without proprietary lock-in .



- **[Yosys](https://github.com/YosysHQ/yosys)**  

  Open synthesis suite for Verilog. The synthesis backbone of the open-silicon toolchain, used in conjunction with OpenROAD, nextpnr, and other flow components. ISC licensed.



- **[KLayout](https://github.com/KLayout/klayout)**  

  High-performance layout viewer and DRC/LVS engine. Essential for IC and PCB mask work, with scripting support and a large community in the open-silicon ecosystem .



- **[Horizon EDA](https://github.com/horizon-eda/horizon)**  

  Open-source PCB layout tool with real-time DRC, constraint-driven routing, and a pooled library system. GPL-3.0. A modern alternative to KiCad for users who want tighter constraint enforcement .



- **[FreeRouting](https://github.com/freerouting/freerouting)**  

  Java-based autorouter that plugs into KiCad and accepts DSN netlists. GPL-3.0. Useful for quickly routing boards where manual routing would be tedious, with interactive feedback .



- **[openEMS](https://github.com/thliebig/openEMS)**  

  Open-source 3D electromagnetic field simulator using FDTD. GPL-3.0. A free alternative to HFSS/CST for signal integrity and EMC analysis, particularly for antenna and high-frequency designs .



- **[PySpice](https://github.com/PySpice-org/PySpice)**  

  Python API for ngspice and Xyce. Enables scriptable parametric sweeps and design-space exploration for circuit simulation. GPL-3.0. Bridges the gap between Python data workflows and SPICE simulation .



- **[Qucs-S](https://github.com/ra3xdh/qucs_s)**  

  Qt GUI for ngspice/Xyce with RF S-parameter and harmonic balance support. GPL-2.0. Best for RF circuit designers who want a GUI over the ngspice engine .



### Additional Strong Open-Source Options



- **cocotb** — Coroutine-based Python testbench framework for verifying digital logic. A key verification tool in the open-silicon flow .

- **Verilator** — Fastest open-source Verilog simulator, widely used for linting and simulation in open-hardware projects .

- **Icarus Verilog** — Event-driven Verilog simulator, a standard companion to Yosys and Verilator for digital design .

- **IIC-OSIC-TOOLS** — Docker image bundling 90+ open analog and digital IC tools into a single container, dramatically lowering the setup barrier for open-silicon work .

- **Frameworks for building custom systems**: Combine **KiCad** for board design with **ngspice** or **PySpice** for simulation, and **FreeRouting** for autorouting. For IC design, chain **Yosys → OpenROAD → KLayout** with **cocotb** for verification. Use **LibrePCB** for smaller projects where KiCad's flexibility is unnecessary overhead.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Open-source EDA tools vary significantly in maturity; verify fabrication outputs against foundry or fab-house requirements before ordering boards.

- The open-silicon flow (OpenROAD, Yosys) is production-capable for many nodes but may lack support for the most advanced process nodes where commercial tools remain mandatory .



---



**Made for hardware engineers, PCB designers, students, and open-silicon advocates.**  

Let's make electronics design more open, accessible, and reproducible.
