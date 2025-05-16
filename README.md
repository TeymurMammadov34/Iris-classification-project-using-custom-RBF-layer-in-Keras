# 🌸 Iris Veri Seti ile RBF Sinir Ağı Sınıflandırması

Bu proje, scikit-learn kütüphanesinden alınan klasik **Iris veri seti** üzerinde özel bir **Radial Basis Function (RBF)** katmanı kullanarak bir sinir ağı modeli eğitmektedir. Model, Keras ile oluşturulmuştur ve eğitim süreci boyunca başarı oranları görselleştirilmiştir.

---

## 📌 Proje Özeti

- 📊 **Veri Seti**: scikit-learn içindeki Iris veri seti  
- 🧠 **Model**: Keras ile yazılmış özel RBF katmanı + Dense (Çıkış) katmanı  
- ⚙️ **Kütüphaneler**: scikit-learn, TensorFlow, Keras, matplotlib  
- 📈 **Değerlendirme**: Eğitim ve doğrulama kaybı/grafikleri, test seti doğruluğu

---

## ❓ RBF Katmanı Nedir?

RBF (Radial Basis Function), giriş ile belirli merkezler (mu) arasındaki mesafeye göre çalışan bir aktivasyon fonksiyonudur. Bu projede, Keras kullanılarak sıfırdan özel bir RBF katmanı yazılmıştır. Bu katman sayesinde model, verileri farklı bir bakış açısıyla öğrenmektedir.

---



---

## 🚀 Nasıl Çalıştırılır?

1. Jupyter Notebook ortamında `iris_rbf_modeli.ipynb` dosyasını açın.  
2. Tüm hücreleri sırayla çalıştırarak modeli eğitebilir ve sonuçları görebilirsiniz.

---

## 📊 Modelin Çıktısı

- Model 100 epoch boyunca eğitilir.
- Eğitim ve doğrulama sürecindeki **loss** ve **accuracy** grafiklerle görselleştirilir.
- Test verisi üzerinde doğruluk ve kayıp sonuçları yazdırılır:

**Test loss: 0.23, Test accuracy: 0.97**




## 💡 Not

Bu proje yalnızca bir `.ipynb` (Jupyter Notebook) dosyası içermektedir. Harici bir `requirements.txt` dosyasına gerek yoktur.  
Gerekli kütüphaneler şunlardır:

- `tensorflow`
- `scikit-learn`
- `matplotlib`

---



## 👨‍💻 Geliştirici

**Teymur Mammadov** 





