# Clustering Analysis of Contraceptive Method Choices in Indonesia

This analysis uses a subset of the 1987 National Indonesia Contraceptive Prevalence Survey, donated by Lim (1997), to identify distinct sociodemographic groups with varying degrees of contraceptive non-use.

The dataset has been clustered using several different techniques and can be further built upon using supervised learning techniques on the clusters to identify features within the clusters.

## Project Overview

I built this project to explore how unsupervised machine learning can reveal meaningful patterns in public-health behaviour. Rather than predicting contraceptive method choice directly, the analysis groups respondents by sociodemographic similarity and then interprets how contraceptive use differs across those groups.

The notebook compares clustering approaches including:

- K-Means clustering with cluster-count optimisation.
- Agglomerative hierarchical clustering using Euclidean distance.
- Hierarchical clustering using Gower distance for mixed-type feature comparison.
- Cluster interpretation using contraceptive-use distributions and demographic summaries.

## Why This Project Matters

Contraceptive access and use are shaped by more than individual preference. Education, standard of living, occupation, and family context can all affect whether people use no contraception, short-term contraception, or long-term contraception.

This project matters because clustering provides a way to surface those hidden groupings without starting from a predefined label. That makes it useful for public-health analysis: the resulting clusters can help identify which sociodemographic groups may be at greater risk of contraceptive non-use, and where policy or outreach might need to be more targeted.

The project also demonstrates how machine learning can support interpretation rather than replace it. The most important step was not simply producing clusters, but examining whether those clusters made sense in relation to standard of living, education, occupation, and contraceptive behaviour.

## Skills Learnt

- **Unsupervised machine learning:** applying K-Means and hierarchical clustering to discover structure in demographic data.
- **Model selection and evaluation:** using silhouette scores, dendrograms, and clustering metrics to compare potential cluster solutions.
- **Feature preprocessing:** standardising numerical features and preparing mixed demographic variables for clustering.
- **Exploratory data analysis:** using distributions, heatmaps, and summary statistics to understand the dataset before modelling.
- **Cluster interpretation:** translating mathematical groupings into meaningful public-health insights.
- **Research communication:** documenting both the technical process and the practical implications of the clustering results.

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

1. Create a directory called `contraceptive-method-choice` in the project root.
2. Download the dataset files (`cmc.data` and `cmc.names`) from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Contraceptive+Method+Choice).
3. Place the files in the `contraceptive-method-choice` directory.

### Running the Analysis

1. Start Jupyter Notebook:

```bash
jupyter notebook
```

2. Open the notebook file:
   - `Clustering Analysis of Sociodemographic Patterns in Contraceptive Method Choices -  A Machine Learning Approach.ipynb`

3. Run all cells in the notebook to execute the analysis.

### Expected Output

The notebook will produce:

- Data exploration visualizations.
- Clustering analysis using K-Means and Agglomerative Clustering.
- Silhouette scores and other clustering metrics.
- Dendrograms for hierarchical clustering.
- Final cluster assignments and interpretations.

## Repository Structure

| File | Purpose |
| --- | --- |
| `Clustering Analysis of Sociodemographic Patterns in Contraceptive Method Choices -  A Machine Learning Approach.ipynb` | Main notebook containing the EDA, clustering workflow, visualisations, and interpretation. |
| `Clustering Analysis Report.pdf` | Written report summarising the project methodology and findings. |
| `README.md` | Project overview and run instructions. |
