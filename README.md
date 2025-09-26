# beginner_intel_image_classification_project

# Giriş

Bu projede kaggle üzerinde bulunan intel image classificiation veri seti kullanılarak, CNN tabanlı bir sınıflandırma modeli eğitilmiştir.

Veri setinde 6 sınıf bulunmaktadır:
- Buildings (Binalar)  
- Forest (Orman)  
- Glacier (Buzul)  
- Mountain (Dağ)  
- Sea (Deniz)  
- Street (Sokak)

Proje yapısı:
- Veri analizi ve veri görselleştirmeleri yapılmıştır, sınıf örnek dengesi kontrol edilmiştir
- Model eğitiminde 20 epoch kullanılmıştır.
- Model 3 adet conventional ve maxpooling layer katmanı kullanılmıştır.
- Adam optimizer ve Cross_entropy kullanılarak eğitim gerçekleştirilmiştir.

# Metrikler

- Accuracy ve Loss grafikleri çıkarılmıştır.
- Confusion matrix kullanılarak modelin hangi sınıflar arasında hata yapmaya yatkın olduğu gözlemlenmiştir.

# Ekler

Projenin sonunda ayrıca hiperparametre optimizasyon denemesi yapılmıştır. Bu denemede filter ve learning rate değerleriyle oynayarak modelin başarısındaki değişim gözlemlenmiştir

# Kaggle Notebook Linki

-> https://www.kaggle.com/code/semihgunes/beginner-intel-image-cnn
