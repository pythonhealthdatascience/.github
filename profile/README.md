Welcome to the **pythonhealthdatascience** GitHub organisation!

> Note on our name: We started as a Python-only initiative, but quickly expand to include R to, as another popular language for healthcare simulation.

This project tackles the challenges of **sharing, reusing, and reproducing** discrete event simulation (DES) models in healthcare. Our goal is to create open resources using the two most popular open-source languages for DES: Python and R. Here you’ll find tutorials, code examples, and tools to help researchers and practitioners develop, validate, and share DES models more effectively.

This work has been centred around three important qualities for shared models - that they can be:

* **Reproducible** - running code regenerates the published results - which verifies code is working as expected and increases trust.
* **Reusable** - code can be adapted and used in new contexts - which saves time and increases impact.
* **Replicable** - new code based on described methods produces consistent results - which gives confidence in results, their validity and reliability.

We have also been exploring how large language models (LLMs) could be used to support the development of simulation models.

Explore our repositories to get started, and feel free to reach out!

Project team members:

**Tom Monks**

* [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--2631--4481-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-2631-4481)
* [![GitHub](https://img.shields.io/badge/GitHub-TomMonks-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TomMonks)
* [![Email](https://img.shields.io/badge/Email-t.m.w.monks%40exeter.ac.uk-de7e72?style=for-the-badge&logo=gmail&logoColor=white)](mailto:t.m.w.monks@exeter.ac.uk)

**Amy Heather**

* [![ORCID](https://img.shields.io/badge/ORCID-0000--0002--6596--3479-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0002-6596-3479)
* [![GitHub](https://img.shields.io/badge/GitHub-amyheather-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amyheather)
* [![Email](https://img.shields.io/badge/Email-a.heather2%40exeter.ac.uk-de7e72?style=for-the-badge&logo=gmail&logoColor=white)](mailto:a.heather2@exeter.ac.uk)

**Alison Harper**

* [![ORCID](https://img.shields.io/badge/ORCID-0000--0001--5274--5037-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0001-5274-5037)
* [![GitHub](https://img.shields.io/badge/GitHub-AliHarp-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AliHarp)
* [![Email](https://img.shields.io/badge/Email-a.l.harper%40exeter.ac.uk-de7e72?style=for-the-badge&logo=gmail&logoColor=white)](mailto:a.l.harper@exeter.ac.uk)

**Nav Mustafee**

* [![ORCID](https://img.shields.io/badge/ORCID-0000--0002--2204--8924-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0002-2204-8924)
* [![GitHub](https://img.shields.io/badge/GitHub-NavonilNM-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NavonilNM)
* [![Email](https://img.shields.io/badge/Email-n.mustafee%40exeter.ac.uk-de7e72?style=for-the-badge&logo=gmail&logoColor=white)](mailto:n.mustafee@exeter.ac.uk)

**Andy Mayne**

* [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--1263--2286-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-1263-2286)
* [![GitHub](https://img.shields.io/badge/GitHub-andy--mayne-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/andy-mayne)
* [![Email](https://img.shields.io/badge/Email-andrew.mayne%40somersetft.nhs.uk-de7e72?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andrew.mayne@somersetft.nhs.uk)

**Fatemeh Alidoost**

* [![ORCID](https://img.shields.io/badge/ORCID-0009--0000--0252--560X-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0000-0252-560X)
* [![GitHub](https://img.shields.io/badge/GitHub-Falidoost-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Falidoost)
* [![Email](https://img.shields.io/badge/Email-fa418%40exeter.ac.uk-de7e72?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fa418@exeter.ac.uk)

## Reproducible simulations

<details><summary>Click to find out more</summary>

### Assessing the reproducibility of published DES models

We attempted to reproduce the outputs from eight Python and R DES models, as described in:

> Heather, A., Monks, T., Harper, A., Mustafee, N., & Mayne, A. (2025). On the reproducibility of discrete-event simulation studies in health research: an empirical study using open models. arxiv. <https://doi.org/10.48550/arXiv.2501.13137>.

| Repositories | Description |
| --- | --- |
| [stars-reproduction-protocol](https://github.com/pythonhealthdatascience/stars_reproduction_protocol) | Latex files for reproduction protocol |
| [stars-reproduce-allen-2020](https://github.com/pythonhealthdatascience/stars-reproduce-allen-2020) | Test run of reproducibility protocol on Allen et al. 2020 |
| [stars-reproduction-template](https://github.com/pythonhealthdatascience/stars_reproduction_template) | Template for assessment of computational reproducibility |
| [stars-reproduce-shoaib-2022](https://github.com/pythonhealthdatascience/stars-reproduce-shoaib-2022) | Reproduction study 1: Shoaib and Ramamohan 2022 (Python) |
| [stars-reproduce-huang-2019](https://github.com/pythonhealthdatascience/stars-reproduce-huang-2019) | Reproduction study 2: Huang et al. 2019 (R) |
| [stars-reproduce-lim-2020](https://github.com/pythonhealthdatascience/stars-reproduce-lim-2020) | Reproduction study 3: Lim et al. 2020 (Python) |
| [stars-reproduce-kim-2021](https://github.com/pythonhealthdatascience/stars-reproduce-kim-2021) | Reproduction study 4: Kim et al. 2021 (R) |
| [stars-reproduce-anagnostou-2022](https://github.com/pythonhealthdatascience/stars-reproduce-anagnostou-2022) | Reproduction study 5: Anagnostou et al. 2022 (Python) |
| [stars-reproduce-johnson-2021](https://github.com/pythonhealthdatascience/stars-reproduce-johnson-2021) | Reproduction study 6: Johnson et al. 2021 (R) |
| [stars-reproduce-hernandez-2015](https://github.com/pythonhealthdatascience/stars-reproduce-hernandez-2015) | Reproduction study 7: Hernandez et al. 2015 (Python model + R figures) |
| [stars-reproduce-wood-2021](https://github.com/pythonhealthdatascience/stars-reproduce-wood-2021) | Reproduction study 8: Wood et al. 2021 (R) |
| [stars_wp1_summary](https://github.com/pythonhealthdatascience/stars_wp1_summary) | Summary of the eight computational reproducibility assessments conducted as part of STARS Work Package 1. These assessed discrete-event simulation papers with models in Python and R. |

### Online book guiding how to create reproducible Python and R DES models

We are developing a book which demonstrates how to create DES models in Python (SimPy) and R (simmer) which are reproducible - following the recommendations from our assessment above - and also, form a reproducible analytical pipeline. This is illustrated using a simple template model and an applied stroke model.

| Repositories | Description |
| --- | --- |
| [des_rap_book](https://github.com/pythonhealthdatascience/des_rap_book) | Online book providing detailed step-by-step guidance on developing reproducible DES models in Python and R |
| [rap_template_python_des](https://github.com/pythonhealthdatascience/rap_template_python_des) | Template reproducible analytical pipeline (RAP) for simple python discrete-event simulation (DES) model. |
| [rap_template_r_des](https://github.com/pythonhealthdatascience/rap_template_r_des) | Template reproducible analytical pipeline (RAP) for simple R discrete-event simulation (DES) model. |
| [stroke_rap_python](https://github.com/pythonhealthdatascience/stroke_rap_python) | Applying the Python DES RAP Template to the Stroke Capacity Planning Model from Monks et al. 2016. |
| [stroke_rap_r](https://github.com/pythonhealthdatascience/stroke_rap_r) | Applying the R DES RAP Template to the Stroke Capacity Planning Model from Monks et al. 2016. |

</details>

## Reusable simulations

<details><summary>Click to find out more</summary>

### Systematic review

We conducted a systematic review of how healthcare DES models (any software/language) are currently shared in the literature.

We identified common barriers to model reuse, including lack of documentation and standardised repositories.

Key takeaway: There is a clear need for better frameworks and tools to support reusable simulation models.

> Monks, T., & Harper, A. (2023). Computer model and code sharing practices in healthcare discrete-event simulation: a systematic scoping review. Journal of Simulation, 19(1), 108–123. https://doi.org/10.1080/17477778.2023.2260772

### STARS framework

Following this review, we developed the STARS framework, which provides essential and optional guidance to help make shared models more reusable. This is described in:

> Monks, T., Harper, A., & Mustafee, N. (2024). Towards sharing tools and artefacts for reusable simulations in healthcare. Journal of Simulation, 1–20. <https://doi.org/10.1080/17477778.2024.2347882>

This paper included three examples of the STARS framework implemented in Python:

| Repositories | Description |
| --- | --- |
| [stars-treat-sim](https://github.com/pythonhealthdatascience/stars-treat-sim) | STARS paper example 1. Implements essential components + annotated notebook to run code executable online with Binder |
| [stars-simpy-example-docs](https://github.com/pythonhealthdatascience/stars-simpy-example-docs)<br><br>[stars-streamlit-example](https://github.com/pythonhealthdatascience/stars-streamlit-example) | STARS paper example 2. Fully implements essential + optional components including enhanced documentation hosted online and web app |
| [stars-ciw-example](https://github.com/pythonhealthdatascience/stars-ciw-example) | STARS paper example 3. Fully implements essential + optional components, but with different licence, documentation publishing software, web app framework and web app hosting |

Subsequently, we have been developing similar examples in R, as well as looking at webassembly:

| Repositories | Description |
| --- | --- |
| [stars-treat-simmer](https://github.com/pythonhealthdatascience/stars-treat-simmer) | R simmer implementation of treatment simulation model |
| [stars-shiny-simmer](https://github.com/pythonhealthdatascience/stars-shiny-simmer) | Template for shiny interface to simmer DES model |
| [stars-stlite-example](https://github.com/pythonhealthdatascience/stars-stlite-example) | stlite template for SimPy models |
| [stars-simpy-jupterlite](https://github.com/pythonhealthdatascience/stars-simpy-jupterlite) | JupyterLite template for SimPy models |

### Applying STARS

We applied the STARS framework to an oncology cost-effectiveness model developed by PenTAG and collaborates for the NICE Pathways Pilot appraisal.

| Repositories | Description |
| --- | --- |
| [stars-eom-rcc](https://github.com/pythonhealthdatascience/stars-eom-rcc) | Modifications to the "Exeter Oncology Model: Renal Cell Carcinoma edition (EOM-RCC)" as part of STARS work package 3. |

</details>

## Replicable simulations

<details><summary>Click to find out more</summary>

### STRESS guidelines

Tom was involved in developing the Strengthening The Reporting of Empirical Simulation Studies (STRESS) guidelines. They are a 20-item checklist (with guidelines for DES, agent-based simulation, and system dynamics) which outline the details authors should include about their model in their reports/publications.

> Monks, T., Currie, C. S. M., Onggo, B. S., Robinson, S., Kunc, M., & Taylor, S. J. E. (2018). Strengthening the reporting of empirical simulation studies: Introducing the STRESS guidelines. Journal of Simulation, 13(1), 55–67. <https://doi.org/10.1080/17477778.2018.1442155>.

### Updating STRESS

We are currently undergoing a review and update of the STRESS guidelines.

| Repositories | Description |
| --- | --- |
| [stress_update](https://github.com/pythonhealthdatascience/stress_update) | A review and update of the Strengthening the Reporting of Empirical Simulation Studies guidelines for DES, SD, and ABS. |

</details>

## Using LLMs

<details><summary>Click to find out more</summary>

### Generating DES models using LLMS

We investigated the ability to replicate Discrete-Event Simulation models reported in the literature using iterative prompting of Perplexity.AI's foundational model:

> Monks, T., Harper, A., & Heather, A. (2025). Unlocking the Potential of Past Research: Using Generative AI to Reconstruct Healthcare Simulation Models. arxiv. <https://doi.org/10.48550/arXiv.2503.21646>

| Repositories | Description |
| --- | --- |
| [llm_simpy](https://github.com/pythonhealthdatascience/llm_simpy) | Code for exploring the ability of LLMs to generate SimPy models and streamlit interfaces. |
| [llm_simpy_models](https://github.com/pythonhealthdatascience/llm_simpy_models) | The SimPy models and apps generated by LLMs, deployed as a single app. |

</details>

## Other repositories

<details><summary>Click to find out more</summary>

### SW25 DES in Python tutorial

There is a tutorial on discrete-event simulation for the Operational Research Society Simulation Workshop 2025:

> Monks, T., Harper, A., Heather, A., Mayne, A., & Mustafee, N. (2025). Building healthcare discrete-event simulation models in free and open source software: an introductory tutorial. Proceedings of the Operational Research Society Simulation Workshop 2025 (SW25). <https://doi.org/10.36819/SW25.004>.

| Repositories | Description |
| --- | --- |
| [intro-open-sim](https://github.com/pythonhealthdatascience/intro-open-sim) | An introduction to Discrete-Event Simulation using Free and Open Source Software. |

### GW4 Open Research Prize

Amy was shortlisted for the GW4 Open Research Prize for her work on assessing the computational reproducibility of published models. The slides from her presentation at the prize ceremony are here:

| Repositories | Description |
| --- | --- |
| [gw4_prize_presentation](https://github.com/pythonhealthdatascience/gw4_prize_presentation) | Amy Heather's presentation for the GW4 Open Research Prize 2024/25. |

### Review of computer simulation in orthopaedic services

We used a topic modelling approach to examine and map the computational simulation literature applied to operational-level orthopedics services, combined with a structured analysis of the papers. The repository below serves as supplementary material for the paper:

> Mapping Applications of Computer Simulation in Orthopedic Services: A Topic Modeling Approach.

| Repositories | Description |
| --- | --- |
| [scope_wsc_2025](https://github.com/pythonhealthdatascience/scope_wsc_2025) | Data and analysis for a literature review of simulation for orthopaedics services |

### Other STARS repositories

| Repositories | Description |
| --- | --- |
| [stars-publications](https://github.com/pythonhealthdatascience/stars-publications) | List of all STARS publications |
| [stars-logo](https://github.com/pythonhealthdatascience/stars-logo) | SVG and PNG files with logo |
| [stars_wp3_summary](https://github.com/pythonhealthdatascience/stars_wp3_summary) | Reflections from prospective and retrospective application of the STARS framework |

</details>
