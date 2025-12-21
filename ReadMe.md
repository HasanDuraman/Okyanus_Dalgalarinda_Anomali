# Okyanus Dalgalarında Fırtına Kaynaklı Anomali Tespiti

Bu proje, NOAA (National Data Buoy Center) şamandıra istasyonlarından alınan **gerçek zamanlı (real-time)** okyanus verilerini kullanarak, fırtına kaynaklı dalga anomalilerini tespit eden bir **Veri Madenciliği ve Makine Öğrenmesi** uygulamasıdır.

Proje, ham verinin temizlenmesinden (preprocessing) başlayıp, spektral analiz (FFT) ve denetimsiz öğrenme (Unsupervised Learning) modelleriyle anomali tespiti yapılmasına kadar uçtan uca bir analiz sunar.

## Özellikler

* **Canlı Veri Akışı:** NOAA İstasyon 46047'den anlık veri çekme ve işleme.
* **Veri Madenciliği:** Eksik veri tamamlama, gürültü filtreleme (Rolling Median) ve ilişki analizi (Korelasyon Matrisi).
* **Spektral Analiz:** Hızlı Fourier Dönüşümü (FFT) ile dalga enerji dağılımının incelenmesi.
* **Anomali Tespiti:** **Isolation Forest** algoritması ile fırtına ve ani dalga değişimlerinin tespiti.
* **Kümeleme:** **PCA** (Boyut İndirgeme) ve **DBSCAN** ile deniz durumlarının sınıflandırılması.
* **Performans Analizi:** ROC Eğrisi ve AUC skoru ile model başarımı.

## Kurulum

Bu proje **Python 3.13** ve üzeri sürümlerle uyumlu olacak şekilde geliştirilmiştir.

### Projeyi Klonlayın
git clone [https://github.com/KULLANICI_ADIN/REPO_ADIN.git](https://github.com/KULLANICI_ADIN/REPO_ADIN.git)
