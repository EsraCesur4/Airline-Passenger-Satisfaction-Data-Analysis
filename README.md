# 🧳 Airline Passenger Satisfaction Data Analysis

![## 🔍 7  Örnek Tahminler (Sample Predictions) Modelin gerçek hayattaki tahmin gücünü göstermek amacıyla test setinden rastgele seçilen öğrenciler için tahminler yapılmıştır  Öğrenci  Gerçek Değer  (2)](https://github.com/user-attachments/assets/65984ab6-ee40-40e7-89bf-328f76f54c54)

Bu proje, uçak yolcularının memnuniyetini etkileyen faktörleri incelemek ve memnuniyet düzeyini tahmin etmeye yönelik bir veri bilimi çalışmasıdır. Veri seti, yolcuların uçuş deneyimlerine ilişkin çeşitli kategorik ve sayısal özellikleri içermektedir.

## 1. Veri Seti Hakkında

Veri seti, yolcu tipi, sadakat durumu, seyahat sınıfı, yaş, uçuş süresi, çeşitli hizmet değerlendirmeleri (check-in, eğlence, yemek vb.) ve uçuş gecikmeleri gibi değişkenleri içermektedir. Hedef değişken `satisfaction` olup, memnun (`satisfied`) ya da memnun değil (`neutral or dissatisfied`) şeklinde iki kategoriye ayrılmıştır.

## 2. Veri Ön İşleme

- `Unnamed: 0` ve `id` gibi analiz açısından anlam ifade etmeyen sütunlar kaldırılmıştır.
- Eksik veriler analiz edilerek silme ve atama (imputation) yöntemleriyle uygun şekilde işlenmiştir.
- Sayısal sütunlar için istatistiksel özetler çıkarılmış, aykırı değerler görselleştirme ile analiz edilmiştir.

## 3. Görselleştirmeler

- Kategorik ve sayısal sütunlar için dağılım grafikleri
- Hizmet türlerine göre memnuniyet oranlarının bar grafikleri
- Gecikme ve memnuniyet ilişkisi
- Uçuş süresi ve yaş gibi değişkenlerin etkileri

## 4. Sonuçlar ve Yorumlar

- Hangi faktörlerin memnuniyeti en çok etkilediği analiz edilmiştir.
- Elde edilen sonuçlara göre uçuş şirketleri için iyileştirme önerileri sunulmuştur.

## 📁 Notebook

Tüm analiz süreci detaylı ve açıklamalı olarak `airline-passenger-satisfaction-bitirme-projesi-1.ipynb` dosyasında yer almaktadır.
