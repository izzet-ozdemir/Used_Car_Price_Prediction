
# 🚗 Used Car Price Prediction

![Project Badge](https://img.shields.io/badge/Project-Used%20Car%20Price%20Prediction-blue?style=flat-square)



## 📌 Proje Özeti

Bu projenin amacı, Craigslist üzerinde listelenen ikinci el araçların fiyatlarını çeşitli makine öğrenmesi regresyon modelleri kullanarak tahmin etmektir. Veri seti; marka, model, üretim yılı, kilometre gibi birçok özelliği içermektedir. Amaç, alıcı ve satıcılara daha doğru fiyat tahminleri sunarak karar verme süreçlerine katkı sağlamaktır.

## 🧠 Model Değerlendirmesi

| Model               | MAE    | RMSE   | R²     |
|---------------------|--------|--------|--------|
| Ridge Regression    | 0.582  | 1.038  | 0.278  |
| Random Forest       | 0.333  | 0.714  | 0.659  |
| Gradient Boosting   | 0.426  | 0.875  | 0.488  |


## 🔍 Model Yorumları:
- **Ridge Regression**: Doğrusal bir model olduğu için verideki karmaşık örüntüleri yakalayamadı ve hata oranları yüksek kaldı.

- **Random Forest**: En düşük MAE ve RMSE değerlerinin yanı sıra en yüksek R² skoru ile diğer modellere göre açık ara daha iyi performans gösterdi.

- **Gradient Boosting**: Etkili bir model olmasına rağmen, bu veri setinde Random Forest kadar başarılı olamadı ve orta düzeyde bir performans sergiledi.

## 📌 Linkler:

- Veri Seti : https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data
- Notebook Dosyası : https://www.kaggle.com/code/iozdemir/used-car-price-prediction-with-machine-learning


/* ------------------------------------------------------------------------------------------------------------- */


## 📌 Project Overview

This project aims to predict the prices of used cars listed on Craigslist using various machine learning regression models. The dataset includes features such as make, model, year, mileage, and more. The goal is to provide accurate price predictions to assist buyers and sellers in making informed decisions.

## 🧠 Models Evaluated

| Model               | MAE    | RMSE   | R²     |
|---------------------|--------|--------|--------|
| Ridge Regression    | 0.582  | 1.038  | 0.278  |
| Random Forest       | 0.333  | 0.714  | 0.659  |
| Gradient Boosting   | 0.426  | 0.875  | 0.488  |

### 🔍 Model Insights:

- **Ridge Regression**: As a linear model, it struggled to capture complex patterns in the data, resulting in higher error metrics.
- **Random Forest**: Outperformed other models with the lowest MAE and RMSE, and the highest R² score, indicating its effectiveness in predicting car prices.
- **Gradient Boosting**: While effective, it did not surpass Random Forest in this dataset, showing moderate performance.

## 📌 Links:

- Database : https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data
- Notebook File : https://www.kaggle.com/code/iozdemir/used-car-price-prediction-with-machine-learning


