# World Development Clusters - Streamlit app

## 1. Create the files (once)
Run **all cells** of `Cluster_Analysis_EDA_Final_Complete.ipynb`.
It saves these files in the notebook's folder:
`scaler.pkl`, `pca.pkl`, `kmeans.pkl`, `gmm.pkl`, `dbscan.pkl`, `agglo.pkl`, `app_info.pkl`, `country_results.csv`

## 2. Put everything in one folder
```
final_project\
├── app.py
├── requirements.txt
├── scaler.pkl
├── pca.pkl
├── kmeans.pkl
├── gmm.pkl
├── app_info.pkl
└── country_results.csv
```
(`dbscan.pkl` and `agglo.pkl` are not needed by the app.)

## 3. Run
```
pip install -r requirements.txt
streamlit run app.py
```

## 4. Before presenting
Open `app.py` and fill in `CLUSTER_NAMES` (near the top) with a friendly name for each cluster number.
