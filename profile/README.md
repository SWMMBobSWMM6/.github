# SWMM6 Enablement

Where EPA SWMM goes next. This organization is the research frontier: transient flow, reinforcement learning, model coupling, and the large model corpora needed to test all three.

## The model corpus

**[1729-SWMM5-Models-2030](https://github.com/SWMMBobSWMM6/1729-SWMM5-Models-2030)** is a library of 3,800+ EPA SWMM5 `.inp` models, each with an auto-generated Markdown summary. It spans hydrology, hydraulics, LID, force mains, pumps, weirs, orifices, and dynamic-wave routing, plus XPSWMM conversions and training examples. When you need to prove an engine change holds across thousands of real networks, this is the test set.

## Next-generation engines

**[ITM_SWMM](https://github.com/SWMMBobSWMM6/ITM_SWMM)** couples Arturo Leon's Illinois Transient Model with SWMM, for the mixed free-surface and pressurized flow that the standard Preissmann slot only approximates.

**[openswmm.engine](https://github.com/SWMMBobSWMM6/openswmm.engine)** and **[HydroCouple](https://github.com/SWMMBobSWMM6/HydroCouple)** carry the C engine and the interface specifications for coupling SWMM to other models.

## Machine learning on the engine

**[openswmm.gymnasium](https://github.com/SWMMBobSWMM6/openswmm.gymnasium)** wraps the SWMM engine as a reinforcement-learning environment. Train a control policy for real-time gate and pump operation against the model instead of hand-tuning rules.

**[pybme](https://github.com/SWMMBobSWMM6/pybme)** brings Bayesian Maximum Entropy (Serre and Christakos) to Python, for spatial estimation of rainfall and other fields that feed the model.

## Browser tools

**[swmm5-runoff-explorer](https://github.com/SWMMBobSWMM6/swmm5-runoff-explorer)** rebuilds SWMM5 subcatchment runoff in the browser so you can watch the nonlinear reservoir respond to each parameter.

## The other accounts

- **[dickinsonre](https://github.com/dickinsonre)** is the main personal account.
- **[SWMMEnablement](https://github.com/SWMMEnablement)** enhances current SWMM with apps and preserves historical engine code.
- **[Robert-Dickinson-NS-Apps](https://github.com/Robert-Dickinson-NS-Apps)** holds the single-file teaching apps.
- **[CIMM-ORG](https://github.com/CIMM-ORG)** is the nonprofit behind the SWMM5plus Fortran engine.

## About

Maintained by Robert (Bob) Dickinson, Autodesk Water Technologist and co-developer of EPA SWMM versions 3, 4, 5, and 5+. Fifty-plus years of continuous SWMM work, from punch cards at the University of Florida in 1974 to reinforcement learning on the engine today. Chair of the SWMM5+ Technical Advisory Committee at [CIMM.org](http://www.cimm.org) and member of the EWRI Stormwater Modeling Committee.

**Contact:** robert.dickinson@gmail.com · X [@RDickinson](https://twitter.com/RDickinson)

---

*Experimental work. Verify all results against the production engine before using them for design.*
