# Rosa María Mariscal Romero

**Applied Data Scientist | Quantitative modeling, machine learning & time series in Python | Risk & uncertainty modeling | 13+ yrs applied ML | PhD Engineering (UNAM), physicist | Postdoc & AI lecturer, UNAM**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rosa%20Mar%C3%ADa%20Mariscal-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rosa-mar%C3%ADa-m-6474a416b/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0001--8366--6718-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0001-8366-6718)
[![Email](https://img.shields.io/badge/Email-rosa.m.mariscal%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:rosa.m.mariscal@gmail.com)

**Open to Applied Data Scientist roles, including digital assets and financial AI.** Based in Mexico City.

I frame the problem, build features from incomplete and messy data, evaluate models honestly with their biases and uncertainty documented, and automate the resulting decision so it can be reused.

## Capabilities

### Prediction / forecasting
Multivariate time-series forecasting (random forests, LSTM), neural-network regression to complete incomplete series, probabilistic inference.
- [Predicción](https://github.com/rosammariscal/Predicci-n): lagged-correlation input selection, then a multi-output random forest and an LSTM (Keras) forecasting Google Community Mobility data (Puebla, Mexico), evaluated on a held-out final period.
- Neural networks to complete geophysical well logs from incomplete, uncertain lab and field data: IIMAS, UNAM (Aug 2014 – May 2016) and TEMPLE (Jan 2012 – Aug 2013).
- Predictive models for decision support in consumer goods, as an independent consultant (Aug – Dec 2021).

### Pattern recognition & classification
Supervised and unsupervised classification: random forests, clustering (k-means, Gaussian mixtures), self-organizing maps, computer vision.
- [Clasificación](https://github.com/rosammariscal/Clasificaci-n): unsupervised classification of mobility time series (Tabasco, Mexico) with lagged features, k-means and a self-organizing map.
- [RandomForest](https://github.com/rosammariscal/RandomForest): decision-tree and random-forest classifiers on the Pima diabetes dataset (scikit-learn).
- [Mecánica de Fluidos](https://github.com/rosammariscal/Mec-nica-de-Fluidos): Gaussian-mixture clustering of pipe-flow data, compared with Reynolds-number flow regimes.
- Computer vision: ROJA, a Python image-analysis tool for oil–water droplet statistics ([ACS Omega 2026](https://doi.org/10.1021/acsomega.6c01366)).
- Lithology classification with self-organizing maps and neural networks (HAGREPE, IIMAS, 2014–2016). Random forests, clustering, pattern recognition and basic NLP for consumer-goods, mobility and telecom clients (BIGDATA4ALL, 2019–2021).

### Simulation
Numerical and semi-analytical modeling of flow in fractured porous media in Python: finite differences, fractal and fractional-derivative models, Newton–Raphson.
- [UnconventionalReservoirSimulatorLib](https://github.com/rosammariscal/UnconventionalReservoirSimulatorLib): 3D finite-difference simulator of gas flow to a hydraulically fractured well in shale, from my PhD (UNAM, 2022). Fractal permeability and porosity, Caputo fractional derivatives, Forchheimer flow and Langmuir desorption.
- Papers: [URTeC 2022](https://doi.org/10.15530/urtec-2022-3724064) (3D fractal model) and [Transport in Porous Media 2025](https://doi.org/10.1007/s11242-025-02203-2) (semi-analytical flow model).
- Synthetic seismogram implementation (IIMAS, UNAM, 2014–2016).

### Optimization
Hyperparameter search, constraint-aware heuristic scheduling, genetic algorithms (PyGAD).
- [RandomForest](https://github.com/rosammariscal/RandomForest): Optuna search over decision-tree hyperparameters (depth, split and leaf sizes, criterion).
- [Schedule module](https://github.com/rosammariscal/UnconventionalReservoirSimulatorLib/blob/main/bibScheduleOptimization.py) (2023): greedy scheduler that assigns a semester of field trips to vans and buses by date. It respects vehicle capacity, drivers per day, allowed weekdays and trip length, then flags same-destination trips that fit in one bus.
- Supervise machine-learning and optimization theses, Faculty of Engineering, UNAM (Dec 2022 – present).

### Automated decision-making
Rule-based ranking under constraints, Bayesian networks (pgmpy) for probabilistic inference, decision support.
- [cagr-growth-value-pipeline](https://github.com/rosammariscal/cagr-growth-value-pipeline): reproducible gates → cross-sectional ranks → composite score → capped Top-N weights → CSV, with every dropped value flagged. Personal research, not advice.
- Bayesian networks to infer water saturation, in my MSc thesis (Institute of Physics, UNAM, 2017).
- Turned model results into operational recommendations for clients (BIGDATA4ALL, 2019–2021) and delivered interpretable decision-support analytics (independent consultant, 2021).

## Featured project

### [cagr-growth-value-pipeline](https://github.com/rosammariscal/cagr-growth-value-pipeline)

A reproducible Python pipeline that scores equities on growth, value and quality using yfinance data. It computes multi-year revenue, net income and FCF CAGRs, adds a valuation overlay (P/E, P/B, FCF yield), applies eligibility gates and builds capped Top-N weights. Look-ahead and survivorship bias are documented, and the code is unit-tested.  
Personal research: a screening tool with no backtest and no performance claims. Not investment advice.

`Python` `pandas` `NumPy` `yfinance` `pytest`

## Selected publications

- Montaño-Salazar, Gómora-Figueroa, Zenit & Mariscal-Romero. *Rheological Insights: The Role of Divalent Ions on the Stability and Phase Behavior of Oil–Water Emulsions.* ACS Omega (2026). Covers ROJA, a Python image-analysis tool for droplet statistics. [doi:10.1021/acsomega.6c01366](https://doi.org/10.1021/acsomega.6c01366)
- Teja-Juárez et al. *A Semi-Analytical Model to Simulate Fluid Flow in Fractured Reservoirs.* Transport in Porous Media (2025). [doi:10.1007/s11242-025-02203-2](https://doi.org/10.1007/s11242-025-02203-2)
- Mariscal-Romero & Camacho-Velázquez. *Three-dimensional Fractal Model of Hydraulically Fractured Horizontal Wells in Anisotropic Naturally Fractured Reservoirs.* URTeC 2022, Houston. [doi:10.15530/urtec-2022-3724064](https://doi.org/10.15530/urtec-2022-3724064)

Full list: [ORCID 0009-0001-8366-6718](https://orcid.org/0009-0001-8366-6718)

## Experience

- **CONAHCYT Postdoctoral Researcher & Adjunct Professor**, Faculty of Engineering, UNAM (Dec 2022 – present): I teach AI algorithms for petroleum engineering (graduate) and supervise ML and optimization theses.
- **Independent Consultant, Analytics & Applied AI** (Aug – Dec 2021): predictive models and analytics for decision support in consumer goods (client: Danone Mexico, Digital Insights).
- **Data Scientist / Consultant**, BIGDATA4ALL (Jun 2019 – Dec 2021): ML models for consumer-goods, mobility and telecom clients (Danone, ADO, Levi's, Telmex). Data workflows in pandas, with Spark/Hadoop when volume required it.
- **Developer, ML for Subsurface Data**, IIMAS, UNAM (Aug 2014 – May 2016): neural networks and self-organizing maps in SENER–CONACYT hydrocarbons projects.
- **Senior Developer**, Lennken Group (Sep 2013 – May 2014): .NET REST portal and Android apps in production (AXA Seguros, ODM).
- **Physicist, ML Models**, TEMPLE (Jan 2012 – Aug 2013): supervised and self-organizing neural networks, with custom ML libraries in C++ and C#.
- **Volunteer:** Latin America Regional Co-Chair, SPE Data Science and Engineering Analytics Technical Section (DSEATS), since 2024.

## Education

- **PhD in Engineering** (Reservoirs), UNAM, 2022. Thesis: hydraulically fractured wells in anisotropic media with fractal and fractional derivatives, with a numerical simulator in Python.
- **MSc in Physics** (Statistical Mechanics & Complex Systems), UNAM, 2017. Thesis: Bayesian networks for water-saturation inference.
- **BSc in Physics**, BUAP, 2009.

## Stack

**Python** (pandas, NumPy, SciPy, scikit-learn, TensorFlow/Keras, pgmpy, Optuna, PyGAD, pytest) · SQL · R · C++ · C#/.NET · MATLAB · Java · Git · Spark/Hadoop when volume requires it · AWS & GCP working environments  
Languages: Spanish (native), English (advanced)

## Contact

- LinkedIn: [linkedin.com/in/rosa-maría-m-6474a416b](https://www.linkedin.com/in/rosa-mar%C3%ADa-m-6474a416b/)
- ORCID: [0009-0001-8366-6718](https://orcid.org/0009-0001-8366-6718)
- Email: [rosa.m.mariscal@gmail.com](mailto:rosa.m.mariscal@gmail.com)
