# Néstor O. Vásquez C.

**Electronic engineer · MSc candidate in Data Analytics**  
Embedded estimation, health-aware control, and applied machine learning.  
Bogotá, Colombia · Jitter Ingeniería SAS

[ORCID](https://orcid.org/0009-0003-6483-790X) · [LinkedIn](https://www.linkedin.com/in/nestor-vasquez-castro) · nvasquezc@ucentral.edu.co

---

## Research focus

I work on **estimating slowly-varying physical parameters from observer
residuals** in resource-constrained embedded systems. Two application
threads share this mathematical structure:

**Embedded metrology without traceability infrastructure.** Recovering
measurement confidence in instruments that cannot be routinely calibrated
against a reference standard.

**Health-aware control in low-cost power electronics.** Detecting and
compensating degradation — winding resistance, back-EMF constant, brush
voltage drop — online, inside the control loop, on commodity hardware.

Motivating context: environmental monitoring and off-grid energy access,
where the instruments that most need calibration are the least likely to
receive it.

---

## Work

## Work

**[dc-motor-fault-detection](https://github.com/nvasquezc/dc-motor-fault-detection)** · *in progress*

Closed-loop testbed on STM32F407VG producing a reproducible fault dataset with physically quantified severity, plus comparative classifier evaluation. The contribution is the system and its instrumentation: fault injection is parameterized in physical units, not categorical labels.

`STM32 HAL · EKF · PI control · DMA telemetry · PyQt6 · scikit-learn`

**firewatch-colombia**

Satellite wildfire monitoring pipeline: NASA FIRMS and GOES-19 ingestion, DBSCAN clustering of active fire detections, LLM-generated situation bulletins, served through a Dash dashboard.

`Python · Dash · scikit-learn`

**carcino-qsar** · *private, research group*

Carcinogenicity prediction under a medallion data architecture, with scaffold splits, class-imbalance handling, SHAP attribution, and OECD validation principles.

`RDKit · scikit-learn · Plotly · uv`

---

## Stack

| Domain | Tools |
|---|---|
| Embedded | STM32CubeIDE, HAL, C, DMA |
| Estimation & control | EKF, PI/PID, system identification |
| ML / Data | Python, scikit-learn, PyTorch, pandas, PyQt6, Plotly |
| MLOps | MLflow, Delta Lake, Databricks, GitHub Actions |
| Instrumentation | Oscilloscope, logic analyzer, serial telemetry |

---

## Background

MSc Data Analytics, Universidad Central de Colombia *(in progress)* ·
BSc Electronic Engineering · 6 years in IP/MPLS network engineering for
telecom operators · Engineering practice at Jitter Ingeniería SAS.
