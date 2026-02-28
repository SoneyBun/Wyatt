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

>[!IMPORTANT]
> To run a Google Colab, you must be signed in with a Google account. For more information, view [stackoverflow](https://stackoverflow.com/questions/57561823/does-it-require-eveyone-to-have-a-gmail-account-to-run-a-colab-notebook#:~:text=Users%20can%20view%20notebooks%20shared%20publicly%20without%20sign-in.%20In&text=Do%20I%20have%20to%20install%20packages%20needed%20each%20time%20when%20I%20start%20Google%20Colab?).

Select <a href="https://colab.research.google.com/github/SoneyBun/Wyatt/blob/main/wyatt.ipynb\" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/Open%20in%20Colab-%20?style=plastic&logo=Google%20Colab&labelColor=%23606060&color=%231384c5"></a> and then upload the following datasets found <a href="./Datasets" target="_blank">here</a>:
- AmesHousing.csv
- Virginia_Housing.csv

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
<!-- Divider -->
---

<div align="center">Independence DSAI 2526</div>
