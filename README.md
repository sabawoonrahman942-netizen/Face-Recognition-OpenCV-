# Face Recognition with OpenCV & Google Colab

Bu proje, Python ve OpenCV kütüphanesi kullanılarak geliştirilmiş temel bir yüz tanıma sistemidir. Görüntüler üzerinde yüz tespiti yapar ve kayıtlı veri seti ile karşılaştırarak kimlik tespiti gerçekleştirir.

## 🚀 Proje İçeriği
* **Yüz Tespiti:** Haar Cascade sınıflandırıcı kullanılarak fotoğraflardaki yüzler otomatik olarak tespit edilir.
* **Eğitim:** Belirlenen bir klasördeki oyuncu fotoğrafları okunur ve gri tonlamaya çevrilerek sisteme kaydedilir.
* **Tanıma Algoritması:** Test edilen yüz ile kayıtlı yüzler arasındaki "Kare Farklarının Toplamı" (MSE) hesaplanarak en düşük skora sahip kişi belirlenir.

## 🛠 Kullanılan Teknolojiler
* **Dil:** Python
* **Kütüphane:** OpenCV (cv2), NumPy
* **Platform:** Google Colab & Drive

## 📸 Örnek Çıktı
![Yüz Tanıma Sonucu](image_d445aa.jpg)

## 📖 Nasıl Çalıştırılır?
1. `oyuncu_yuzleri/` klasörüne tanınacak kişilerin klasörlerini ve fotoğraflarını ekleyin.
2. `test_images/` klasörüne test etmek istediğiniz fotoğrafları yükleyin.
3. Colab dosyasını açın ve tüm hücreleri sırayla çalıştırın.
