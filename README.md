## Proje Adı: Spam Filtresi (Spam Detector)

Bu proje, yapay zeka (AI)  kullanarak gelen e-postaların spam olup olmadığını sınıflandırmayı amaçlar. Proje, e-posta metinlerini analiz ederek spam'larda sıklıkla kullanılan kelime ve ifadeleri tespit ederek spam ile normal e-postaları ayırt edebilmeyi öğrenen bir makine öğrenimi modeli oluşturur.

# Özellikler:

Veri Hazırlama: Spam ve normal e-postalar bir veri setine yüklenir ve ön işleme adımlarından geçirilir (temizleme, gereksiz sözcüklerin kaldırılması, metinlerin küçük harfe dönüştürülmesi).  
Öznitelik Çıkarma: TF-IDF (Term Frequency-Inverse Document Frequency) yöntemi kullanılarak e-postaların metinleri sayısal özelliklere dönüştürülür. Bu sayısal özellikler, e-postanın içeriği hakkında bilgi taşırır.  
Model Eğitimi: Logistic Regression algoritması kullanılarak bir sınıflandırma modeli eğitilir. Eğitim verisi, modelin spam ve normal e-posta ayırt etme yeteneğini öğrenmesini sağlar.  
Tahmin: Gelen yeni bir e-posta metni, eğitilmiş modele girilir. Model, e-postanın spam olma ihtimalini tahmin eder.  

# Nasıl Kullanılır:

Gerekli Kütüphaneler: Bu proje, Python programlama dili ve Pandas, NumPy, Scikit-learn gibi kütüphaneleri kullanır. Bu kütüphaneleri kurmanız gerekmektedir.  
Kod Çalıştırma: Jupyter Notebook ortamında veya Python komut satırında kodu çalıştırarak e-posta spam olup olmadığını kontrol edebilirsiniz.  

# Projenin Faydaları:

Spam e-postalar filtrelenerek gelen kutunuzda yer açabilir ve sizi gereksiz e-postalardan korur.  
Phishing gibi dolandırıcılık e-postalarını tespit ederek sizi siber güvenlik tehditlerinden korumaya yardımcı olur.  
