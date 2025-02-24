## 6. Analysis of Designed Libraries (INDDS, DIADS, and PYRDS)

We analyzed the chemical space of the curated designed libraries (INDDS, DIADS, and PYRDS). Compound diversity was assessed by comparing the cumulative distribution functions (CDFs). The chemical space was analyzed based on fingerprints and molecular features using t-SNE and Principal Moments of Inertia (PMI) plots. t-SNE of two components was performed using the scikit-learn module to visualize the inhibitors and their potencies, using MACCS keys (166-bits) fingerprints generated with the RDKit package in Python. A ternary plot of PMI was used to analyze molecular geometry.

### 6.1 Cumulative Distribution Function of Designed Libraries (INDDS, DIADS, and PYRDS)
### 6.2 t-SNE Analysis of Designed Libraries (INDDS, DIADS, and PYRDS)
### 6.3 PMI Analysis of Designed Libraries (INDDS, DIADS, and PYRDS)

## Methodology
Visualization of CDF, t-SNE, and PMI plots were computed on Python 3.12.7 with the following libraries:
- **RDKit**: An open-source chemical structure curation pipeline.
- **Numpy**: Supports large, multi-dimensional arrays and matrices.
- **Pandas**: For data manipulation and organization.
- **Seaborn**: A data visualization library based on matplotlib.
- **Molplotly**: Built on RDKit, which allows 2D images of molecules to be shown in Plotly.
- **Plotly**: An interactive, open-source, and browser-based graphing library for Python.
- **Matplotlib**: A comprehensive library for creating static, animated, and interactive visualizations in Python.
- **Scikit-learn**: A free and open-source machine learning library for the Python programming language.

## Author
Alberto Marban Gonzalez adapted the cumulative similarity distribution and t-SNE notebooks from [this article](https://doi.org/10.1021/acsomega.3c04566) and [MAYA on GitHub](https://github.com/IsrC11/MAYA/tree/44661380db69df87131c8dd5315a24debe5e6020), respectively.

## References
- Espinoza-Castañeda, J. I., & Medina-Franco, J. L. (2025). *MAYA (Multiple ActivitY Analyzer): An Open Access Tool to Explore Structure Multiple Activity Relationships in the Chemical Universe*. Molecular Informatics, 44(2), e202400306. [https://doi.org/10.26434/chemrxiv-2024-8l14c](https://doi.org/10.26434/chemrxiv-2024-8l14c)
- Cedillo-González, R., & Medina-Franco, J. L. (2023). *Diversity and Chemical Space Characterization of Inhibitors of the Epigenetic Target G9a: A Chemoinformatics Approach*. ACS Omega, 8(33), 30694–30704. [https://doi.org/10.1021/acsomega.3c04566](https://doi.org/10.1021/acsomega.3c04566)
- Saldívar-González, F. I., Navarrete-Vázquez, G., & Medina-Franco, J. L. (2023). *Design of a multi-target focused library for antidiabetic targets using a comprehensive set of chemical transformation rules*. Frontiers in Pharmacology, 14. https://doi.org/10.3389/fphar.2023.1276444
