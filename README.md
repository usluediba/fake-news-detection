
🫁 Akciğer Kanseri Tahminleme Sistemi: Makine Öğrenmesi Yaklaşımı

 Proje VizyonuBu çalışma, modern tıbbın en büyük zorluklarından biri olan akciğer kanserinin erken teşhisi konusuna veri bilimi perspektifiyle yaklaşmaktadır. Geleneksel yöntemlerin ötesinde, anket tabanlı yaşam tarzı verilerini kullanarak yüksek doğruluklu bir risk analiz motoru oluşturmayı hedefler.

 Teknik EkosistemProje, verinin ham halinden tahmin üretimine kadar olan tüm süreçte şu araçları kullanır:
 Dil: Python
 3.xAnaliz: Pandas & NumPy (Matematiksel ve yapısal veri yönetimi)
 Görselleştirme: Seaborn & Matplotlib (Veri desenlerinin keşfi)
 Modelleme: Scikit-learn (Algoritma geliştirme ve değerlendirme)

 Veri Mühendisliği ve Ön İşlemeMakine öğrenmesi modelinin başarısı, verinin kalitesine bağlıdır. Bu projede şu kritik işlemler uygulanmıştır:
 Veri Temizleme: Eksik veya gürültülü verilerin analizi yapıldı.Özellik Mühendisliği (Feature Engineering):
 Label Encoding: "Evet/Hayır" gibi sözel veriler 1/0 mantığına çevrildi.
 Standard Scaling: Sayısal değerler arasındaki ölçek farkı giderildi, böylece modeller daha dengeli eğitildi.
 Korelasyon Analizi: Hangi faktörlerin (Sigara, Hava Kirliliği, Genetik vb.) kanserle daha doğrudan ilişkili olduğu ısı haritalarıyla (Heatmap) saptandı.

 Algoritma KarşılaştırmasıProje, tek bir modele güvenmek yerine üç farklı mimariyi "yarıştırmıştır":AlgoritmaKullanım AmacıAvantajıLogistic RegressionOlasılık Temelli SınıflandırmaHızlı ve yorumlanabilir.Naive BayesBayes Teoremi YaklaşımıKarmaşık olmayan veri setlerinde çok etkili.Random ForestKarar Ağaçları Topluluğu(En İyi Performans) Aşırı öğrenmeyi (overfitting) engeller.

 Performans Analizi (Metrikler)Model başarısı sadece "doğruluk" (accuracy) ile değil, tıbbi hassasiyet gözetilerek şu yöntemlerle ölçülmüştür:
 Confusion Matrix: Hatalı pozitif ve hatalı negatif tahminlerin dağılımı.
 ROC-AUC Eğrisi: Modelin kanser olan ile olmayanı birbirinden ayırma kapasitesi.
 F1-Score: Duyarlılık ve kesinlik arasındaki denge.

 Kurulum ve KullanımProjeyi kendi ortamınızda çalıştırmak için:Depoyu indirin: git clone https://github.c
om/KULLANICI_ADIN/REPOSTORY_ADIN.gitGereksinimleri kurun: pip install -r requirements.txtJupyter Notebook'u başlatın: jupyter notebook

SonuçBu model, yaşam tarzı verileriyle akciğer kanseri riskinin % 91 doğrulukla tahmin edilebileceğini kanıtlamıştır. Gelecekte görüntü işleme (CT taramaları) entegrasyonu ile sistemin kapsamı genişletilebilir.

fileID:1XyZ_example_id

