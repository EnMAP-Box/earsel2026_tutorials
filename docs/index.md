---
title: Home
layout: home
---

# EARSeL Imaging Spectroscopy 2026 EnMAP Tutorials

**Last update: 2026-05-08**

EnMAP Tutorials at [14th EARSeL Workshop on Imaging Spectroscopy](https://is.earsel.org/workshop/14-IS-Helsinki2026/), 2-4 June 2026, Helsinki, Finland.


# Prerequisites

Participants are requested to bring their own Laptop.
Please install the required software in advance. 

The following setup is recommended:

1. Install a conda / conda-forge package installer, e.g., from https://conda-forge.org/download/
2. Create a conda environment that contains QGIS and *all python packages* that are required to run the tutorials.
   The environment is defined in [`enmaptutorials.yml`](https://github.com/EnMAP-Box/earsel2026_tutorials/blob/main/enmaptutorials.yml).

   ```bash
   # from web
   conda env create --file=https://raw.githubusercontent.com/EnMAP-Box/earsel2026_tutorials/refs/heads/main/enmaptutorials.yml -y
   ```
   
3. Activate the conda environment
   ````bash
   conda activate enmaptutorials
   ```` 
4. Start QGIS from the conda environment and use a new user profile dedicated to the tutorials
   ````bash
   (enmaptutorials) qgis --profile EnMAP-Tutorials
   ```` 
   ![installation_qgis_empty.png](img/installation_qgis_empty.png)

5. Open the QGIS Plugin Manager and install the EnMAP-Box plugin

   ![installation_qgis_pm1.png](img/installation_qgis_pm1.png)

   ![installation_qgis_pm2.png](img/installation_qgis_pm2.png)



# Schedule
## Part I (09:00 - 11:30)

* 09:00 - 09:30: Installation of required software
* 09:30 - 10:30: EnMAP-Box
  *  Introduction
  *  New Features
* 10:30 - 11:30: EnMAP Data Access* 


## Part II (12:30 - tbd.)

* 12:30 – 13:30 EnMAP Preprocessing Tool (EnPT)
* 13:30 – 14:30 Water Tools
* 14:30 – 15:30 EnSoMAP

