<img align="center" src="https://raw.githubusercontent.com/pythonhealthdatascience/.github/main/images/stars_logo_blue_text.png" alt="STARS: Sharing Tools and Artefacts for Reproducible Simulations">

## STARS Framework

The STARS framework is a set of open practices, tools and learning materials to produce enhanced versions of research artefacts that intend to increase accessibility for others to (re)use, adapt and build on work.

Essential components of STARS framework (shaded in green below):
* Open license
* Dependency management
* Model created using free and open-source software (FOSS)
* Minimum documentation
* Research artefact meta data (ORCID ID + citation information)
* Remote code repository
* Open science archive

Optional components of STARS framework (shaded in blue below):
* Enhanced documentation
* Documentation hosting
* Online coding environment
* Model interface
* Web app hosting

<img align="center" src="https://raw.githubusercontent.com/pythonhealthdatascience/.github/main/images/stars_framework_overview.png" alt="STARS framework overview">

## Repositories

Several repositories are related to our recent paper '[Towards sharing tools and artefacts for reusable simulations in healthcare](https://doi.org/10.1080/17477778.2024.2347882)', which includes three examples of the implemented STARS framework in Python:
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

As part of STARS, we are assessing the reproducibility of published simualation models, with related repositories as follows:
| Repositories | Description |
| --- | --- |
| [stars-reproduction-protocol](https://github.com/pythonhealthdatascience/stars_reproduction_protocol) | Latex files for reproduction protocol |
| [stars-reproduce-allen-2020](https://github.com/pythonhealthdatascience/stars-reproduce-allen-2020) |Test run of reproducibility protocol on Allen et al. 2020 |
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

There is a tutorial on discrete-event simulation for the Operational Research Society Simulation Workshop 2025:

| Repositories | Description |
| --- | --- |
| [intro-open-sim](https://github.com/pythonhealthdatascience/intro-open-sim) | An introduction to Discrete-Event Simulation using Free and Open Source Software |

Other repositories are:
| Repositories | Description |
| --- | --- |
| [stars-publications](https://github.com/pythonhealthdatascience/stars-publications) | List of all STARS publications |
| [stars-logo](https://github.com/pythonhealthdatascience/stars-logo) | SVG and PNG files with logo |
| [stress_update](https://github.com/pythonhealthdatascience/stress_update) | A review and update of the Strengthening the Reporting of Empirical Simulation Studies guidelines for DES, SD, and ABS. |
| [stars-eom-rcc](https://github.com/pythonhealthdatascience/stars-eom-rcc) | Modifications to the "Exeter Oncology Model: Renal Cell Carcinoma edition (EOM-RCC)" as part of STARS work package 3. |
| [stars_wp3_summary](https://github.com/pythonhealthdatascience/stars_wp3_summary) | Reflections from prospective and retrospective application of the STARS framework |

## Team

| Member | ORCID | GitHub |
| --- | --- | --- |
| Thomas Monks | [![ORCID: Monks](https://img.shields.io/badge/ORCID-0000--0003--2631--4481-brightgreen)](https://orcid.org/0000-0003-2631-4481) | https://github.com/TomMonks |
| Alison Harper | [![ORCID: Harper](https://img.shields.io/badge/ORCID-0000--0001--5274--5037-brightgreen)](https://orcid.org/0000-0001-5274-5037) | https://github.com/AliHarp |
| Navonil Mustafee | [![ORCID: Mustafee](https://img.shields.io/badge/ORCID-0000--0002--2204--8924-brightgreen)](https://orcid.org/0000-0002-2204-8924) | https://github.com/NavonilNM |
| Andrew Mayne | [![ORCID: Mayne](https://img.shields.io/badge/ORCID-0000--0003--1263--2286-brightgreen)](https://orcid.org/0000-0003-1263-2286) | https://github.com/andy-mayne |
| Amy Heather | [![ORCID: Heather](https://img.shields.io/badge/ORCID-0000--0002--6596--3479-brightgreen)](https://orcid.org/0000-0002-6596-3479) | https://github.com/amyheather |
