---
lang: en
theme: csc-2019
title: EO @ CSC
---


# CSC 

* non-profit state enterprise with special tasks
* owned by Finnish state (70%) and higher education institutions (30%)
* headquaters in Keilaniemi, Espoo
* side offices and supercomputers in Kajaani

# Geoportti and CSC

* Finnish research infrastructure
* CSC is one of many project partners
* technical implementation
* computing support

# CSC services

[`research.csc.fi/en/service-catalog`](https://research.csc.fi/en/service-catalog)

<div class="column">
**Compute & Analyze**

  - cPouta / ePouta
  - Puhti / Mahti / LUMI
  - Notebooks
  - Rahti

</div>

<div class="column">
**Store, Share & Publish Data**

  * Allas
  * EUDAT
  * IDA
  * Paituli

</div>

\+ Sensitive Data (SD) services


# Storing EO data

Allas object storage

* during project lifetime
* CSC account and project required
* access from other services and own computer
* data is immutable
* Maximum size for free: **200TB**

[Allas and Geospatial data webinar](https://www.youtube.com/watch?v=mnFXe2-dJ_g)


# Key to geocomputing

<p align="center">
  <img src="images/gui_to_script.png" width="50%">
</p>


# EO data processing and analysis

![](images/puhti_pouta_table.png)


# Pouta cloud

* Virtual Machines
* available on demand
* under own administration
* ideal for webserver / databases

# Puhti supercomputer

-> High Performance Computing

Main differences to laptop:
* memory and CPU(/GPU) availability
* non-interactive
* resource knowledge

# Computing solutions - Puhti


<p align="center">
  <img src="images/puhti_overview.png" width="50%">
</p>

# Puhti webinterface 


-> check your data, testing, code development, file management, quotas, apps

[`puhti.csc.fi`](https://puhti.csc.fi)


# Why use Puhti?

When own computer is not enough:

* Resource needs (time (> 2 hours), memory (> 8 GB), storage (> 50GB))
* prebuilt environments
* parallelization
* data availability (Paituli)

**-> Outsource heavy computations, keep own computer free**

* It’s **free**! (for open science at Finnish higher education and state research institutes)


# Software and data

[List of Applications in Docs](https://docs.csc.fi/apps/#geosciences)

stored in modules, geoconda (Python, +)

[List of Geoscience data sets available from CSC computing environment](https://docs.csc.fi/data/datasets/spatial-data-in-csc-computing-env/)


# Common EO challenges

* many tiles 
-> "embarassingly parallel"
* huge "dataframes"
-> dask(Python)/future(R)
* data transfer
-> Allas


# Get access

[Step by step instructions ](https://research.csc.fi/en/accounts-and-projects)

* Account 
* Project
* Resources
* Services
* [Find your account and project information](my.csc.fi)
* [Read the docs](https://docs.csc.fi)
* check our [tutorials](https://docs.csc.fi/support/tutorials/) and [geocomputing examples](https://github.com/csc-training/geocomputing)

# CSC expertise


...at your fingertips:

<div class="column">
[`docs.csc.fi`](https://docs.csc.fi)

[`research.csc.fi`](https://research.csc.fi)

</div>

<div class="column">
**\+ servicedesk@csc.fi**
* Geoinformatics team
* Data analytics and AI team
* Storage team
* Supercomputer team
* Cloudcomputing team
* Accounts team
* ...
</div>


# How we can help

<div class="column">
* 'Z is not working as expected'
* 'my code gives error Y '
* 'can A be installed to Puhti?'
* 'any advice how to do X?'
* training/example wishes

**-> servicedesk@csc.fi**
</div>

<div class="column">
[Speed up your request](https://docs.csc.fi/support/support-howto/)

* Setting up pipelines, product provision, R&D, ...

**-> CSC as project partner / subcontractor**
</div>

# Training

* ['Using CSC environment efficiently' course](https://csc-training.github.io/csc-env-eff/)
* [18.05: Webinar - CSC´s generic services for storing, sharing and publishing data](https://ssl.eventilla.com/event/pEAl3)
* [09.-10.06: Fundamentals of Machine Learning](https://ssl.eventilla.com/mlfundamentals)
* [CSC geoinformatics training material](https://research.csc.fi/gis-learning-materials)

-> follow our [training calendar](https://www.csc.fi/en/training#training-calendar)


# Geoinformatics team { .author } 

| Kylli Ek
| Samantha Wittke
| Katri Tegel
| CSC – IT Center for Science Ltd.

giscoord@csc.fi

![](images/geoportti.png)


