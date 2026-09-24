\
---
name: "ERP Süreç Eşleştirme"
template_version: "0.0.0"
status: "Active"
category: "Governance"
authority: "Implementing AS9100 8.5.6"
file_path: "03_ERP_Fonksiyon _Eslestirme_Surec_Konfigurasyonu/erp-process-mapping-and-configuration.md"
---

# ERP Süreç Eşleştirme

**Artifact ID:** ERP001  
**Artifact Name:** "ERP Process Mapping and Configuration"  
**Template Version:** 0.0.0  
**Status:** Active  
**Authority:** "Implementing AS9100 8.5.6 "  
**File Path:** `03_ERP_Fonksiyon _Eslestirme_Surec_Konfigurasyonu/erp-process-mapping-and-configuration.md`

> **Usage note:** ERP Süreç Eşleştirme Matrisi, süreçler ile ERP fonksiyonları arasındaki temel ilişkiyi tanımlamak amacıyla hazırlanmıştır. Bu çalışma, ERP kullanım detaylarının, kullanıcı talimatlarının veya sistem konfigürasyon ayarlarının yerine kullanılmaz. Süreçlerin geliştirilmesi, yeni ihtiyaçların ortaya çıkması veya ERP kullanım kapsamının genişlemesi durumunda matris gözden geçirilerek güncellenmelidir.

---

## Proje Kimliği

| --- | --- |
|---|---|
| **Proje Adı** | ERP Süreç Eşleştirme Aşaması |
| **Proje ID / Kodu** | ERP003 |
| **Proje Türü** | Değişiklik Yönetimi Sürecinin Oluşturulması |
| **Başlatma Belgesi Tarihi** | 24.09.2026 |
| **Belge Versiyonu** | .v000 |
| **Hazırlayan** | Ezgi ÖZCAN |

---

## ERP Süreç Eşleştirme

### Amaç

Operasyonel süreçlerde gerçekleştirilen faaliyetlerin ERP sistemi içerisindeki karşılıklarını tanımlamak, süreçler ile ERP fonksiyonları arasındaki ilişkiyi standart hale getirmek ve her iş adımı sonucunda oluşan kayıtların sorumluluklarını belirleyerek izlenebilir bir kullanım yapısı oluşturmak.

### Tanım

Bu aşamada, operasyonel süreçlerde gerçekleştirilen faaliyetler ERP sistemi içerisindeki ilgili işlem veya modüller ile eşleştirilir. Her süreç adımı için oluşturulan kayıt, sorumlu rol ve sonraki sürece aktarılan bilgi belirlenerek süreçlerin ERP üzerinde tutarlı, izlenebilir ve standart şekilde yürütülmesi amaçlanır.

Bu çalışma sonucunda oluşturulan eşleştirme matrisi, veri standardizasyonu, kullanıcı yetkilendirmesi, eğitim planlaması, görev tanımları, pilot uygulama ve sistem doğrulama çalışmalarına temel girdi oluşturur.

## ERP Süreç Eşleştirme Matrisi

| No | İş Süreci / Faaliyet                                                        | ERP Fonksiyonu / İşlemi                       | Oluşturulan Kayıt                            | Sorumlu Rol               | Sonraki Süreç                           |
| -- | --------------------------------------------------------------------------- | --------------------------------------------- | -------------------------------------------- | ------------------------- | --------------------------------------- |
| 1  | Müşteri talebi ve sipariş bilgilerinin alınması                             | Fırsat / Teklif / Sipariş yönetimi            | Fırsat kaydı, teklif kaydı, müşteri siparişi | Satış / ERP Kullanıcısı   | Teknik değerlendirme ve üretim planlama |
| 2  | Teknik gerekliliklerin değerlendirilmesi ve ürün bilgilerinin oluşturulması | Ürün kartı ve ürün ağacı yönetimi             | Ürün kartı, revizyon bilgisi, ürün ağacı     | Üretim Mühendisi          | Operasyon planlama                      |
| 3  | Üretim yöntemleri ve operasyonların belirlenmesi                            | Rota ve operasyon tanımlama                   | Üretim rotası, operasyon bilgileri           | Üretim Mühendisi          | İş emri oluşturma                       |
| 4  | Üretim planlama ve iş emri oluşturma                                        | İş emri yönetimi                              | İş emri kaydı                                | Üretim Sorumlusu          | Üretim faaliyetleri                     |
| 5  | Malzeme ihtiyaçlarının belirlenmesi                                         | Malzeme ihtiyaç yönetimi                      | Malzeme talebi, ihtiyaç kaydı                | Üretim / Depo Sorumlusu   | Malzeme hazırlığı                       |
| 6  | Malzeme kabul, stok ve izlenebilirlik yönetimi                              | Stok yönetimi, lot/seri takibi                | Stok kaydı, lot/heat bilgisi                 | Depo Sorumlusu            | Üretim kullanımı                        |
| 7  | Üretim operasyonlarının gerçekleştirilmesi                                  | İş emri operasyon takibi                      | Operasyon gerçekleşme kaydı                  | Üretim Personeli          | Kalite kontrol                          |
| 8  | Kalite kontrol faaliyetlerinin gerçekleştirilmesi                           | Kalite kontrol / GKK işlemleri                | Kontrol kaydı, ölçüm sonuçları               | Kalite Kontrol Elemanı    | Ürün kabul veya uygunsuzluk yönetimi    |
| 9  | Uygunsuz ürünlerin yönetimi                                                 | Uygunsuzluk ve DF yönetimi                   | Uygunsuzluk kaydı, düzeltici faaliyet kaydı  | Kalite Birimi             | Tekrar değerlendirme                    |
| 10 | Ürün izlenebilirliğinin sağlanması                                          | Lot/seri/parti takibi                         | İzlenebilirlik kayıtları                     | Kalite / Depo Sorumlusu   | Sevkiyat hazırlığı                      |
| 11 | Ürün sevkiyatının gerçekleştirilmesi                                        | Sevkiyat yönetimi                             | Sevkiyat kaydı, irsaliye                     | Lojistik / Depo Sorumlusu | Müşteri teslimatı                       |
| 12 | Süreç performanslarının izlenmesi                                           | Raporlama ve analiz                           | KPI raporları, performans kayıtları          | Yönetim / Kalite          | İyileştirme faaliyetleri                |
| 13 | Müşteri özel şartları, teknik dokümanlar ve revizyonların kontrolü          | Doküman yönetimi / ürün dokümanı bağlantıları | Teknik doküman kayıtları, revizyon bilgileri | Kalite / Üretim Mühendisi | Üretim ve kalite kontrol faaliyetleri   |

### Faz Çıktıları

Bu fazın tamamlanması ile aşağıdaki çıktılar oluşturulur:

- ERP Süreç Eşleştirme Matrisi
- Operasyonel süreçler ile ERP fonksiyonları arasındaki ilişki tanımı
- Süreç adımlarında oluşturulan kayıtların belirlenmesi
- ERP işlemlerinden sorumlu rollerin belirlenmesi
- Süreçler arası bilgi akışının tanımlanması

### Faz Tamamlanma Kriterleri

Bu faz aşağıdaki kriterlerin sağlanması ile tamamlanmış kabul edilir:

-  Kritik operasyonel süreçler ERP fonksiyonları ile eşleştirilmiştir.
-  Her süreç adımı için oluşturulacak kayıtlar tanımlanmıştır.
-  Süreçlerde görev alacak sorumlu roller belirlenmiştir.
-  Süreçler arasındaki bilgi aktarımı ve devam eden adımlar tanımlanmıştır.
-  ERP Süreç Eşleştirme Matrisi gözden geçirilmiş ve onaylanmıştır.

## Sonuç

Bu aşamanın tamamlanmasıyla birlikte operasyonel süreçler ile ERP sistemi arasındaki ilişki tanımlanmış, süreç bazında oluşturulan kayıtlar ve sorumluluklar belirlenmiş olur. Böylece ERP kullanımına ilişkin ortak bir referans oluşturularak veri standardizasyonu, pilot uygulama, eğitim, doğrulama ve sürekli iyileştirme çalışmalarının kontrollü ve tutarlı şekilde yürütülmesi için gerekli temel yapı sağlanır.





## Onaylar

| Rol | İsim | İmza | Tarih |
|---|---|---|---|
| Genel Müdür | Onur AYDÖRE | [FIELD: Signature or digital approval] | [FIELD: YYYY-MM-DD] |
| Proje Yöneticisi | Ezgi ÖZCAN | [FIELD: Signature or digital approval] | [FIELD: YYYY-MM-DD] |


## Değişiklik Geçmişi

| Versiyon | Tarih | Hazırlayan | Değişiklik Açıklaması |
|---|---|---|---|
| 0.0.0 | 24.09.2026 | Ezgi ÖZCAN | ERP Süreç Eşleştirme Fazı  |

 \---