# Clustering-Analysis-of-Contraceptive-Method-Choices-in-Indonesia
This analysis uses a subset of the 1987 National Indonesia Contraceptive Prevalence Survey donated by Lim (1997) to identify distinct sociodemographic groups with varying degrees of contraceptive non-use.

The dataset has been clustered using several different techniques and can be further built upon using supervised learning techniques on the clusters to identify features within the clusters.

## How to Run

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
```bash
git clone https://github.com/JBourton/Clustering-Analysis-of-Contraceptive-Method-Choices-in-Indonesia.git
cd Clustering-Analysis-of-Contraceptive-Method-Choices-in-Indonesia
```

2. Install required Python packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

### Data Setup

The analysis requires the Contraceptive Method Choice dataset. You'll need to:

1. Create a directory called `contraceptive-method-choice` in the project root
2. Download the dataset files (`cmc.data` and `cmc.names`) from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Contraceptive+Method+Choice)
3. Place the files in the `contraceptive-method-choice` directory

### Running the Analysis

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open the notebook file:
   - `Clustering Analysis of Sociodemographic Patterns in Contraceptive Method Choices -  A Machine Learning Approach.ipynb`

3. Run all cells in the notebook to execute the analysis

### Expected Output

The notebook will produce:
- Data exploration visualizations
- Clustering analysis using K-Means and Agglomerative Clustering
- Silhouette scores and other clustering metrics
- Dendrograms for hierarchical clustering
- Final cluster assignments and interpretations
