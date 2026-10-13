# Cognitive-Load-Aware Phishing Defense Simulation

An exploratory computational research project combining **agent-based modeling (ABM)** and **evolutionary game theory (EGT)** to study phishing attacks and defenses under cognitive load.

## Research question
Can defensive strategies informed by an imperfect estimate of users' cognitive overload reduce phishing risk more effectively than static interventions, once deployment costs and behavioral adaptation are considered?

## Approach
The simulation investigates phishing campaigns under baseline conditions and combinations of alert flooding, time pressure, and authority cues. It compares candidate defensive policies including training, static warnings, rapid SOC response, adaptive warnings, filtering, and combined or targeted adaptive interventions.

A simulated overload detector is inspired by passive-BCI principles. Detector balanced accuracy is varied in sensitivity experiments; this is **not a deployed EEG-based phishing detector**. EGT provides a complementary framework for examining strategic adaptation.

## Outcomes and analysis
The investigation tracks simulated clicking, reporting, compromise and containment, breach risk, expected loss, and cost-adjusted net loss. It includes robustness and ablation analyses.

In the studied cost assumptions, static warnings often achieved the lowest net expected loss, despite some adaptive defenses reducing other risk measures. This highlights an important distinction between optimizing detection/risk and optimizing an operational objective including intervention costs. These findings depend on simulation assumptions and should not be interpreted as real-world deployment evidence.

## Repository contents
- `cognitive_load_aware_phishing_abm_egt_RACS_robustness.ipynb`: simulation, robustness, and analysis notebook.
- `cogload_phishing_outputs_last.zip`: archived simulation outputs (large ZIP; inspect its contents before use).

## Reproducing the study
This repository currently preserves an exploratory research notebook and output archive. Reproduction requires documenting the Python dependencies, notebook execution order, simulation settings, seeds, and output directories. Until these are verified, this should be regarded as a **research archive**, not a validated turnkey package.

## Research context
Developed during Erasmus+ academic mobility at the University of Salerno. The study extends EEG/cognitive-load research toward human-centered cybersecurity. The included notebook name references a RACS-oriented robustness analysis; it does **not** imply publication or acceptance at RACS.

[Project report](https://drive.google.com/file/d/1niWUfV3OTOL0TZQ8yLpHdI6fVq4qAXo5/view) · [Additional manuscript](https://drive.google.com/file/d/1Azf_OEUAKdJ5cEYk6xHRzkbElZpLYp6s/view)

## Author
Danial Daniyaruly · [GitHub](https://github.com/daniyarulydanial) · [LinkedIn](https://www.linkedin.com/in/danial-daniyaruly/)
