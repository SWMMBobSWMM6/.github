# SWMMBobSWMM6

Hydrology, hydraulics, and water-quality modeling built around **EPA SWMM5** — model libraries, open-source simulation engines, interactive teaching tools, and research code. Maintained by **Robert (Bob) Dickinson** ([swmm5.org](https://swmm5.org/)), with 50+ years in stormwater and hydraulic modeling.

The repositories here fall into four groups: a large library of ready-to-run SWMM5 models, forks of the open-source SWMM / OpenSWMM engines and their coupling frameworks, browser-based educational tools, and geostatistics / research code.

---

## 📚 Model libraries & interactive tools

### [1729-SWMM5-Models-2030](https://github.com/SWMMBobSWMM6/1729-SWMM5-Models-2030) · `Batchfile`
A reference library of **~3,800 EPA SWMM5 (`.inp`) models** spanning hydrology, hydraulics, LID, water quality, force mains, pumps, weirs, orifices, and dynamic-wave routing — plus XPSWMM conversions and full training sets (EPA, OWA, NCIMM, and more). Every model ships with an **auto-generated Markdown summary** beside it: badges for flow units / routing / infiltration / element counts, a configuration table, an element inventory, and the run status pulled from its `.rpt`. Binary `.out` results stay on disk but are git-ignored to keep the repo small.

### [swmm5-runoff-explorer](https://github.com/SWMMBobSWMM6/swmm5-runoff-explorer) · `HTML`
A single-file, browser-based tool for exploring SWMM5 **runoff** behavior — how subcatchment width, slope, imperviousness, and infiltration shape the runoff hydrograph. One of the interactive "vibe-coded" teaching apps from the SWMM5.org series; open it in any browser, no install required.

### [BobSWMM-Auto-Research](https://github.com/SWMMBobSWMM6/BobSWMM-Auto-Research) · `TypeScript`
An AI-assisted automated-research app (developed on [Replit](https://replit.com/@robertdickinson/BobSWMM-Auto-Research)) for gathering and summarizing SWMM and water-engineering references and analysis.

---

## ⚙️ SWMM / OpenSWMM engines & model coupling

Forks of the open-source **HydroCouple** modeling ecosystem and related transient / 3-D engines, kept here for reference and development.

### [openswmm.engine](https://github.com/SWMMBobSWMM6/openswmm.engine) · `C` · MIT
The SWMM computational engine packaged as a **HydroCouple component** — dynamic hydrology, hydraulics, and water-quality simulation for stormwater, wastewater, and combined-sewer collection systems.
↳ Fork of [HydroCouple/openswmm.engine](https://github.com/HydroCouple/openswmm.engine)

### [openswmm.gymnasium](https://github.com/SWMMBobSWMM6/openswmm.gymnasium) · `Python` · MIT
A **reinforcement-learning** environment (Gymnasium / OpenAI-Gym style) wrapped around the SWMM engine — for training agents to perform real-time control (RTC) of stormwater and sewer systems.
↳ Fork of [HydroCouple/openswmm.gymnasium](https://github.com/HydroCouple/openswmm.gymnasium)

### [HydroCouple](https://github.com/SWMMBobSWMM6/HydroCouple) · `C++` · MIT
Interface specifications for **HydroCouple**, a component-based framework for coupling environmental and hydrologic models — the standard that the OpenSWMM engine plugs into.
↳ Fork of [HydroCouple/HydroCouple](https://github.com/HydroCouple/HydroCouple)

### [ITM_SWMM](https://github.com/SWMMBobSWMM6/ITM_SWMM) · `Pascal` · MIT
The **Illinois Transient Model** integrated with SWMM — simulates mixed flow (free-surface *and* pressurized / surcharged transient flow) in storm and sewer networks, capturing rapid filling and geysering that the standard dynamic-wave solver doesn't.
↳ Fork of [artuleon/ITM_SWMM](https://github.com/artuleon/ITM_SWMM) (Arturo León)

### [EFDCPlus8.5](https://github.com/SWMMBobSWMM6/EFDCPlus8.5) · `Fortran`
**EFDC+** (Environmental Fluid Dynamics Code Plus), v8.5 — a 3-D hydrodynamic, sediment-transport, and water-quality model for rivers, lakes, reservoirs, estuaries, and coastal waters.
↳ Fork of [HydroCouple/EFDCPlus8.5](https://github.com/HydroCouple/EFDCPlus8.5)

---

## 🔬 Research & geostatistics

### [pybme](https://github.com/SWMMBobSWMM6/pybme) · `Python`
A Python port of **BMElib** — Bayesian Maximum Entropy (Serre & Christakos) for spatiotemporal geostatistical estimation, useful for interpolating rainfall and water-quality fields.
↳ Fork of [wiesnerfriedman/pybme](https://github.com/wiesnerfriedman/pybme)

### [Hackathon_KM](https://github.com/SWMMBobSWMM6/Hackathon_KM) · `Ruby` · MIT
Ruby code ("KM") from the NG hackathon — scripting and automation for water-modeling workflows.

---

<sub>Maintained by Robert (Bob) Dickinson · <a href="https://swmm5.org/">swmm5.org</a></sub>
