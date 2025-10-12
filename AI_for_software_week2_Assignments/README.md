# Crop Production Analysis in East Asia

## Project Overview
This project analyzes crop production trends in East Asia using the dataset **Production_Crops_E_Asia.csv**.  
The goal is to clean the data, explore patterns across countries and crops, and build a simple predictive model for future production.

---

## Dataset
**File name:** `Production_Crops_E_Asia.csv`

**Main columns used:**
- **Area** → China  
- **Item** → maize, potatoes, barley 
- **Year** → 1960-2030 
- **Value** → Production quantity in tonnes  

---

## Steps Completed
1. Uploaded dataset to Google Colab  
2. Cleaned the dataset (renamed columns, melted year columns into one column)  
3. Filtered crops and countries for analysis (e.g., *India Potatoes*, *China Maize*)  
4. Visualized production trends with Matplotlib  
5. Built a Linear Regression model to forecast future production  
6. Exported graphs for results  

---

## Results
- India shows steady growth in Potato production over the years.  
- China dominates Maize production and is expected to keep increasing.  
- Smaller regions like Japan show relatively stable but lower production.  

---

## Visuals
Save your charts from Colab (`File → Download → PNG`), then place them inside an **images/** folder.  
Replace the example images below with your saved file names.

Example:

![China Potatoes](images/China_potatoes.png)  
*Potato production trend in China*

![China Maize](images/China_maize.png)  
*Maize production trend in China*

![China Barley](images/China_barley.png)  
*Barley production trend in China*

---

## How to Run This Project
1. Open the Colab notebook here: [Google Colab Notebook](https://colab.research.google.com/drive/1M1GxFzMVRHZaQWGVK_SjgP0jUlmFKdY2?authuser=0#scrollTo=ibvSZVq6Vpg9)   
2. Upload the dataset file **Production_Crops_E_Asia.csv**  
3. Run all the cells to reproduce the analysis and charts  

---

## Files Included
- `Production_Crops_E_Asia.csv` → original dataset  
- `Crop_Production_Analysis.ipynb` → Colab notebook with code  
- `README.md` → project documentation  
- `images/` → folder for saved graphs  
`pitchdeck/` → folder for pitchdeck presentation
