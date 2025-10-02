## 2. İkinci El Araba Satış Fiyatı Tahmini Projesi README İçeriği

Bu README, regresyon modeli odaklı bir proje için hazırlanmıştır.

```markdown
# 🚗 İkinci El Araba Satış Fiyatı Tahmini (Car Sale Price Prediction)

Bu proje, kapsamlı bir ikinci el araba satış veri setini kullanarak, bir aracın özelliklerine (marka, model, yıl, kilometre, motor gücü vb.) dayanarak piyasa satış fiyatını tahmin eden bir regresyon modeli geliştirmeyi amaçlar.

## 🎯 Proje Amacı

Veri setindeki kategorik ve sayısal özellikleri işleyerek, regresyon algoritmaları (örneğin Lineer Regresyon, Random Forest Regressor) yardımıyla ikinci el araçların fiyatlarını mümkün olan en düşük hata payıyla tahmin etmektir.

## ✨ Temel Özellikler ve Aşamalar

- **Veri Temizleme:** Aykırı değerlerin (outliers) ve eksik verilerin tespiti ve yönetimi.
- **Kategorik Veri İşleme:** One-Hot Encoding veya Label Encoding gibi yöntemlerle marka, model, yakıt tipi gibi kategorik değişkenlerin makine öğrenimine hazır hale getirilmesi.
- **Korelasyon Analizi:** Fiyatı en çok etkileyen özelliklerin belirlenmesi.
- **Regresyon Modeli Seçimi:** Fiyat tahmininde en iyi performansı veren modelin seçilmesi ve hiperparametre optimizasyonu.
- **Model Değerlendirmesi:** Ortalama Mutlak Hata (MAE), Ortalama Kare Hata (MSE) ve R-Kare (R²) skorları ile model başarısının ölçülmesi.

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

Bu projenin çalışması için gerekli olan Python kütüphaneleri:

- **Python** (Tercihen 3.8+)
- **Pandas:** Veri çerçeveleri ile çalışmak için.
- **Numpy:** Yüksek performanslı dizi ve matris işlemleri için.
- **Matplotlib / Seaborn:** Veri görselleştirme (özellikle dağılım grafikleri) için.
- **Scikit-learn:** Regresyon modelleri ve veri ön işleme araçları için.

### Kurulum

Aşağıdaki komutu kullanarak gerekli kütüphaneleri tek seferde kurabilirsiniz:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
