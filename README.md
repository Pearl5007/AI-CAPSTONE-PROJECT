# AI-CAPSTONE-PROJECT

This project uses machine learning to classify breast cancer dataset.

## How to Run

1. Open the notebook: `ai_webiste_updated.ipynb`
2. Click on open in colab
3. Run all cells in Google Colab
4. After running it at the end you will get the training accuracy and testing accuracy
5. At the complete end you will see a link starting with https, click on that, it will redirect you to the BREAST CANCER DETECTION Website
6. In the website enter the required fields and click on predict to get the output

## Loading the Dataset
```python
import pandas as pd
df = pd.read_csv("wisc_bc_data.csv")

