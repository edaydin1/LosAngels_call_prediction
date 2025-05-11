📊 LA311 Service Requests Data Analysis
Bu proje, Los Angeles şehrine ait 311 hizmet talebi verileri üzerinde yapılan veri ön işleme ve analiz sürecini kapsamaktadır. Kullanılan veri kümesi, çeşitli hizmet başvurularının tarihsel ve kategorik bilgilerini içermektedir.

📁 Veri Seti
Kaynak: MyLA311_Service_Request_Data_2024_20250212.csv

İçerik: Hizmet türleri, konum bilgileri, talep oluşturulma tarihleri, kapanış tarihleri gibi birçok sütunu barındırmaktadır.

🧰 Kullanılan Kütüphaneler
pandas

numpy

matplotlib

seaborn

🔧 Yapılan İşlemler
Gereksiz sütunların kaldırılması

Eksik/veri doğruluğu olmayan kayıtların temizlenmesi

Tarih sütunlarının işlenmesi ve yeni zaman tabanlı özelliklerin oluşturulması (örn. AM/PM, hafta içi/hafta sonu)

Verilerin görselleştirilmesi için hazırlık

📂 Dosyalar
i_new copy2.ipynb: Tüm analiz ve işleme adımlarının yer aldığı Jupyter defteri

MyLA311_Service_Request_Data_2024_20250212.csv: Ham veri seti (dahil edilmediyse dış kaynak belirtilmeli)

🚀 Nasıl Kullanılır?
Gerekli kütüphaneleri yükleyin:

bash

pip install pandas numpy matplotlib seaborn
Notebook dosyasını çalıştırın:

bash

jupyter notebook i_new copy2.ipynb
Adım adım hücreleri çalıştırarak veri temizleme sürecini takip edebilirsiniz.

