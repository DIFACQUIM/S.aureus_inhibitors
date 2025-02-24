## 5.1 Machine Learning Models
The next notebooks were used to construct machine learning (ML) models. For this purpose, molecular properties, topological, and constitutional descriptors were calculated using Molfeat. Shape descriptors: Molecular Shape Index, Molecular Flexibility, and Molecular Complexity were determined using DataWarrior v06.02.05. Shape descriptors were added to each dataframe. Molecular fingerprints were calculated with MolFeat, but only Extended Connectivity Fingerprint (ECFP4) of radius = 2 and length of 2048 bits is shown in the scripts. The fingerprints like Topological torsions, Functional Class Fingerprint (FCFP), Atompairs, Avalon, Layered, Pattern, and MACCS keys of 167-bits can be calculated with Molfeat library. Redundant features were identified through Pearson correlation analysis. The regressors used in the notebooks were Support Vector Regressor (SVR), Ridge linear Regressor (RR), and Random Forest Regressor (RFR) using Scikit-Learn library. These ML regressors were employed to calculate the predicted pIC<sub>50</sub> (ppIC<sub>50</sub>). The libraries (INDDS, DIADS, and PYRDS) with descriptors can be requested to the author contact.

Some scripts (notebooks 5.1 and 5.3) were adapted from Patrick Walters Github https://github.com/PatWalters/practical_cheminformatics_tutorials

### 5.1 Descriptor and Fingerprint Calculations with Molfeat (the same script was used in *S. aureus* dataset).
### 5.2 Identification of Redundant Features.
### 5.3 Training SVR Model External Validation Using *S. aureus* Dataset
Cross-validation and error metrics calculations. In this same notebook, the ppIC<sub>50</sub> was calculated for the designed libraries (INDDS, DIADS, and PYRDS) obtained from transformation rules (calculations computed in MOE 2024).

### 5.4 Training RR Model External Validation Using *S. aureus* Dataset
Cross-validation and error metrics calculations. In this same notebook, the ppIC<sub>50</sub> was calculated for the designed libraries (INDDS, DIADS, and PYRDS) obtained from transformation rules (calculations computed in MOE 2024).

### 5.5 Training RFR Model External Validation Using *S. aureus* Dataset
Cross-validation and error metrics calculations. In this same notebook, the ppIC<sub>50</sub> was calculated for the designed libraries (INDDS, DIADS, and PYRDS) obtained from transformation rules (calculations computed in MOE 2024).

### pIC<sub>50</sub> from Designed Libraries
The libraries (INDDS, DIADS, and PYRDS) with descriptors can be requested to the author contact.
Contact: alberto.marban.glez90@gmail.com

## Methodology
The descriptor and fingerprint calculations, identification of redundant features, and ppIC50 calculations were computed on Python 3.12.7 with the following libraries:
- **RDKit**: An open-source chemical structure curation pipeline.
- **Numpy**: Support for large, multi-dimensional arrays and matrices.
- **Pandas**: For data manipulation and organization.
- **Seaborn**: Data visualization library based on matplotlib.
- **Molplotly**: Built on RDKit which allows 2D images of molecules to be shown in Plotly.
- **Plotly**: An interactive, open-source, and browser-based graphing library for Python.
- **Matplotlib**: Comprehensive library for creating static, animated, and interactive visualizations in Python.
- **Datamol**: An open-source toolkit that simplifies molecular processing and featurization workflows for ML scientists in drug discovery.
- **Scikit-learn**: A free and open-source machine learning library for the Python programming language.
- **Yellowbrick**: Machine learning visualization.
- **Molfeat**: An open-source hub that makes it easy for ML scientists to evaluate and implement a wide range of molecular featurizers.
- **Pillow**: The Python Imaging Library adds image processing capabilities to your Python interpreter.

## Author
Alberto Marban Gonzalez adapted descriptor calculations with MolFeat and reviewed machine learning models examples from [Patrick Walters' Practical Cheminformatics Tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials).

## Reference
Walters, P. Practical Cheminformatics with Open Source Software. [https://github.com/PatWalters/practical_cheminformatics_tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials)

