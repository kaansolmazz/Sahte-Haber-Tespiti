# Sahte Haber Tespiti Projesi

Bu proje, internette bulunan sahte haberlerin tespitini sağlamak amacıyla Python ve çeşitli makine öğrenmesi algoritmaları kullanarak geliştirilmiştir. Proje kapsamında, çeşitli metin madenciliği teknikleri uygulanarak haberlerin gerçek ya da sahte olduğunu belirleme çalışmaları gerçekleştirilmiştir.

## Özellikler
- **Metin Madenciliği:** Stopwords temizleme, stemming, büyük/küçük harf düzenlemesi ve noktalama işaretlerinin temizlenmesi gibi işlemler yapılmıştır.
- **Veri Dönüşümü:** Veriler, TF-IDF ve Word2Vec gibi yöntemler kullanılarak sayısallaştırılmıştır.
- **Modelleme:** Naive Bayes, LSTM, KNN, ve SVM gibi makine öğrenmesi algoritmaları kullanılmıştır.
- **Performans Değerlendirme:** Doğruluk, precision, recall, F1 skoru gibi metrikler kullanılarak modellerin performansları değerlendirilmiştir.

## Kurulum
1. Bu projeyi yerel makinenize klonlayın:
    ```bash
    git clone https://github.com/kullaniciadi/sahte-haber-tespiti.git
    ```
2. Gerekli Python kütüphanelerini yükleyin:
    ```bash
    pip install -r requirements.txt
    ```
   **Not:** `requirements.txt` dosyasına aşağıdaki kütüphaneleri eklemeyi unutmayın:
   - numpy
   - pandas
   - scikit-learn
   - nltk
   - tensorflow

3. Uygulamayı çalıştırın:
    ```bash
    python sahte_haber_tespiti.py
    ```

## Kullanım
Uygulama çalıştırıldığında, veri setinizde bulunan haber metinlerini modelinize girdiler olarak verin. Model, bu girdilere dayanarak haberlerin gerçek mi yoksa sahte mi olduğunu tahmin edecektir. Sonuçlar, doğruluk, precision, recall, F1 skoru gibi metriklerle birlikte raporlanacaktır.

## Performans Sonuçları
Projede elde edilen sonuçlara göre, SVM ve TF-IDF kombinasyonu en yüksek doğruluk oranını sağlamıştır:
- **SVM + TF-IDF:** 98.1%
- **SVM + Word2Vec:** 70.1%
- **LSTM + TF-IDF:** 92.9%
- **LSTM + Word2Vec:** 90.4%
- **KNN + TF-IDF:** 84.5%
- **KNN + Word2Vec:** 89.6%
- **Naive Bayes + TF-IDF:** 90.7%

## Katkıda Bulunma
Katkılarınızı memnuniyetle karşılıyorum! Eğer bu projeyi geliştirmek isterseniz, lütfen mail atınız.

## Lisans
Bu proje Kırıkkale Üniversitesi lisans eğitimim altında gerçekleştirilmiştir.
