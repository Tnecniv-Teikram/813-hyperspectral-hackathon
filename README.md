# Arab 813 hyperspectral hackathon – Data & Notebook Repository

Welcome to the official GitHub repository for the **[Arab 813 Hackathon & Incubation Program](https://spaceacademy-hackathons.space.gov.ae/)**.

This repository is designed to support participants with:
- starter notebooks,
- theme-specific technical examples,
- satellite data exploration workflows,
- onboarding resources,
- and submission support materials.

The Arab 813 Hackathon is a regional online innovation program created to transform hyperspectral and Earth observation data into high-impact, scalable, and policy-relevant solutions. The program brings together participants from across the UAE and the Arab world to build solutions aligned with national priorities and the UN Sustainable Development Goals (SDGs). The top teams continue into a structured incubation phase to mature their prototypes into viable startups or deployable solutions.

---

## Table of Contents

- [Overview](#overview)
- [About the Hackathon](#about-the-hackathon)
- [Objectives](#objectives)
- [Who This Repository Is For](#who-this-repository-is-for)
- [Repository Structure](#repository-structure)
- [Themes](#themes)
  - [Climate Resilience & Disaster Recovery](#1-climate-resilience--disaster-recovery)
  - [Precision Agriculture & Crop Intelligence](#2-precision-agriculture--crop-intelligence)
  - [Marine & Water Security](#3-marine--water-security)
  - [Blue Carbon & Mangrove Health](#4-blue-carbon--mangrove-health)
  - [Sustainable Urban Planning](#5-sustainable-urban-planning)
  - [Air Quality & Atmospheric Monitoring](#6-air-quality--atmospheric-monitoring)
- [Getting Started](#getting-started)
- [How to Use the Notebooks](#how-to-use-the-notebooks)
  - [Data Exploration Notebook](#data-exploration-notebook)
  - [Theme Notebooks](#theme-notebooks)
- [Data Resources](#data-resources)
- [Platform & Tools](#platform--tools)
- [Recommended Workflow](#recommended-workflow)
- [Program Timeline](#program-timeline)
- [Team Deliverables](#team-deliverables)
- [Mentoring & Support](#mentoring--support)
- [Submission Guidance](#submission-guidance)
- [Repository Best Practices](#repository-best-practices)
- [Acknowledgements](#acknowledgements)

---

## 🌍 Overview

The Arab 813 Hackathon is a **multi-month online hackathon and incubation program** built around hyperspectral and other Earth observation data. Participants work in multidisciplinary teams to solve real-world challenges related to climate resilience, agriculture, water, ecosystems, and urban systems. Teams are supported with structured lectures, technical mentoring, curated datasets, and access to the **gIQ** geospatial platform.

This repository serves as the technical entry point for participants and contains the notebooks and examples needed to:
- explore the available datasets,
- understand the themes,
- prototype solution ideas,
- and prepare project deliverables.

---

## 🚀 About the 813 hackathon

The hackathon was created to celebrate and activate the potential of the **Arab Hyperspectral Satellite 813**, enabling participants to use hyperspectral and other Earth observation data to develop impactful downstream applications. The initiative is organized as part of the broader UAESA–Space42 ecosystem, which supports innovation, applied geospatial analytics, capacity building, and commercialization pathways in the UAE and across the Arab region.

Unlike a traditional weekend hackathon, this program is structured as a longer innovation pipeline:
1. registration and shortlisting,
2. Proof of Concept (PoC) development,
3. pitching and team selection,
4. incubation and MVP maturation,
5. and final evaluation and awards.

Target Audience: Students, data scientists, GIS professionals, and researchers passionate about Earth Observation (EO).

Official Landing Page: [Space Academy Hackathons](https://spaceacademy-hackathons.space.gov.ae/)

---

## Objectives

The program is designed around five core strategic objectives:

- **Maximize Satellite Impact** — enable early, high-value utilization of hyperspectral data through real-world applications.
- **Build Regional Capacity** — strengthen skills in hyperspectral analytics, AI, and geospatial intelligence among Arab youth, researchers, and professionals.
- **Foster Cross-Border Collaboration** — encourage collaboration across Arab institutions, universities, and innovation ecosystems.
- **Accelerate Commercialization** — support teams in transforming prototypes into startups, services, or deployable government/industry solutions.
- **Support Evidence-Based Policy** — generate analytics that inform decision-making in agriculture, water security, climate resilience, and disaster management.

---

## Who This repository is for

This repository is intended for:

- registered hackathon participants,
- technical team members,
- students and researchers,
- developers and geospatial data scientists,
- mentors supporting technical work,
- and organizers maintaining common resources.

It is particularly useful for participants who want a **structured technical starting point** to work with satellite data in Python, Google Colab, and cloud-native analysis workflows. The broader hackathon program is designed for multidisciplinary teams and supports both technical and entrepreneurial solution development. 

---
## 🎯 Themes

Participants are encouraged to build solutions within one of the following domains:

**Precision Agriculture & Crop Intelligence**: Optimize crop health, detect nutrient stress, and improve irrigation efficiency.

**Land Use & Land Cover**: Monitor urban expansion, classify infrastructure, and track environmental change.

**Air Quality & Atmospheric Monitoring**: Detect methane/CO₂ point-source plumes and analyze industrial aerosol patterns for public health.

**Climate Resilience & Disaster Recovery**: Map wildfire burn scars and flood extents for rapid response and recovery.

**Blue Carbon & Mangrove Health**: Protect mangroves and seagrasses via hyperspectral trait analysis.

**Marine & Water Security**: Monitor inland water quality, turbidity, and harmful algal blooms (HABs).

---

## 💻 Getting started

How to Run
These notebooks are built to run in standard Jupyter environments (e.g., JupyterLab, Google Colab, or local VS Code).

**Step 1: Clone the Repository**
```
Bash
git clone https://github.com/Tnecniv-Teikram/813-hyperspectral-hackathon
cd 813-hyperspectral-hackathon
```

**Step 2: Setup Environment**
Ensure you have the required geospatial libraries installed. We recommend using **conda** or **venv**:

```
Bash
pip install numpy matplotlib xarray rioxarray geopandas h5py pystac-client
```

**Step 3: Run the Notebooks**
Launch Jupyter: jupyter notebook

Start with **00_EO_data_quickstart.ipynb** to familiarize yourself with the STAC framework to search, read and view satellite data from within your jupyter notebook without downloading it directly.

Choose your theme-specific notebook to begin developing your hackathon solution.





````
