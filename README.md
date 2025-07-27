# Makine Öğrenimi Kümeleme Algoritmaları

Bu depo, çeşitli popüler makine öğrenimi kümeleme algoritmalarının (K-Means, Hiyerarşik Kümeleme, DBSCAN ve diğerleri) Python ve scikit-learn kütüphaneleri kullanılarak uygulanmasını ve incelenmesini içermektedir. Proje, farklı veri setleri üzerinde bu algoritmaların nasıl çalıştığını, güçlü ve zayıf yönlerini görselleştirmelerle birlikte göstermektedir.

## İçerik

Bu depo, kümeleme algoritmaları üzerine çeşitli Jupyter Notebook dosyalarını içermektedir:

* **`kMeans.ipynb`**: K-Means kümeleme algoritmasının temel prensiplerini ve rastgele oluşturulmuş veri setleri üzerinde nasıl uygulandığını göstermektedir. Elbow metodu gibi K değeri seçimi yöntemleri de incelenmiş olabilir.
* **`hiyerarsik.ipynb`**: Hiyerarşik kümeleme algoritmalarını (Agglomerative Clustering) ve dendrogramların nasıl yorumlandığını açıklar. Farklı bağlantı (linkage) yöntemleri (Ward, Complete, Average, Single) ile kümeleme sonuçları karşılaştırılır.
* **`dbscan.ipynb`**: Yoğunluk tabanlı bir kümeleme algoritması olan DBSCAN'in (Density-Based Spatial Clustering of Applications with Noise) yapısını ve özellikle gürültülü verilerle veya küresel olmayan şekillerdeki kümelerle nasıl başa çıktığını gösterir.
* **`kumelemeAlgoritmalari.ipynb`**: Birden fazla kümeleme algoritmasını (K-Means, Hiyerarşik, DBSCAN, Spectral, BIRCH vb.) farklı sentetik veri setleri üzerinde karşılaştıran ve görselleştiren genel bir not defteridir. Bu, algoritmaların çeşitli veri dağılımlarına nasıl tepki verdiğini anlamak için idealdir.

## Özellikler

* Kapsamlı veri görselleştirmeleri ile kümeleme sonuçlarının analizi.
* Her bir algoritmanın parametrelerinin (örneğin K-Means için `k`, DBSCAN için `eps` ve `min_samples`) etkilerinin incelenmesi.
* Veri seti oluşturma (örneğin `make_blobs`, `make_circles`, `make_moons`) ile algoritmaların farklı veri yapıları üzerindeki davranışlarını test etme.
* Scikit-learn kütüphanesinin etkin kullanımı.

## Kullanılan Teknolojiler

* **Python**
* **NumPy**: Sayısal işlemler ve dizi manipülasyonları için.
* **Matplotlib**: Veri görselleştirmeleri için.
* **Scikit-learn**: Çeşitli kümeleme algoritmaları ve veri seti oluşturma fonksiyonları için.
* **SciPy**: Hiyerarşik kümeleme dendrogramları için.
