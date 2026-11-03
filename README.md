# Hi, I'm Pablo 👋

**Commercial asset manager turned energy data builder.**
Almost 10 years managing renewable assets (wind, PV, BESS) across Spain and Europe — now building data, ML and AI tools for fun (and also focused on the Iberian power market)

📍 Valencia, Spain

---

### ⚡ What I work on

- **Power market analytics** — OMIE/ESIOS day-ahead and intraday prices, capture rates, balancing (aFRR/mFRR), imbalances (*desvíos*), technical constraints (RRTT)
- **Forecasting & ML** — price forecasting at 15-minute resolution with gradient boosting, weather-driven features, hyperparameter optimisation
- **Weather & geospatial data** — ERA5-Land processing, capacity-weighted features for thousands of Spanish power plants
- **Commercial PV/BESS management** — O&M optimisation, PPAs, GoOs/RECs, Market data

### 🔭 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**Spanish spot price forecaster**]| 96 quarter-hourly D+1 forecasts of OMIE day-ahead prices; one XGBoost model per QH slot with ERA5-Land weather, gas (MIBGAS) and CO₂ features. Avg. MAE ≈ 15.8 €/MWh on 2025–26 out-of-sample data. Master's thesis (UPV). | Python · XGBoost · Optuna · pandas |
| [**ERA5-Land weather pipeline**]| Turns raw ERA5-Land archives into capacity-weighted 15-min weather features by snapping ~3,800 Spanish plants to the grid with a KD-tree. Memory-efficient numpy (~10M rows/month). | Python · numpy · h5netcdf · SciPy |
| [**MatchLens**](https://github.com/r0sick/matchlens) | AI match-intelligence app built for a Microsoft hackathon: turns football event data into explainable metrics, LLM-generated multi-language narratives, analyst vs. casual-fan views and a Fantasy points/transfer-advice module. | Python · Azure OpenAI · Microsoft Foundry · Web UI |
| 🚧 *Coming soon* | Spanish solar capture price & cannibalisation tracker — live dashboard | Streamlit · GitHub Actions |

### 🛠️ Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD)
![Optuna](https://img.shields.io/badge/Optuna-2C5BB4)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)

### 💼 Background

Commercial asset management at **Statkraft**, **Repsol**, **FRV** and **Blue Tree** — from O&M, PPAs, contract management, settlement review or reporting to O&M handovers and final acceptance and portfolio integrations to the Company's pipeline.
Currently completing a **Master's in Big Data Analytics** at Universitat Politècnica de València.

### 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:YOUR-EMAIL)

Open to roles in **renewable energy asset management, origination and energy analytics** in Spain.
