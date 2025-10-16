# Smart Transport Optimization for SDG 11 — Nairobi, Kenya

**Author:** STEPHEN ODHIAMBO

## Project Summary
This project applies K-Means clustering to urban transport and demographic data to identify city regions with similar transportation demand patterns. The goal is to support decision-making for bus stop placement, route planning, and targeted transport services — contributing to SDG 11: Sustainable Cities and Communities.

## Files
- `Smart_Transport_SDG11.ipynb` — Colab-ready notebook with synthetic example and instructions for real data.
- `SDG11_Report.pdf` — One-page project summary (findings, metrics, and ethical reflection).
- `Pitch_Deck.pptx` — Five-slide presentation for peer review.


## How to run (Colab)
1. Open the notebook `Smart_Transport_SDG11.ipynb` in Google Colab.
2. (Optional) Install dependencies in a cell: `!pip install scikit-learn pandas matplotlib seaborn geopandas folium`
3. Replace the synthetic dataset with your CSV or connect to an open-data source.
4. Run all cells and export charts as images for README/screenshots.

## Suggested datasets
- Open Data Kenya (transport datasets)
- World Bank urban population data
- Kaggle: urban mobility datasets

## Screenshots
Place screenshots of your notebook outputs (cluster scatterplot, cluster summary table, and map visualization) in a `screenshots/` folder and reference them here in the README using markdown image links:
```
![clusters](screenshots/clusters.png)
```

## Notes
Preferred framework: TensorFlow/PyTorch noted in project settings — however, the example uses scikit-learn K-Means for simplicity. If you want, I can convert the pipeline to use TensorFlow (e.g., for building autoencoders or deep clustering).
