## 4. Structure-Activity Similarity Map

We analyzed the presence of Active Compounds (ACs) in the *S. aureus* dataset (STADS) with 217 compounds using a Structure-Activity Similarity (SAS) map. We computed all 23,436 pairwise comparisons using the Tanimoto coefficient and Extended Connectivity Fingerprint of radius 2 (ECFP4) (2048-bits). ACs were identified using the Structure-Activity Landscape Index (SALI), defined as follows:

SALI<sub>(i,j)</sub> = |A<sub>i</sub> - A<sub>j</sub>| / (1 - sim(i,j))

where A<sub>i</sub> and A<sub>j</sub> are the activities of the ith and jth inhibitors, respectively, and sim(i,j) is the similarity between them. This script was adapted by Alberto Marbán, originally developed by Raziel Cedillo-González, Fernanda I. Saldívar-González, and Luis Rivera. The original script is available at [DIFACQUIM's GitBook on Chemoinformatics](https://difacquim.gitbook.io/quimioinformatica).

### 4.1 Highly Active Inhibitors

## Methodology
Analysis of pairwise comparisons was performed using Python 3.12.7 with the following libraries:
- **RDKit**: An open-source chemical structure curation pipeline.
- **Numpy**: Support for large, multi-dimensional arrays and matrices.
- **Pandas**: For data manipulation and organization.
- **Seaborn**: A data visualization library based on matplotlib.
- **Molplotly**: Built on RDKit, which allows 2D images of molecules to be shown in Plotly.
- **Plotly**: An interactive, open-source, and browser-based graphing library for Python.
- **Matplotlib**: A comprehensive library for creating static, animated, and interactive visualizations in Python.
- **Datamol**: An open-source toolkit that simplifies molecular processing and featurization workflows for ML scientists in drug discovery.
- **Scikit-learn**: A free and open-source machine learning library for the Python programming language.
- **Yellowbrick**: Machine learning visualization.
- **Molfeat**: An open-source hub that makes it easy for ML scientists to evaluate and implement a wide range of molecular featurizers.
- **Pillow**: Adds image processing capabilities to your Python interpreter.

## Author
Alberto Marban Gonzalez adapted this notebook from [DIFACQUIM's GitBook on Chemoinformatics](https://difacquim.gitbook.io/quimioinformatica).

## Reference
Saldivar-González, F. I., Prado-Romero, D. L., Cedillo-González, R., Chávez-Hernández, A. L., Avellaneda-Tamayo, J. F., Gómez-García, A., Juárez-Rivera, L., & Medina-Franco, J. L. (2024). A Spanish Chemoinformatics GitBook for Chemical Data Retrieval and Analysis Using Python Programming. *Journal of Chemical Education*, 101(6), 2549–2554. [DOI:10.1021/acs.jchemed.4c00041](https://doi.org/10.1021/acs.jchemed.4c00041)

