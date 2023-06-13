---
title: MDverse
feature_text: |
  ## MDverse
  #### Exploring molecular dynamics data
feature_image: "/assets/img/background.jpg"
layout: page
---

MDverse is an international project aiming at indexing, annotating and exploring molecular dynamics simulation data with the ultimate goal of making it **reusable**.

> 💡 Did you know? **1 %** of all data stored in the data repository [Zenodo](https://zenodo.org/) is related to molecular dynamics simulations? 

## Achievements

[Data collection](https://zenodo.org/record/7856806): about 250,000 files and 2,000 datasets have been indexed so far. All data are shared as Parquet files under Creative Commons Attribution 4.0 International (CC BY 4.0) license.

[MDverse data explorer](https://mdverse.streamlit.app/) is a prototype search engine for molecular dynamics data. Browse collected files and search for specific data using keywords.

Preprint: [MDverse: Shedding Light on the Dark Matter of Molecular Dynamics Simulations](https://www.biorxiv.org/content/10.1101/2023.05.02.538537v1), bioRxiv, 2023. 

> 📝 The *dark matter of MD* refers to data that is technically accessible, but neither indexed, curated, or easily searchable.


## Developments

All developments are open-source, available on GitHub and archived in Software Heritage:

- [MDverse web scrapper](https://github.com/MDverse/mdws): index and collect MD data from generic data repositories (Zenodo, Figshare and Open Science Framework). Download and mine .mdp and .gro Gromacs files.
- [MDverse data analysis](https://github.com/MDverse/mdda): analyze MD data previously collected by the web scrapper.
- [MDverse data explorer](https://github.com/MDverse/mdde): prototype search engine for MD data.

