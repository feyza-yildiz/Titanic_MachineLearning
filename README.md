# Titanic_MachineLearning
Titanic Veri Seti - Makine Öğrenmesi Projesi

Proje sahipleri : Muhammed Fatih Toprak-Feyza Yıldız 

Bu projede Titanic veri seti üzerinde gözetimli ve gözetimsiz öğrenme teknikleri uygulanmıştır. Projenin amacı, makine öğrenmesi tekniklerini kullanarak Titanic yolcularının hayatta kalıp kalmadığını tahmin etmek ve veri içindeki gizli kalıpları keşfetmektir.
Projenin kaggle linki : https://www.kaggle.com/code/feyzayildiz/titanic-ml


Veri Seti Seçimi:
Bu projede kullanılan veri seti, Kaggle platformundan temin edilen Titanic veri setidir: /kaggle/input/titanic-huge-dataset-1m-passengers. Veri seti, Titanic gemisindeki 1 milyon yolcu hakkında bilgiler içermektedir.



Proje Yapısı
1. Veri Yükleme ve İnceleme:
Veri seti yüklenmiş ve eksik veriler ile genel özellikler incelenmiştir.

3. Veri Görselleştirme:
Yaş dağılımı ve cinsiyete göre hayatta kalma durumu gibi önemli veriler görselleştirilmiştir.

5. Veri Ön İşleme:
Eksik veriler doldurulmuş, kategorik değişkenler sayısal değerlere dönüştürülmüş ve gereksiz sütunlar çıkarılmıştır.

7. Gözetimli Öğrenme:
Bu projede gözetimli öğrenme yöntemi olarak lojistik regresyon kullanılarak, yolcuların hayatta kalma durumlarını tahmin etmek amaçlanmıştır.

  a. Lojistik Regresyon (Logistic Regression)
Lojistik regresyon, sınıflandırma problemleri için yaygın olarak kullanılan bir gözetimli öğrenme algoritmasıdır. Bu projede, Titanic yolcularının hayatta kalma olasılıklarını tahmin etmek için kullanılmıştır.
Veri seti eğitim ve test olarak bölünmüştür.
Model, eğitim verileri ile eğitilmiş ve test verileri ile doğrulama yapılmıştır.
Model Doğruluğu: %65.35
Performans metrikleri olarak doğruluk skoru, karışıklık matrisi, kesinlik, duyarlılık ve F1 skoru gibi metrikler hesaplanmıştır.

5. Gözetimsiz Öğrenme
Gözetimsiz öğrenme yöntemlerinden K-Means Kümeleme algoritması kullanılarak yolcuların belirli özelliklerine göre gruplandırılması yapılmıştır.

  a. K-Means Kümeleme (K-Means Clustering)
K-Means algoritması, verileri belirli sayıda kümeye ayırarak veri içindeki gizli kalıpları ortaya çıkarmayı amaçlar. Bu projede, yolcuların özelliklerine göre 2 kümeleme yapılmıştır.
PCA (Principal Component Analysis) yöntemi ile boyut indirgeme yapılarak verilerin iki boyutta görselleştirilmesi sağlanmıştır.
Kümeleme sonuçları görsel olarak analiz edilmiştir.

6. Model Değerlendirme
Gözetimli öğrenme modelleri doğruluk, kesinlik, duyarlılık ve F1 skoru gibi performans metrikleri ile değerlendirilmiştir.
Gözetimsiz öğrenme modeli ise kümeleme sonuçlarının görselleştirilmesi ile incelenmiştir.

Kullanılan Kütüphaneler
pandas
numpy
matplotlib
seaborn
scikit-learn

Sonuçlar

Gözetimli Öğrenme: Lojistik Regresyon modeli kullanılarak Titanic yolcularının hayatta kalma olasılıkları başarıyla tahmin edilmiştir.

Gözetimsiz Öğrenme: K-Means kümeleme algoritması ile yolcuların belirli gruplara ayrıldığı gözlemlenmiştir.
