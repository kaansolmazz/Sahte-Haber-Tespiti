<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sahte Haber Tespiti Projesi</title>
</head>
<body>
    <h1>Sahte Haber Tespiti Projesi</h1>
    <p>Bu proje, internette bulunan sahte haberlerin tespitini sağlamak amacıyla Python ve çeşitli makine öğrenmesi algoritmaları kullanarak geliştirilmiştir. Proje kapsamında, çeşitli metin madenciliği teknikleri uygulanarak haberlerin gerçek ya da sahte olduğunu belirleme çalışmaları gerçekleştirilmiştir.</p>

    <h2>Özellikler</h2>
    <ul>
        <li>Metin Madenciliği: Stopwords temizleme, stemming, büyük/küçük harf düzenlemesi ve noktalama işaretlerinin temizlenmesi gibi işlemler yapılmıştır.</li>
        <li>Veri Dönüşümü: Veriler, TF-IDF ve Word2Vec gibi yöntemler kullanılarak sayısallaştırılmıştır.</li>
        <li>Modelleme: Naive Bayes, LSTM, KNN, ve SVM gibi makine öğrenmesi algoritmaları kullanılmıştır.</li>
        <li>Performans Değerlendirme: Doğruluk, precision, recall, F1 skoru gibi metrikler kullanılarak modellerin performansları değerlendirilmiştir.</li>
    </ul>

    <h2>Kurulum</h2>
    <ol>
        <li>Bu projeyi yerel makinenize klonlayın:
            <pre><code>git clone https://github.com/kullaniciadi/sahte-haber-tespiti.git</code></pre>
        </li>
        <li>Gerekli Python kütüphanelerini yükleyin:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <p><strong>Not:</strong> <code>requirements.txt</code> dosyasına aşağıdaki kütüphaneleri eklemeyi unutmayın:</p>
        <ul>
            <li>numpy</li>
            <li>pandas</li>
            <li>scikit-learn</li>
            <li>nltk</li>
            <li>tensorflow</li>
        </ul>
        <li>Uygulamayı çalıştırın:
            <pre><code>python sahte_haber_tespiti.py</code></pre>
        </li>
    </ol>

    <h2>Kullanım</h2>
    <p>Uygulama çalıştırıldığında, veri setinizde bulunan haber metinlerini modelinize girdiler olarak verin. Model, bu girdilere dayanarak haberlerin gerçek mi yoksa sahte mi olduğunu tahmin edecektir. Sonuçlar, doğruluk, precision, recall, F1 skoru gibi metriklerle birlikte raporlanacaktır.</p>

    <h2>Performans Sonuçları</h2>
    <p>Projede elde edilen sonuçlara göre, SVM ve TF-IDF kombinasyonu en yüksek doğruluk oranını sağlamıştır:</p>
    <ul>
        <li>SVM + TF-IDF: 98.1%</li>
        <li>SVM + Word2Vec: 70.1%</li>
        <li>LSTM + TF-IDF: 92.9%</li>
        <li>LSTM + Word2Vec: 90.4%</li>
        <li>KNN + TF-IDF: 84.5%</li>
        <li>KNN + Word2Vec: 89.6%</li>
        <li>Naive Bayes + TF-IDF: 90.7%</li>
    </ul>

    <h2>Katkıda Bulunma</h2>
    <p>Katkılarınızı memnuniyetle karşılıyoruz! Eğer bu projeyi geliştirmek isterseniz, lütfen bir pull request gönderin veya bir konu açın.</p>

    <h2>Lisans</h2>
    <p>Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına göz atın.</p>
</body>
</html>

