<h1 style='background:#007fff;border:0; color:white;
box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.25);
    transform: rotateX(10deg); border-radius: 25px;
    '><center>
    CSE-4250: Data Mining and Warehousing Sessional (Syllabus: V2)</center>
</h1>


Welcome to the official laboratory repository for the **CSE 4250: Data Mining and Warehousing Sessional (Syllabus: V2)** course at the **Bangladesh Army University of Engineering and Technology (BAUET)**. This repository serves as a structured collection of all lab sessions, source datasets, interactive notebooks, and practical models curated for students to master data preprocessing, mining techniques, and machine learning architectures.

---

## 📋 Repository Structure & Catalog

The repository is organized sequentially, pairing notebooks with raw data templates to build data pipeline architectures from the ground up.

### 🔹 Phase 1: Foundational Data Handling & Operations
*   **`Lab01_Basic_Building_Blocks_in_Python`**
    *   `Lab01-Introduction_to_python.ipynb` : Core syntax, loops, flows, and basic data structures.
    *   `data_matrix.csv` / `data_matrix.npy` : Target datasets for structural manipulation.
    *   `Python-Cheatsheet.jpg` : Desktop environment quick-reference syntax guide.
*   **`Lab02_Python_libraries_Numpy_Pandas_Matplotlib`**
    *   `Lab02-Introduction_to_Numpy,_Pandas_and_matplotlib.ipynb` : Core framework integrations.
    *   `pandas_indexing_selection_cheatsheet.ipynb` : Deep-dive reference for filtering structural frames.
*   **`Lab03_Explore_various_aspects_of_data_manipulation`**
    *   `Lab03_Understanding_Data_Univariate_data_analysis.ipynb` : Summary statistics and data distribution behavior.
    *   `data_profiling_gui.ipynb` : Interactive exploration interfaces.
    *   *Datasets:* `brain_size.csv`, `iris.csv`, `pima-indians-diabetes.csv`.

### 🔹 Phase 2: Data Visualization & Exploratory Analysis (EDA)
*   **`Lab04_Data_Visualization_in_Python`**
    *   `Lab04_Updated_Data_Visualization_with_Python_Matplotlib.ipynb` : Building production charts.
    *   `multivariate_seaborn_fixed.ipynb` : Advanced multi-dimensional relational arrays and distributions.
    *   `example_plot.png` : Render outputs.

### 🔹 Phase 3: Advanced Data Preprocessing & Cleaning
*   **`Lab05_Imputation_Scaling_Encoding`**
    *   `Sessional05_Imputation_Scaling_Encoding.ipynb` : Standard missing value pipelines.
    *   `Sessional-09_imputer_encoding_scaling_DataPreprocessing.ipynb` : Feature transformations.
    *   `dropna_filna_ffill_bfill.ipynb` : Direct cell cleansing and forward/backward structural alignment.
    *   *Datasets:* `df1.csv`.
*   **`Lab06_Identification_and_Removal_of_Outliers`**
    *   `Lab06_outlier_detection_handling_notebook.ipynb` : Statistical screening using IQR and Z-Scores.
    *   `Lab_6_Feature Selection & Removing Outliers.ipynb` : Managing dirty data points.

### 🔹 Phase 4: Feature Engineering & Dimensionality Reduction
*   **`Lab07_Creating_Dataset_and_feature_Engineering`**
    *   `Lab-6-Hands-On-Data-Analysis.ipynb` : Real-world transformations and target mapping.
    *   *Datasets:* `Random_Dataset.csv`, `Random_Dataset.xlsx`.
*   **`Lab08_Data_Dimension_Reduction_Techniques`**
    *   Advanced labs exploring dataset compression via Principal Component Analysis (PCA) and Singular Value Decomposition (SVD).

### 🔹 Phase 5: Machine Learning Models & Analytical Frameworks
*   **`Lab09_Clustering`** : Unsupervised grouping models (K-Means, Hierarchical).
*   **`Lab10-Classification`** : Supervised class predictive frameworks.
*   **`Lab11_Performance_metrics`** : Matrices, ROC-AUC, precision-recall optimization profiles.

---

## 🔬 Core Capstone Sandbox
*   **`Classification_26_ML_Models_Comparison_ExplainableAI_Tanvir.ipynb`**
    *   An extensive analytical playground benchmarking 26 distinct Machine Learning classification architectures.
    *   Includes complete model evaluation structures paired with **Explainable AI (XAI)** frameworks (`SHAP`, `LIME`) to demystify complex model logic, feature importances, and decision pathways.

---

## 💻 Installation & Setup Instruction

To get these lab environments running locally on your workstation, follow these steps:

### 1. Clone the Workspace
```bash
git clone https://github.com/tanvirsweb/Data_Mining_and_WareHousing_CSE4250_BAUET.git
cd Data_Mining_and_WareHousing_CSE4250_BAUET
```

### 2. Configure Environment & Dependencies
It is highly recommended to deploy these inside an isolated sandbox environment (such as `venv` or `conda`). First, create and activate your environment:

```bash
# Create a native Python virtual environment
python -m venv cse4250_env

# Activate the environment
# On Linux/macOS:
source cse4250_env/bin/activate  
# On Windows:
cse4250_env\Scripts\activate
```

Next, install the dependencies using one of the following methods:

#### Option A: Quick Setup via Environment File (Recommended)
If you want to ensure matching package version configurations across platforms (Anaconda, Kaggle, Colab, or local), restore the exact setup file:
```bash
pip install -r environmentsetup.txt
```

#### Option B: Manual Installation
Alternatively, you can manually pull the latest versions of the required frameworks:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn shap lime jupyter openpyxl
```

### 3. Open the Labs
Launch your local workspace runner tool to browse through individual packages:
```bash
jupyter notebook
```

---

## ⚙️ Prerequisites & Tools Used
*   **Language Environment:** Python 3.8+
*   **Core Packages:** `NumPy`, `Pandas`, `SciPy`, `openpyxl`
*   **Visual Elements:** `Matplotlib`, `Seaborn`
*   **Mining & ML Engine:** `Scikit-Learn`
*   **Exploded Interpretability:** Frameworks for Explainable AI (e.g., `SHAP`, `LIME`)

---

## 👤 Course Instruction & Mentorship

**Tanvir Anjom Siddique**  
Lecturer, Department of Computer Science and Engineering (CSE)  
Bangladesh Army University of Engineering and Technology (BAUET)  
Portfolio: [https://tanvirsweb.github.io](https://tanvirsweb.github.io)  
Date: 14/10/2026

---

<h2 style='background:#007fff;border:0; color:white;
box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.25);
    transform: rotateX(10deg); border-radius: 25px;
    '><center>
    Happy Mining! May your features always be significant and your distributions clean.
    </center>
</h2>
