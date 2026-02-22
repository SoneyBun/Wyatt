<!-- Header -->
<div align="center">
  <img width="2000" height="500" alt="WyattAIBanner" src="https://github.com/user-attachments/assets/df7cd353-54f1-4ba1-8d8d-6c41572f4cd3" />
  <h3>House Pricing AI Model</h3>
</div>

<!-- Links -->
<div align="center">
  <a href="./Datasets" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/Datasets-wyatt?style=for-the-badge&logo=github&logoColor=%2300b7ff&color=%23ffffff"></a>
  <a href="./wyatt.ipynb" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/wyatt.ipynb-wyatt?style=for-the-badge&logo=google%20colab&logoColor=%2300b7ff&color=%23ffffff"></a>
</div>

<!-- Divider -->
---

## Implementation

>[!TIP]
>Wyatt AI has been developed to use general features instead of overly-specific ones. If a certain feature is missing, input a reasonable estimate.

 ```py
# Instructions
# Input your house features into the last segment of the Jupyter Notebook

sample = pd.DataFrame({
    "Square_Feet": [2700],
    "Bedrooms": [5],
    "Bathrooms": [4],
    "Year_Built": [2018],
    "Lot_Size": [0.49],
    "Garage": [2]
})

# Printing
predicted_price = model.predict(sample)
print(f"\nPredicted Price for Sample House: ${predicted_price[0]:,.2f}")
```
