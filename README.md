# 🎵 Music Recommendation System

This repository contains a Music Recommendation System implemented with Jupyter Notebooks and Python. The notebooks explore music data, preprocess features, train recommendation models, and provide example inference to generate personalized song recommendations.

## Contents
- notebooks/
  - EDA_and_Preprocessing.ipynb  — exploratory data analysis and preprocessing
  - Modeling.ipynb               — model training, tuning, and evaluation
  - Inference_and_Examples.ipynb — inference examples and usage
- data/                          — datasets (not included)
- models/                        — saved model artifacts (if any)

## Key features
- Data exploration and visualization (pandas, matplotlib, seaborn)
- Preprocessing pipelines for user and track features
- Baseline and matrix-factorization recommendation approaches
- Evaluation with ranking metrics (Precision@K, Recall@K, NDCG)
- Example inference notebook showing how to get recommendations

## Quickstart
1. Clone the repo:

   git clone https://github.com/Thisara-Anjana/Music_Recommendation_System.git
   cd Music_Recommendation_System

2. Create and activate a Python environment, then install dependencies:

   python -m venv venv
   source venv/bin/activate  # macOS / Linux
   venv\Scripts\activate    # Windows
   pip install -r requirements.txt

3. Place your dataset files in the `data/` directory or update notebook paths.
4. Open the notebooks in JupyterLab/Notebook and run them in order.

## Notes on data
- Datasets are not included in the repository. Add your CSVs or dataset downloads to `data/`.
- If you used the Spotify API, Million Song Dataset, or other sources, include attribution and license details in this section.

## Requirements
- Python 3.8+
- Jupyter
- pandas, numpy, scikit-learn, scipy, matplotlib, seaborn
- Optional (if used): surprise, lightfm, librosa, streamlit

## Results & Next steps
- Summarize main results and best-performing model in the `Results & Findings` section of the README or the notebooks.
- Next steps: expand feature engineering, add audio features, build a small web demo (Streamlit / FastAPI).

