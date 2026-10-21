# Credit Risk & IFRS 9 Framework: End-to-End Modeling

Este repositorio contiene la implementación práctica del ciclo de vida de modelos de Probabilidad de Incumplimiento (PD), cubriendo tanto el enfoque estadístico/machine learning para originación/admisión como la adaptación metodológica a los requerimientos contables y regulatorios de la norma IFRS 9 (NIIF 9).

El código está estructurado en dos fases: desarrollo predictivo y monitoreo continuo, seguido del cálculo de pérdidas esperadas (ECL) a 12 meses y Lifetime con ajuste forward-looking.

---

## Estructura del Repositorio

```text
├── 01_credit_scoring_ml/
│   ├── 01_pd_model_development.ipynb
│   ├── 02_pd_calibration_and_mapping.ipynb
│   └── 03_model_monitoring_and_drift.ipynb
│
├── 02_ifrs9_ecl_framework/
│   ├── 01_pd_12m_monthly_cohorts.ipynb
│   └── 02_lifetime_pd_macro_scenarios.ipynb
│
└── README.md
