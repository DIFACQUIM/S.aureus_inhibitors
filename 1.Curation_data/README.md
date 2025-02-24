## 1. Curation data
In these notebooks, the FabI inhibitors were retrieved from the ChEMBL database. Analysis of Assays descriptions were grouped by `molecule_chembl_id` and manually reviewed in ChEMBL to search for inconsistencies between IC$_{50}$ values. 

### 1.1 ChEMBL Data FabI Retrieval
### 1.2 Separation by Standard Units and Experiment Type
### 1.3 *S. aureus* dataset (STADS) Curation

## Methodology
ChEMBL retrieval, data visualization, and data curation were computed on Python 3.12.7 with the following libraries:
- **ChEMBL webresource client**: Helps accessing ChEMBL data and cheminformatics.
- **Pandas**: For data manipulation and organization.
- **RDKit**: An open-source chemical structure curation pipeline.

## Author
Alberto Marban Gonzalez adapted the curated section from [DIFACQUIM GitBook on Chemoinformatics](https://difacquim.gitbook.io/quimioinformatica).

## Reference
Saldivar-González, F. I., Prado-Romero, D. L., Cedillo-González, R., Chávez-Hernández, A. L., Avellaneda-Tamayo, J. F., Gómez-García, A., Juárez-Rivera, L., & Medina-Franco, J. L. (2024). A Spanish Chemoinformatics GitBook for Chemical Data Retrieval and Analysis Using Python Programming. *Journal of Chemical Education*, 101(6), 2549–2554. [https://doi.org/10.1021/acs.jchemed.4c00041](https://doi.org/10.1021/acs.jchemed.4c00041)
