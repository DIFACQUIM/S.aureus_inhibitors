# Structure-Activity Relationships and Design of Focused Libraries Tailored for Staphylococcus aureus Inhibition  

[![Powered by RDKit](https://img.shields.io/badge/Powered%20by-RDKit-3838ff.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQBAMAAADt3eJSAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAFVBMVEXc3NwUFP8UPP9kZP+MjP+0tP////9ZXZotAAAAAXRSTlMAQObYZgAAAAFiS0dEBmFmuH0AAAAHdElNRQfmAwsPGi+MyC9RAAAAQElEQVQI12NgQABGQUEBMENISUkRLKBsbGwEEhIyBgJFsICLC0iIUdnExcUZwnANQWfApKCK4doRBsKtQFgKAQC5Ww1JEHSEkAAAACV0RVh0ZGF0ZTpjcmVhdGUAMjAyMi0wMy0xMVQxNToyNjo0NyswMDowMDzr2J4AAAAldEVYdGRhdGU6bW9kaWZ5ADIwMjItMDMtMTFUMTU6MjY6NDcrMDA6MDBNtmAiAAAAAElFTkSuQmCC)](https://www.rdkit.org/)

# **Focused Libraries**
## **Project Overview**
In this project, we curated and analyzed compounds tested against *S. aureus* FabI, which were sourced from ChEMBL. We employed visualization techniques such as t-Distributed Stochastic Neighbor Embedding (t-SNE) and Principal Moments of Inertia (PMI), alongside the distribution of various descriptors, to explore the chemical space of the *S. aureus* dataset. We applied transformation rules to the most potent *S. aureus* FabI inhibitors, resulting in the creation of three newly designed focused libraries: INDDS, DIADS, and PYRDS.
We developed machine learning (ML) models to predict pIC<sub>50</sub> values (ppIC<sub>50</sub>), utilizing molecular properties and descriptors including topological, constitutional, and fingerprint data using SciKit-learn (v.1.6). We assessed the presence of activity cliffs (ACs) within the *S. aureus* dataset using a Structure-Activity Similarity (SAS) map. By identifying and removing certain inhibitors, we enhanced our model's performance.
The newly designed libraries were further evaluated using the cumulative distribution function of pairwise compounds, complemented by t-SNE and PMI visualizations. Compounds were ranked based on structural similarity and the ppIC<sub>50</sub> values derived from our ML models.
## **The scripts consist**
* **Dataset Retrieval and Curation** 
* **Dataset Analysis**
  * **Distribution of *S. aureus* FabI Inhibitors**
  * **t-SNE of *S. aureus* FabI Inhibitors**
  * **PMI of *S. aureus* FabI Inhibitors**
  * **Activity Cliffs (ACs) of *S. aureus* FabI Inhibitors**

## **ML Models**
* **Source**: ChEMBL
* **Molecular Representations**:
  * **Pharmacological Properties**
  * **Fingerprint**:  Extended Conectivity Fingerprint (ECFP), Topological torsions, Functional Class Fingerprint (FCFP), Atompairs, Avalon, Layered, Pattern and MACCS keys (167-bits) 
* **ML Models**:  Support Vector Regressor (SVR)  (SVR), Ridge Regressor (RR) and Random Forest Regressor (RFR).
  * **Cross-Validation**
## **Focused Libraries**
* **Cumulative Distribution Function of the Designed Libraries**
* **t-SNE of the Designed Libraries**
* **PMI of the Designed Libraries**
* **Ranking of the Designed Libraries**: Comparison of ppIC<sub>50</sub> calculated by SVR, RR and RFR against similarity scores (using a Morgan fingerprint of 2048-bits).

## **Requirements**
To run the notebook, install the following dependencies:
```bash
pip install chembl-webresource-client matplotlib Python numpy seaborn molplotly kaleido scipy pillow plotly yellowbrick datamol rdkit scipy
```
## **Usage**
1. Open the Jupyter Notebooks:
2. Run the notebook cells sequentially.
3. Review results and visualization outputs.

## **License**
This project is for research purposes only. Please cite appropriately if used in publications.




