# Spotify Müzik Verileri Üzerinden Şarkı Popülerliğinin Makine Öğrenmesi ile Analizi ve Tahmini

Bu proje, Spotify platformunda yer alan şarkıların akustik ve teknik ses özniteliklerini inceleyerek bir şarkının popüler olma olasılığını makine öğrenmesi algoritmaları ile tahmin etmek amacıyla geliştirilmiştir.

---

## 📋 Proje Hakkında
Günümüz dijital müzik endüstrisinde hangi şarkıların geniş dinleyici kitlelerine ulaşacağını öngörmek kritik bir öneme sahiptir. Bu çalışmada, açık kaynaklı Spotify şarkı veri seti kullanılarak keşifsel veri analizi (EDA) gerçekleştirilmiş ve farklı sınıflandırma algoritmalarıyla popülerlik tahmini modelleri eğitilmiştir.

---

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler
* **Programlama Dili:** Python
* **Geliştirme Ortamı:** Google Colaboratory (Colab)
* **Veri İşleme ve Analiz:** Pandas, NumPy
* **Veri Görselleştirme:** Matplotlib, Seaborn
* **Makine Öğrenmesi:** Scikit-learn (Logistic Regression, Random Forest, StandardScaler, train_test_split)

---

## 📊 Proje Adımları
1. **Veri Ön İşleme:** Ham veri setindeki eksik değerler ve tekrarlayan kayıtlar temizlenmiş; popülerlik skoru 60 eşik değerine göre ikili sınıflandırma (`1: Popüler`, `0: Popüler Değil`) formatına dönüştürülmüştür.
2. **Keşifsel Veri Analizi (EDA):** Müzik türlerine göre ortalama popülerlik oranları incelenmiş ve ses öznitelikleri arasındaki ilişkiler korelasyon matrisi (ısı haritası) ile görselleştirilmiştir.
3. **Modelleme:** Veri seti %80 eğitim ve %20 test olarak ayrılmış; Lojistik Regresyon ve Random Forest modelleri eğitilerek doğruluk (accuracy) skorları karşılaştırılmıştır.
4. **Öznitelik Önemi (Feature Importance):** Random Forest modeli kullanılarak şarkı popülerliğini en çok etkileyen akustik parametreler tespit edilmiştir.

---

## 🚀 Projeyi Çalıştırma
Analiz kodlarını incelemek ve çalıştırmak için:
1. `Spotify_Populerlik_Analizi.ipynb` dosyasını bilgisayarınıza indirin veya doğrudan **Google Colab** üzerinde açın.
2. Kod hücrelerini sırasıyla çalıştırarak veri analizi ve model eğitim aşamalarını gözlemleyin.

---

## 📂 Dosya Yapısı
```text
├── README.md                  # Proje dokümantasyonu
└── Spotify_Populerlik_Analizi.ipynb # Colab veri analizi ve modelleme kodları
