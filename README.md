# GoStock - Esnaflar için Yapay Zeka Destekli Akıllı Stok ve Mesajlaşma Asistanı

Grup 4 Yapay Zeka ve Teknoloji Akademisi - No-Code/Low-Code Bootcamp 2026 Projesi

---

## Takım Elemanları ve Rol Dağılımı
* **John Doe**: Product Owner (Ürün Sahibi & Süreç Yönetimi)
* **Jane Doe**: Scrum Master (Scrum Süreçleri & Takım Kolaylaştırıcısı)
* **Atıl Samancıoğlu**: Team Member / Lead Developer (Sistem Mimarisi & n8n/AppSheet Geliştirici)

---

## Ürün Bilgileri

### Ürün İsmi
GoStock

### Ürün Açıklaması
GoStock, geleneksel esnafların ve küçük işletmelerin dijitalleşmesini sağlayan; WhatsApp ve Instagram DM kanallarından gelen müşteri yoğunluğunu yapay zeka ile yönetirken arka planda No-Code entegrasyonuyla anlık stok takibi yapan akıllı bir otomasyon sistemidir.

Sistem, esnafın günlük operasyonel yükünü sıfıra indirirken, müşterilerin anlık fiyat ve stok sorularına 7/24 esnaf dilinde doğru yanıtlar üreterek satış dönüşümlerini artırır.

### Ürün Özellikleri
* **Google AppSheet Entegrasyonu**: Esnafın cep telefonundan kolayca ürün eklemesini, fiyat değiştirmesini ve hızlı stok girişi yapmasını sağlayan dinamik mobil/web panel.
* **Merkezi Veri Yönetimi (Google Sheets)**: Tüm stok, ürün ve fiyat verilerinin güvenli, anlık ve maliyetsiz bir şekilde bulutta depolanması.
* **Yapay Zeka Destekli Müşteri İlişkileri (AI Agent & n8n)**: Instagram DM ve WhatsApp üzerinden gelen ürün ve fiyat sorularının n8n üzerinden yakalanıp, OpenAI (GPT-4o mini) entegrasyonlu AI Agent ile anlık cevaplanması.
* **Akıllı Stok Sorgulama (RAG / Tool Çağırma)**: Yapay zekanın sadece metin üretmekle kalmayıp, esnafın güncel stok tablosuna giderek anlık veri doğrulaması yapması.
* **Kritik Stok Bildirim Sistemi**: Herhangi bir ürünün stoğu tükendiğinde veya kritik eşiğin altına düştüğünde, n8n aracılığıyla esnafa (Telegram/WhatsApp üzerinden) anlık mobil uyarı gitmesi.

### Hedef Kitle
* Yoğun müşteri mesajı alan yerel esnaflar ve KOBİ'ler
* Instagram ve WhatsApp üzerinden e-ticaret/satış yapan butikler
* Karmaşık ERP sistemlerine bütçe ayıramayan küçük işletmeler
* Müşteri ilişkilerini otomatize etmek isteyen dijital girişimciler

### Product Backlog
[Miro Backlog & Scrum Board URL]

---

## SPRINT 1

### Backlog Düzeni ve Story Seçimleri
Backlog'umuz ilk yapılacak User Story'lere göre önceliklendirilmiştir. Sprint başına tahmin edilen Story Puanı (SP) toplam puan sınırını geçmeyecek şekilde sırasıyla seçilmiştir. Story başına çıkan tahmin puanları, toplam puanın yarısından az tutularak risk minimize edilmiştir.

Miro Board'umuzda işbölümünü netleştirmek adına:
* **Mavi Kartlar**: User Story'leri temsil etmektedir.
* **Kırmızı Kartlar**: Story'lerin bölündüğü alt işleri (Task) temsil etmektedir.

### Daily Scrum
* **1. Gün**: Başlangıç yayınından hemen sonra görev dağılımı ve rol tanımları üzerine görüşmelere başlandı. Karar süreçlerini hızlandırmak amacıyla tüm proje fikirlerinin kolektif bir listede birleştirilmesi kararlaştırılarak ortak bir çalışma disiplini oluşturuldu.
* **2. Gün**: Proje üzerinde konuşulmak üzere saatler belirlendi. Proje ve roller belirlenecek.
* **3. Gün**: Projenin ne olduğu ve roller belirlendi. Product backlog'un ve ardından ilk sprintin de hazırlanması kararlaştırıldı.
*(4-14. Gün: Süreç takibi devam etmiştir.)*

### Sprint Board Durumu
*[Buraya Miro veya Jira Sprint Board ekran görüntüsünü ekleyin]*

### Ürün Durumu
*[Buraya AppSheet panelinizden ve AI mesajlaşma testlerinden ekran görüntülerini ekleyin]*

### Sprint Review
* **Alınan Kararlar**: Müşteri sipariş geçmişinin tutulacağı gelişmiş bir veritabanı yapısı bu sprintte önceliklendirilmemiştir. Sadece stok odaklı ilerlendiği için ilgili PBI bir sonraki sprint'e aktarılmıştır. Çıkan ürünün çalışmasında ve testlerinde bir problem görülmemiştir. Ekstra koyulması gereken özellikler belirlenmiştir.
* **Katılımcılar**: John Doe (PO), Jane Doe (SM), Atıl Samancıoğlu (Dev)

### Sprint Retrospective
* Takım içindeki görev dağılımıyla ilgili düzenleme yapılması kararı alınmıştır.
* Tahmin puanları gözden geçirilmeli ve sprint planlama toplantılarında gerekli geri bildirimlerin developer'lar tarafından verildiğine emin olunmalı.
* Entegrasyon testleri için ayrılan efor/saat arttırılmalı.

---

## SPRINT 2

### Backlog Düzeni ve Story Seçimleri
Backlog'umuz ilk yapılacak story'lere göre düzenlenmiştir. Sprint başına tahmin edilen puan sayısını geçmeyecek şekilde sıradan seçimler yapılmaktadır. Story başına çıkan tahmin puanı, toplam puanın yarısından az tutulmuştur.

### Daily Scrum
*(Gerekli günlük raporları buraya ekleyin)*

### Sprint Board Durumu
*[Buraya ekran görüntüsü ekleyin]*

### Ürün Durumu
*[Buraya ekran görüntüsü ekleyin]*

### Sprint Review
* **Alınan Kararlar**: Veritabanı optimizasyonları yapılmıştır. Çıkan ürünün çalışmasında ve testlerinde bir problem görülmemiştir. Ekstra koyulması gereken özellikler belirlenmiştir.
* **Katılımcılar**: John Doe (PO), Jane Doe (SM), Atıl Samancıoğlu (Dev)

### Sprint Retrospective
* Görev dağılımı optimize edildi.
* Tahminleme süreçleri iyileştirilmeli.
* Entegrasyon testlerine daha fazla odaklanılmalı.

---

## SPRINT 3

### Backlog Düzeni ve Story Seçimleri
Backlog'umuz ilk yapılacak story'lere göre düzenlenmiştir. Sprint başına tahmin edilen puan sayısını geçmeyecek şekilde sıradan seçimler yapılmaktadır. Story başına çıkan tahmin puanı, toplam puanın yarısından az tutulmuştur.

### Daily Scrum
*(Gerekli günlük raporları buraya ekleyin)*

### Sprint Board Durumu
*[Buraya ekran görüntüsü ekleyin]*

### Ürün Durumu
*[Buraya ekran görüntüsü ekleyin]*

### Sprint Review
* **Alınan Kararlar**: Projenin canlıya alım hazırlıkları tamamlanmıştır. Çıkan ürünün çalışmasında ve testlerinde bir problem görülmemiştir. Son sunum hazırlıkları gözden geçirilmiştir.
* **Katılımcılar**: John Doe (PO), Jane Doe (SM), Atıl Samancıoğlu (Dev)

### Sprint Retrospective
* Proje süreci başarılı tamamlandı.
* Gelecek geliştirmeler için notlar alındı.
