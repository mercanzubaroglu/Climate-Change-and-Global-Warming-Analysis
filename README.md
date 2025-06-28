# 🌍 Climate Change and Global Warming Analysis / İklim Değişikliği ve Küresel Isınma Analizi

## 📌 Project Description / Proje Açıklaması

This notebook analyzes historical temperature data to explore climate change and global warming using data science and machine learning.

Bu not defteri, veri bilimi ve makine öğrenmesi kullanarak tarihsel sıcaklık verilerini analiz eder ve iklim değişikliğini inceler.

---

## 🎯 Objectives / Amaçlar

- Track global temperature trends over years  
- Examine seasonal and regional patterns in warming  
- Use classification models to label temperature categories  
- Evaluate model performance with a classification report  

- Küresel sıcaklık eğilimlerini yıllar boyunca izlemek  
- Mevsimsel ve bölgesel ısınma desenlerini incelemek  
- Sıcaklık verilerini sınıflandırmak için modeller kullanmak  
- Model performansını sınıflandırma raporuyla değerlendirmek  

---

## 📊 Visualizations / Görselleştirmeler

The notebook includes the following visualizations:  
Notebook aşağıdaki görselleştirmeleri içerir:

- **Line Plot / Çizgi Grafiği**: Annual temperature trends for selected countries  
- **Heatmap / Isı Haritası**: Monthly average temperature across regions  
- **Bar Chart / Çubuk Grafiği**: Comparison of Hot, Cold, and Normal labels  
- **Seasonal Trends / Mevsimsel Trendler**: Temperature variation by season  

---

## 🤖 Classification Model Summary / Sınıflandırma Modeli Özeti

The model classifies temperatures into three categories:  
Model sıcaklıkları üç kategoriye ayırır:

- 🔵 **Cold / Soğuk**  
- 🟡 **Normal / Normal**  
- 🔴 **Hot / Sıcak**

Below is the classification report:  
Aşağıda sınıflandırma raporu yer almaktadır:

| Label / Etiket | Precision | Recall | F1-Score | Support |
|----------------|-----------|--------|----------|---------|
| Cold           | 0.73      | 0.79   | 0.76     | 14      |
| Hot            | 0.67      | 0.71   | 0.69     | 14      |
| Normal         | 0.75      | 0.69   | 0.72     | 26      |
| **Accuracy**   |           |        | **0.72** | **54**  |
| Macro avg      | 0.72      | 0.73   | 0.72     | 54      |
| Weighted avg   | 0.72      | 0.72   | 0.72     | 54      |

---

