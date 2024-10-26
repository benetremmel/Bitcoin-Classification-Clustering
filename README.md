# Bitcoin Classification & Clustering

## Overview
As part of our Advanced Data Analysis course, we, a team of two students, worked on a data-intensive project centered around Bitcoin (BTC) transaction analysis. Our objective was to analyze, classify, and cluster BTC transactions from large CSV files to gain insights into patterns of market activity. We explored a range of data analysis and machine learning techniques, enhancing our understanding of both supervised and unsupervised learning in the context of cryptocurrency transactions. This project provided invaluable experience working with substantial datasets, refining our data processing skills, and expanding our knowledge of clustering methodologies.

## Project Phases
The project was divided into three main phases: 1) classification of transaction types, 2) clustering to discover transaction groups, and 3) "whale watching" analysis for large BTC transactions. Each phase employed different machine learning and data analysis approaches, summarized below:

### 1. Transaction Classification
Using the K-Nearest Neighbors (KNN) algorithm, we categorized BTC transactions based on transaction type, such as:
- **Mining**
- **Gambling**
- **Exchanges**

To achieve this, we first engineered features including account balance, average monthly transaction amounts, and account age. This phase of the project allowed us to label and structure transactions, providing insights into each transaction's purpose.

### 2. Clustering Analysis
After removing labels from the dataset, we applied clustering to uncover natural groupings among transactions without prior knowledge of their categories. We employed the K-Means algorithm, used **t-SNE** for dimensionality reduction, and evaluated cluster quality with:
- **Elbow Method**
- **Silhouette Score**

This step helped validate the clusters and ensured that we captured meaningful patterns in transaction data.

### 3. Whale Watching in Cryptocurrency
In our final analysis, we conducted "whale watching" by monitoring large BTC transactions associated with high-profile market players. These "whale" transactions offer valuable insights into market trends and can signal upcoming shifts in BTC trading behaviors.

## Key Learnings
This project sharpened our data analysis and machine learning skills, especially in handling large datasets. By combining classification, clustering, and "whale" transaction analysis, we developed a robust understanding of cryptocurrency transaction dynamics.

## Repository Structure
- **data/**: Directory to store BTC transaction data files.
- **notebooks/**: Contains Jupyter notebooks documenting the analysis, classification, and clustering steps.

## Usage
### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/BTC-Classification-Clustering.git
   cd BTC-Classification-Clustering
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the BTC transaction dataset in the `data/` directory.

### Running the Notebooks
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open and run the notebooks in the `notebooks/` directory to view the implementation and results.

## About
Students who developed this project:
- Benedikt Tremmel
- Justin Sams
