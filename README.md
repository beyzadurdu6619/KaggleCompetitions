# 📊 Kaggle Competitions & Data Science Practice

Bu depo; Kaggle platformu üzerindeki veri analizi, veri görselleştirme ve makine öğrenimi yarışmaları/alıştırmalarına ait Jupyter Notebook (`.ipynb`) çalışmalarını içermektedir.

---

## 📌 İçindekiler

- [🛠️ Teknolojiler ve Kütüphaneler](#️-teknolojiler-ve-kütüphaneler)
- [🤖 Projeler & Model Çalışmaları](#-projeler--model-çalışmaları)
- [📚 Kaggle Egzersizleri ve Eğitimler](#-kaggle-egzersizleri-ve-eğitimler)
  - [1. Veri Analizi ve Manipülasyon (Pandas)](#1-veri-analizi-ve-manipülasyon-pandas)
  - [2. Veri Görselleştirme (Data Visualization)](#2-veri-görselleştirme-data-visualization)
  - [3. Makine Öğrenimi (Intro & Intermediate ML)](#3-makine-öğrenimi-intro--intermediate-ml)
- [🚀 Başlangıç ve Kurulum](#-başlangıç-ve-kurulum)

---

## 🛠️ Teknolojiler ve Kütüphaneler

| Alan | Kullanılan Araçlar / Kütüphaneler |
| :--- | :--- |
| **Programlama Dili** | Python 3.x |
| **Veri İşleme & Analiz** | Pandas, NumPy |
| **Veri Görselleştirme** | Matplotlib, Seaborn |
| **Makine Öğrenimi** | Scikit-Learn, XGBoost |
| **Geliştirme Ortamı** | VS Code, Jupyter Notebook |

---

## 🤖 Projeler & Model Çalışmaları

Aşağıdaki notebook'lar bağımsız veri kümesi analizleri ve tahmin modellerini içerir:

- 🚗 `carprediction.ipynb` – Araba fiyatı tahmin modeli
- 🏠 `house-prices-prediction.ipynb` / `housepriceprediction.ipynb` / `housingprice.ipynb` – Ev fiyatları tahmini (*House Prices Competition*)
- 💳 `xgboots-cc-fraud-detection-2.ipynb` / `xgboots-credit-card-fraud-detect.ipynb` – XGBoost ile Kredi Kartı Dolandırıcılığı Tespiti (*Fraud Detection*)
- 🍷 `winegradeprediction.ipynb` – Şarap kalitesi ve derecesi tahmini
- 📈 `regression.ipynb` – Regresyon modelleri uygulaması
- 🌲 `randomforest-example.ipynb` – Random Forest algoritması ile sınıflandırma/regresyon örneği

---

## 📚 Kaggle Egzersizleri ve Eğitimler

### 1. Veri Analizi ve Manipülasyon (Pandas)
- 📄 `pandas_exercise_creating_reading_and_writing.ipynb` – Veri kümesi oluşturma, okuma ve kaydetme
- 🔍 `exercise-indexing-selecting-assigning.ipynb` – İndeksleme, filtreleme ve değer atama
- 📊 `exercise-grouping-and-sorting.ipynb` – `groupby` ve sıralama işlemleri
- 🏷️ `exercise-renaming-and-combining.ipynb` – Sütun adı değiştirme ve veri birleştirme (`concat`/`join`)
- 🧹 `exercise-data-types-and-missing-values.ipynb` – Veri tipleri dönüştürme ve eksik veri yönetimi

### 2. Veri Görselleştirme (Data Visualization)
- 🎨 `datavisualizationseaborn.ipynb` & `exercise-hello-seaborn.ipynb` – Seaborn kütüphanesine giriş
- 📈 `exercise-line-charts.ipynb` – Çizgi grafikleri (*Line Charts*)
- 📊 `exercise-bar-charts-and-heatmaps.ipynb` – Çubuk grafikleri ve Isı haritaları (*Bar Charts & Heatmaps*)
- 📉 `exercise-scatter-plots.ipynb` – Dağılım grafikleri (*Scatter Plots*)
- 🌊 `exercise-distributions.ipynb` – Yoğunluk ve Dağılım grafikleri (*Histogram, KDE*)

### 3. Makine Öğrenimi (Intro & Intermediate ML)
- 🎯 `exercise-your-first-machine-learning-model.ipynb` – İlk karar ağacı modeli
- 🧪 `exercise-model-validation.ipynb` – Model doğrulama ve metrikler (MAE, RMSE vb.)
- ⚖️ `exercise-underfitting-and-overfitting.ipynb` – Eksik Öğrenme ve Aşırı Uyum Denetimi
- 🌳 `exercise-random-forests.ipynb` – Random Forest algoritması ile modelleme
- 🧩 `exercise-missing-values.ipynb` / `exercise-handling-missing-values.ipynb` – Eksik verileri doldurma yöntemleri (*Imputation*)
- 🔠 `exercise-categorical-variables.ipynb` – Kategorik Değişken İşleme (*One-Hot Encoding, Ordinal Encoding*)
- ⚙️ `exercise-pipelines.ipynb` – Sklearn `Pipeline` mimarisi kurma
- 🔄 `exercise-cross-validation.ipynb` & `crossvalidation-02102026-2.ipynb` – Çapraz Doğrulama (*Cross-Validation*)
- 📏 `exercise-scaling-and-normalization.ipynb` – Veri Ölçeklendirme ve Normalizasyon

---

## 🚀 Başlangıç ve Kurulum

Projeleri kendi lokal ortamınızda çalıştırmak için:

1. **Depoyu Klonlayın:**
   ```bash
   git clone https://github.com/kullanici-adiniz/KaggleCompetitions.git
   cd KaggleCompetitions
   ```

2. **Gerekli Kütüphaneleri Yükleyin:**
   ```bash
   pip install pandas numpy scikit-learn xgboost seaborn matplotlib jupyter
   ```

3. **Jupyter Notebook'u Çalıştırın:**
   ```bash
   jupyter notebook
   ```