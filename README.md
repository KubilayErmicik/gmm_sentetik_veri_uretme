# 🐦 GMM ile Sentetik Muhabbet Kuşu Ceresi Üretimi

Bu projede, **Gaussian Mixture Model (GMM)** kullanılarak gerçek muhabbet kuşu ceresi görsellerinden yola çıkarak **sentetik ceres görüntüleri** üretilmiştir. Veri artırımı (data augmentation) amacıyla kullanılan bu yöntem, sınırlı sayıda veriden yola çıkarak **doğal varyasyonları yansıtan** yeni örnekler üretmeyi hedefler.

---

## 📌 Projenin Amacı

- 📈 **Veri artırımı:** Gerçek verinin az olduğu senaryolarda model eğitimi için veri üretmek.
- 🧠 **GMM kullanımı:** Görsellerin dağılımını Gauss karışımı ile modelleyip yeni örnekler üretmek.
- 🎨 **Görsel kalite analizi:** Gerçek ve sentetik görsellerin karşılaştırılmasıyla kalite değerlendirmesi.

---

## 🧪 Kullanılan Teknolojiler

- Python 3.x
- OpenCV
- NumPy
- Scikit-learn
- scikit-image (SSIM metriği için)
- Matplotlib

Kurulum:
```bash
pip install numpy opencv-python scikit-learn scikit-image matplotlib
