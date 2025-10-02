## 2. Araç Satış Fiyatı Tahmini Projesi README İçeriği

Bu README, regresyon modeli odaklı bir proje için hazırlanmıştır.

```markdown
# 🚗 Araç Satış Fiyatı Tahmini (Automobile Sale Price Prediction)

Bu proje, kapsamlı bir araç satış veri setini kullanarak, bir aracın özelliklerine (tür,boyut,liste fiyatı,satış fiyatı vb.) dayanarak piyasa satış fiyatını tahmin eden bir regresyon modeli geliştirmeyi amaçlar.

## 🎯 Proje Amacı

Temel amaç, müşteri özelliklerini ve ürün niteliklerini (boyut, satış fiyatı, liste fiyatı, satış sıklığı) kullanarak anlamlı gruplar (kümeler) oluşturmak ve bu kümeler üzerinden her bir müşteri grubuna en uygun araç türlerini önerecek bir makine öğrenmesi modelinin altyapısını kurmaktır.

## ✨ Temel Özellikler ve Aşamalar

- **Veri Ön İşleme:** Eksik değerlerin yönetilmesi, kategorik özelliklerin (araç türü gibi) sayısal hale getirilmesi.
- **Özellik Ölçeklendirme:** Kümeleme performansını artırmak için sayısal özelliklerin ölçeklendirilmesi (Standard Scaler, MinMax Scaler).
- **Müşteri Alışkanlıkları Analizi:** Müşterilerin sipariş sıklığı, tercih ettiği fiyat aralığı ve araç türleri gibi alışkanlıkların çıkarılması.
- **Kümeleme Modeli (K-Means):** Farklı araç türleri ve müşteri grupları arasında doğal gruplar oluşturmak için K-Means algoritmasının kullanılması.
- **Optimum Küme Sayısı (Elbow Metodu):** Veri setine en uygun küme sayısının belirlenmesi.


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
