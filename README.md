Otel Fiyat Tahmin Modeli

Bu proje, farklı şehirlerdeki otellerin özelliklerine göre fiyat tahmini yapan bir regresyon modeli içerir.

📌 Veri Seti

Veri setinde aşağıdaki sütunlar bulunmaktadır:

Özellik	Açıklama
otel_yildizi	Otelin yıldız sayısı (1–5 arası)
sehir	Otelin bulunduğu şehir (İzmir, Bodrum, Antalya, İstanbul vb.)
oda_sayisi	Oteldeki toplam oda sayısı
denize_yakinlik	Otelin denize uzaklığı (km cinsinden)
mevsim	Konaklama mevsimi (Yaz, Kış, Bahar, Sonbahar)
ortalama_puan	Kullanıcıların verdiği ortalama puan (1–10)
fiyat	Hedef değişken: gecelik fiyat (₺)
🛠 Kullanılan Teknolojiler

Python

pandas → Veri işleme

scikit-learn → OneHotEncoder, LinearRegression, Pipeline

train_test_split → Eğitim ve test verisinin ayrılması
