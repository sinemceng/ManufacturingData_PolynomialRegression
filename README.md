## Manufacturing Data Analysis and Quality Prediction
##### This project was developed to analyze manufacturing process data, identify the factors affecting product quality, and predict quality based on these factors.
- Additionally, a Polynomial Regression Model was built to predict product quality using production parameters.

### Dataset
https://www.kaggle.com/datasets/rukenmissonnier/manufacturing-data-for-polynomial-regression

### Project Steps
1. Data loading and cleaning
2. Correlation analysis and visualization
3. Feature selection and data standardization
4. Polynomial regression model training
5. Performance evaluation (MAE, MSE, R²)

### Key Findings
- Temperature and Material Fusion Metric were found to be the most influential factors affecting quality.
- Pressure and Temperature x Pressure interaction were removed due to high correlation.
- The Polynomial Regression (degree=2) model achieved a higher R² score than the linear model, successfully capturing the nonlinear relationships in the production process.
- Data scaling with StandardScaler improved model stability.

### Conclusion
- The model effectively revealed the relationship between manufacturing parameters and product quality.
- The results indicate that:
- Optimizing temperature control, and
  - Increasing material transformation efficiency
  - can significantly improve overall product quality.

### License
- This project is released under the Apache 2.0 License.

##### [TR]
## Üretim Verisi Analizi ve Kalite Tahmini
##### Bu proje, üretim sürecinde toplanan verileri analiz ederek ürün kalitesini etkileyen faktörleri belirlemek ve bu faktörlerle kalite tahmini yapmak amacıyla geliştirilmiştir.
- Ayrıca, üretim parametrelerine göre ürün kalitesini tahmin etmek için bir Polinomsal Regresyon Modeli oluşturulmuştur.

#### Veri Seti
https://www.kaggle.com/datasets/rukenmissonnier/manufacturing-data-for-polynomial-regression

#### Uygulama Adımları
1. Veri yükleme ve temizleme
2. Korelasyon analizi ve görselleştirme
3. Özellik seçimi ve veri standardizasyonu
4. Polinomsal regresyon modeli eğitimi
5. Performans değerlendirmesi (MAE, MSE, R²)


#### Öne Çıkan Bulgular
- Sıcaklık ve malzeme birleşme metriği, kaliteyi en fazla etkileyen değişkenlerdir.

- Basınç ve sıcaklık x basınç etkileşimi yüksek korelasyon gösterdiği için modelden çıkarılmıştır.

- Polinomsal Regresyon (degree=2) modeli, doğrusal modele göre daha yüksek R² skoruna ulaşarak üretim sürecindeki doğrusal olmayan ilişkileri başarıyla yakalamıştır.

- Verinin ölçeklenmesi (StandardScaler) modelin stabilitesini artırmıştır.

#### Sonuç
- Model, üretim parametreleriyle ürün kalitesi arasındaki ilişkiyi güçlü biçimde ortaya koymuştur.
- Elde edilen sonuçlar, üretim sürecinde:
  - Sıcaklık kontrolünün optimize edilmesinin,
  - Malzeme dönüşüm verimliliğinin artırılmasının
ürün kalitesini önemli ölçüde yükseltebileceğini göstermektedir.

#### Lisans
Bu proje Apache 2.0 Lisansı altında yayınlanmıştır.
