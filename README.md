 # Yol Ağı Segmentasyonu
 Bu çalışmada İstanbul'a ait .png formatlı uydu görüntüleri ve maskelerinden Derin Öğrenme ile Yol ağının segmentasyonun üreten bir çalışma yaptım.
 Çalışmada Unet mimarisi ve Efficientnet-b5 sınıflandırma kodlayıcısı kullandım.Google Colab ortamında çalıştım.Veri setini Google Colab'a indirmek için kişisel Kaggle.json dosyasınızı Kaggle'deki kullanıcı bölümünden indirmeniz gerekir.Modelini daha da iyileştirme adına hiper parametreler , veri arttırım parametleri , epok sayısı ( 10 epok çalıştım ) vb parametleri değiştirerek yeniden üretilebilirsiniz.


Veri Seti : https://www.kaggle.com/datasets/ozanozturk61/istanbul-road-dataset

Not:Paylaşılan veri setinde her biri 10 000 'er adet görüntü ve maske olan 4 ayrı bölüm var. 14. bölümde görüntü ve maske sayısı uyuşumsuzluğu olduğu için hata veriyor.  Bu çalışmamda eğitim ve doğrulama için 15. bölümü , test için 17. bölümü kullandım.
