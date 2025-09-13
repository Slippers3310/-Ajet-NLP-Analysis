# ✈️ AJet Havayolu Müşteri Yorumları Analizi (NLP)

## 📌 Proje Hakkında
Bu proje, **AJet havayolu şirketine ait müşteri şikayetlerini** analiz etmek için doğal dil işleme (NLP) ve makine öğrenimi tekniklerini kullanmaktadır.  
Amaç, müşteri yorumlarını otomatik olarak **kategorize etmek**, **duygu analizi** yapmak ve şirketin müşteri deneyimini geliştirmesine yardımcı olacak **eyleme geçirilebilir içgörüler** sunmaktır.  

## 🎯 Amaç ve Motivasyon
- Müşteri şikayetlerini manuel incelemek zaman alıcı ve subjektiftir.  
- NLP tabanlı sınıflandırma ile yorumları **uçuş gecikmeleri, personel davranışı, hizmet kalitesi** gibi kategorilere ayırmak mümkündür.  
- Bu sayede şirket, **operasyonel iyileştirme alanlarını hızlıca tespit edebilir**.  

## ⚙️ Kullanılan Teknolojiler
- **Python** (pandas, numpy, scikit-learn)  
- **Doğal Dil İşleme (NLP)** → NLTK, TF-IDF  
- **Makine Öğrenimi** → Naive Bayes Classifier  
- **Görselleştirme** → Matplotlib, Seaborn, WordCloud  

## 📊 Adımlar
1. **Veri Toplama** → Şikayetvar platformundan toplanmış müşteri şikayetleri.  
2. **Ön İşleme** → Temizleme, tokenizasyon, durak kelime çıkarımı.  
3. **Özellik Çıkarma** → TF-IDF vektörleştirme.  
4. **Modelleme** → Naive Bayes sınıflandırma.  
5. **Analiz** → Duygu analizi, kelime bulutu, kategori dağılımları.  

## 🚀 Çalıştırma
```bash
pip install -r requirements.txt
jupyter notebook "Ajet Proje.ipynb"
