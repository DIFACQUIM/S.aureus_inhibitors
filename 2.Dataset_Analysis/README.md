## 2. Dataset Analysis
We analyzed the chemical space of the 217 inhibitors of *S. aureus* curated in Section 1: Data Curation. The chemical space was analyzed based on fingerprints and molecular features using t-SNE and Principal Moments of Inertia (PMI) plots. t-SNE with two components was performed using the scikit-learn module to visualize the inhibitors and their potencies, employing MACCS keys (166-bit) fingerprints generated with the RDKit package in Python. A ternary plot of PMI was used to analyze molecular geometry
### 2.1 Visualization of Biological Assays of *S. aureus* Dataset (STADS)
### 2.2 t-SNE Analysis of *S. aureus* Dataset (STADS)
### 2.3 PMI Analysis of *S. aureus* Dataset (STADS)

## Methodology
Visualization of biological assays, t-SNE, and PMI plots were computed on Python 3.12.7 with the following libraries:
- **RDKit**: An open-source chemical structure curation pipeline.
- **Numpy**: Support for large, multi-dimensional arrays and matrices.
- **Pandas**: For data manipulation and organization.
- **Seaborn**: Data visualization library based on matplotlib.
- **Molplotly**: Built on RDKit which allows 2D images of molecules to be shown in Plotly.
- **Plotly**: An interactive, open-source, and browser-based graphing library for Python.
- **Matplotlib**: Comprehensive library for creating static, animated, and interactive visualizations in Python.
- **Scikit-learn**: A free and open-source machine learning library for the Python programming language.

## Author
Alberto Marban Gonzalez adapted the t-SNE notebook from [MAYA on GitHub](https://github.com/IsrC11/MAYA/tree/44661380db69df87131c8dd5315a24debe5e6020).

## Reference
- Espinoza-Castañeda, J. I., & Medina-Franco, J. L. (2025). *MAYA (Multiple ActivitY Analyzer): An Open Access Tool to Explore Structure Multiple Activity Relationships in the Chemical Universe*. Molecular Informatics, 44(2), e202400306. [https://doi.org/10.26434/chemrxiv-2024-8l14c](https://doi.org/10.26434/chemrxiv-2024-8l14c)
- Saldívar-González, F. I., Navarrete-Vázquez, G., & Medina-Franco, J. L. (2023). *Design of a multi-target focused library for antidiabetic targets using a comprehensive set of chemical transformation rules*. Frontiers in Pharmacology, 14. https://doi.org/10.3389/fphar.2023.1276444
