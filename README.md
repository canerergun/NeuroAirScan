# 🛰️ NeuroAirScan - YOLOv8 Tabanlı Radar Uçak Tespit Sistemi

Bu proje, **YOLOv8 algoritması** kullanılarak radar uçaklarını tespit etmeye yönelik geliştirilen özel bir görüntü işleme sistemidir. 

Veri kümesindeki tüm etiketlemeler tarafımdan manuel olarak yapılmıştır. Her bir görüntü titizlikle etiketlenmiş ve model eğitimine uygun hale getirilmiştir. Hazır veya otomatik bir veri kümesi kullanılmamıştır.

---

## 🔧 Gereksinimler

## Kullanılan Teknolojiler ve Araçlar

- **Python 3.11.9+**  
- **Roboflow API** — Veri seti yönetimi ve indirme  
- **Ultralytics YOLOv8** — Nesne tespiti modeli  
- **OpenCV** — Video işleme ve görselleştirme  
- **python-dotenv** — Ortam değişkenlerini yönetmek için  
- **Jupyter Notebook** — Deneysel çalışmalar ve prototipleme  

---

## Proje Kurulumu ve Çalıştırma

### 1. Gerekli Kütüphaneleri Yükleme

```bash
pip install ultralytics roboflow python-dotenv opencv-python
