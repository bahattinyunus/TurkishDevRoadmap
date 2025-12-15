# 🤖 AI & Data Roadmap (Yapay Zeka ve Veri Bilimi)

> **"Veriyi petrole, algoritmayı motora dönüştür."**  
> Veriden anlam çıkarma ve makineleri akıllandırma sanatı.

---

## 🟢 Seviye 1: Veri Analisti (Data Analyst) - Junior
*Veriyi anlama, temizleme ve görselleştirme.*

### 1. Python ve Temel Kütüphaneler
- **Python**: Dilin kendisi. List comprehensions, functions.
- **NumPy**: Matematiksel işlemler ve matrisler.
- **Pandas**: Veri manipülasyonu (Excel'in kod hali). `DataFrame`, `read_csv`, `groupby`.
- **Matplotlib / Seaborn**: Veri görselleştirme. Grafikler çizme.

### 2. İstatistik ve Matematik
- [ ] **İstatistik 101**: Ortalama, Medyan, Standart Sapma, Olasılık Dağılımları (Normal, Poisson).
- [ ] **Lineer Cebir**: Vektörler, Matris çarpımı (Yapay zekanın temeli).

### 3. SQL (Veri Çekme)
- [ ] Karmaşık sorgularla (`JOIN`, `GROUP BY`, `WINDOW FUNCTIONS`) veritabanından ham veriyi çekip analize hazır hale getirme.

---

## 🟡 Seviye 2: Veri Bilimci (Data Scientist) - Mid
*Geçmiş veriden geleceği tahmin etme (Predictive/Machine Learning).*

### 1. Machine Learning (Makine Öğrenmesi)
- [ ] **Scikit-Learn**:
    - **Supervised Learning**: Linear Regression (Tahmin), Logistic Regression (Sınıflandırma), Decision Trees.
    - **Unsupervised Learning**: K-Means Clustering (Kümeleme).
- [ ] **Model Evaluation**: Accuracy, Precision, Recall, F1 Score. Overfitting/Underfitting kavramları.

### 2. Deep Learning (Derin Öğrenme)
- [ ] **Kütüphaneler**: TensorFlow veya PyTorch (Sektörde PyTorch yükselişte).
- [ ] **Neural Networks (YSA)**: Katmanlar (Layers), Activation Functions (ReLU, Sigmoid).
- [ ] **CNN (Computer Vision)**: Resim işleme, nesne tanıma (YOLO).
- [ ] **RNN/LSTM**: Zaman serileri ve metin işleme.

### 3. Veri Ön İşleme (Feature Engineering)
- [ ] **Missing Data**: Eksik verileri doldurma (Imputation).
- [ ] **Encoding**: Kategorik veriyi (Kırmızı, Mavi) sayıya çevirme (One-Hot Encoding).
- [ ] **Scaling**: Verileri 0-1 arasına sıkıştırma (Normalization).

---

## 🔴 Seviye 3: AI Engineer / MLOps - Senior
*Modelleri canlıya alma ve büyük dil modelleri.*

### 1. Generative AI & LLMs (Çağın Teknolojisi)
- [ ] **Transformers**: GPT mimarisinin temeli (Attention is all you need).
- [ ] **LLM Kullanımı**: OpenAI API, Hugging Face modelleri.
- [ ] **RAG (Retrieval-Augmented Generation)**: Yapay zekaya kendi dokümanlarını okutarak cevap verdirme (LangChain, Vector Databases - Pinecone/ChromaDB).
- [ ] **Fine-Tuning**: Hazır modeli kendi verinle eğitme.

### 2. MLOps (DevOps for ML)
- [ ] **Model Deployment**: Eğittiğin modeli Flask/FastAPI ile sunucuya koyma.
- [ ] **Tracking**: MLflow veya Weights & Biases ile deney takibi.
- [ ] **Containerization**: Docker ile modelin çalışacağı ortamı sabitleme.

### 3. Big Data (Büyük Veri)
- [ ] Pandas yetmediğinde devreye girenler: **Apache Spark (PySpark)**, **Hadoop**.

---

## 🛠️ Araç Kutusu (Toolkit)
- **IDE**: Jupyter Notebook / Google Colab (Hızlı deneme), VS Code (Proje).
- **Environment**: Anaconda veya Virtualenv.
- **Yarışma**: Kaggle (Veri setleri ve yarışmalar).

---

## 📚 Kaynaklar

| Kaynak | Tip | Dil | Seviye |
| :--- | :--- | :--- | :--- |
| **[Andrew Ng - Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction)** | Kurs | İngilizce | Başlangıç |
| **[Veri Bilimi Okulu (VBO)](https://www.veribilimiokulu.com/)** | Web | Türkçe | Hepsi |
| **[Merve Noyan - Hugging Face](https://huggingface.co/)** | Topluluk | İngilizce | İleri |
| **[TensorFlow Playground](https://playground.tensorflow.org/)** | Simülasyon | İngilizce | Başlangıç |

---

## 💡 Proje Fikirleri

1.  **Ev Fiyat Tahmini**: Kaggle'dan ev verilerini indir, özelliklerine (oda sayısı, konum) göre fiyat tahmin eden model eğit.
2.  **Müşteri Terk Analizi (Churn)**: Hangi müşteri aboneliği iptal edecek? Sınıflandırma projesi.
3.  **Chatbot (RAG)**: Şirket içi PDF dosyalarını yükle, "Şirket izin politikası nedir?" diye sorunca PDF'ten bulup cevaplasın. (LangChain + OpenAI).
4.  **Araç Plaka Tanıma**: CNN kullanarak araba resimlerinden plakayı okuyan sistem.

---

## ❓ Mülakat Soruları
- 1. Overfitting (Aşırı öğrenme) nedir? Nasıl engellenir? (Regularization, Dropout).
- 2. Precision ve Recall arasındaki fark nedir? Hangi durumda hangisi önemlidir?
- 3. "Gradient Descent" algoritması ne işe yarar?
- 4. Train, Validation ve Test setleri neden ayrılır?
- 5. BERT ve GPT arasındaki temel mimari fark nedir? (Encoder vs Decoder).
