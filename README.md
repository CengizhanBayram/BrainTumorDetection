# BrainTumorDetection
# Brain Tumor Detection

Bu proje, beyin tümörlerinin MRI görüntülerini sınıflandırmak için derin öğrenme tekniklerini kullanarak bir model geliştirmeyi amaçlamaktadır. Model, çeşitli beyin tümörü türlerini tanımak için konvolüsyonel sinir ağları (CNN) kullanır ve görüntüleri doğru bir şekilde sınıflandırmak için eğitilmiştir.

## İçindekiler

- [Proje Açıklaması](#proje-açıklaması)
- [Başlangıç](#başlangıç)
- [Veri Seti](#veri-seti)
- [Model Mimarisi](#model-mimarisi)
- [Sonuçlar](#sonuçlar)
- [Lisans](#lisans)

## Proje Açıklaması

Bu proje, beyin tümörlerinin MRI görüntülerini sınıflandırmak için bir derin öğrenme modelinin oluşturulmasını ve test edilmesini içerir. Projede kullanılan model, çeşitli tümör türlerini sınıflandırabilme yeteneğine sahiptir ve bu yetenek, derin öğrenme yöntemleriyle elde edilmiştir.

## Başlangıç

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

### Gereksinimler

- Python 3.7+
- TensorFlow 2.x
- Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn

### Veri Seti
Projede kullanılan veri seti Kaggle'dan alınmıştır ve beyin tümörlerinin MRI görüntülerini içermektedir. Veri seti, Training ve Testing olarak iki ana klasöre ayrılmıştır.
https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri/data


### Model Mimarisi
Model, aşağıdaki katmanları içerir:

Conv2D Katmanı: 32 filtre, 3x3 çekirdek, ReLU aktivasyon
MaxPooling2D Katmanı: 2x2 havuzlama
Flatten Katmanı: Düzleştirme
Dense Katmanları: 128 nöron, ReLU aktivasyon
Dropout Katmanı: %20 dropout
Dense Katmanı: Son sınıflandırma için softmax
### Sonuçlar
Modelin doğruluk ve performans sonuçları aşağıdaki gibidir:

Doğruluk (Accuracy): %77+
Veri seti yeterli gelmedi
### Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.
