\
---
name: "Operasyonel Süreç Keşfi ve Gap Analizi"
template_version: "0.0.0"
status: "Active"
category: "Governance"
authority: "Implementing AS9100 8.5.6"
file_path: "02_Operasyonel_Surec_Kesfi_Gap_Analizi/operational-process-discovery-gap-analysis.md"
---

# Operasyonel Süreç Keşfi ve Gereksinim Analizi

**Artifact ID:** ERP002  
**Artifact Name:** "Operasyonel Süreç Keşfi ve Gap Analizi"  
**Template Version:** 0.0.0  
**Status:** Active  
**Authority:** "Implementing AS9100 8.5.6 "  
**File Path:** `02_Operasyonel_Surec_Kesfi_Gap_Analizi/operational-process-discovery-gap-analysis.md`

> **Usage note:** Mevcut durum analizi ve gereksinim belirleme çalışmaları, kuruluşun mevcut operasyonel yapısı, erişilebilir kayıtlar ve ilgili personel görüşleri temel alınarak gerçekleştirilir. Bu aşamada mevcut olmayan veya yeterli bilgi bulunmayan süreçler için varsayım oluşturulmamalı, eksik bilgiler açık şekilde belirtilerek sonraki proje fazlarında detaylandırılması planlanmalıdır. Operasyonel Süreç Keşfi ve Gereksinim Analizi çıktıları, ERP süreç tasarımı ve sistem yapılandırma çalışmalarına girdi sağlamak amacıyla hazırlanır ve nihai süreç tasarım dokümanı yerine kullanılmamalıdır.

---

## Proje Kimliği

| --- | --- |
|---|---|
| **Proje Adı** | ERP Entegrasyonu Operasyonel Süreç Keşfi ve Gap Analizi Aşaması |
| **Proje ID / Kodu** | ERP002 |
| **Proje Türü** | Değişiklik Yönetimi Sürecinin Oluşturulması |
| **Başlatma Belgesi Tarihi** | 24.09.2026 |
| **Belge Versiyonu** | .v000 |
| **Hazırlayan** | Ezgi ÖZCAN |

---

## Operasyonel Süreç Keşfi ve Gereksinim Analizi

### Bu Aşamanın Amacı

Bu fazın amacı, ERP uygulama projesi kapsamında kuruluşun mevcut operasyonel yapısının, süreçlerinin, müşteri gereksinimlerinin ve kalite yönetim sistemi ihtiyaçlarının analiz edilmesidir.

Çalışma kapsamında mevcut süreçlerin nasıl yürütüldüğü, kullanılan bilgi kaynakları, mevcut kayıt yapıları, operasyonel ihtiyaçlar ve AS9100 Rev.D gereklilikleri değerlendirilerek ERP sisteminin desteklemesi gereken fonksiyonlar belirlenmiştir.

Bu fazda gerçekleştirilen analizler, mevcut durumun ortaya konulması (Current State Assessment), süreç kapsamının belirlenmesi (Process Inventory), müşteri ve operasyonel gereksinimlerin değerlendirilmesi (Customer & Operational Requirement Review), mevcut durum ile hedeflenen yapı arasındaki farkların belirlenmesi (AS9100 / ERP Gap Analysis) ve ERP uygulama gereksinimlerinin tanımlanması (ERP Requirement Catalogue) çalışmalarını kapsamaktadır.

Elde edilen çıktılar, sonraki fazda gerçekleştirilecek ERP süreç tasarımı, sistem yapılandırması, ana veri yönetimi ve uygulama faaliyetleri için temel girdi olarak kullanılacaktır.

### Mevcut Başlangıç Koşulları

Kuruluş ERP uygulamasına yeni başlamış olup süreçlerin önemli bölümü oluşturulma aşamasındadır. Ana veri yapısı, kalite kayıtları, izlenebilirlik sistemi ve operasyonel standartlar geliştirilmektedir. ERP uygulaması pilot kullanım seviyesindedir.

Bu nedenle gerçekleştirilen mevcut durum analizleri; mevcut kayıtlar, erişilebilir dokümanlar, operasyonel gözlemler ve ilgili personel görüşleri temel alınarak gerçekleştirilmiştir.

Bazı süreçler için mevcut uygulamalar henüz standartlaştırılmamış veya dokümante edilmemiş olduğundan, analiz sonuçları mevcut durumun fotoğrafını ortaya koymakta ve geliştirme ihtiyaçlarını tanımlamaktadır. Nihai süreç yapıları ve sistem kullanımı, sonraki fazlarda gerçekleştirilecek tasarım ve uygulama çalışmaları sonucunda oluşturulacaktır.

### Kullanılan Yaklaşım

Bu fazdaki çalışmalar aşağıdaki yaklaşımlar dikkate alınarak gerçekleştirilmiştir:

- AS9100 Rev.D proses yaklaşımı: Süreçlerin tanımlanması, etkileşimlerinin değerlendirilmesi ve kalite gerekliliklerinin belirlenmesi.
- IAQG süreç yaklaşımı: Havacılık sektöründe süreç yönetimi, müşteri gereklilikleri ve operasyonel kontrol bakış açısı.
- PMI proje yönetimi yaklaşımı: Proje çıktılarının, kapsamının ve ilerleyen fazlara aktarılacak girdilerin sistematik şekilde yönetilmesi.
- Gereksinim analiz yaklaşımı: ERP sisteminin desteklemesi gereken fonksiyonların ve ihtiyaçların belirlenmesi.

### Çalışma Çıktıları

Bu faz sonunda aşağıdaki çıktılar oluşturulmuştur:

| Çıktı | Açıklama |
|---|---|
|Mevcut Durum Değerlendirmesi (Current State Assessment)|ERP projesine başlangıç koşullarının ve mevcut durumun değerlendirilmesi|
|Süreç Envanteri (Process Inventory)|ERP kapsamındaki temel süreçlerin belirlenmesi|
|Gereksinim Gözden Geçirme (Customer & Operational Requirement Review)|Müşteri ve operasyon gereksinimlerinin değerlendirilmesi|
|ERP Uygulama Gereksinimleri ve Sistem Entegrasyon Tablosu | ERP üzerinde yönetilecek fonksiyonların ve ilişkili sistem gereksinimlerinin tanımlanması

## 1 — Mevcut Durum Değerlendirmesi

Bu çalışma, ERP uygulama projesinin başlangıcında kuruluşun mevcut operasyonel yapısını, süreç olgunluğunu, kayıt yönetimini ve kalite yönetim sistemi altyapısını objektif olarak değerlendirmek amacıyla hazırlanmıştır.

Değerlendirme; AS9100 Rev.D proses yaklaşımı, PMI proje yönetimi prensipleri ve IAQG Process Approach rehberleri esas alınarak gerçekleştirilmiştir. Bu bölümün amacı mevcut sistemi değerlendirmek veya eksiklikleri eleştirmek değil, ERP uygulama projesinin başlangıç koşullarını (baseline) belirlemek ve sonraki proje fazlarına güvenilir bir referans oluşturmaktır.

Bu değerlendirme ile "ERP projesine hangi operasyonel, organizasyonel ve kalite yönetim sistemi koşullarında başlandı?" sorusuna cevap verilmesi hedeflenmektedir.

1. Organizasyonel Yapı

Kuruluş, havacılık ve savunma sanayine yönelik talaşlı imalat faaliyetleri gerçekleştiren, kalite yönetim sistemi ve ERP altyapısını eş zamanlı olarak geliştirme sürecinde bulunan genç bir organizasyondur.

ERP sistemi kuruluş içerisinde yeni uygulanmaya başlanmış olup, operasyonel süreçlerin önemli bir bölümü henüz standartlaştırma aşamasındadır. Organizasyon yapısı, görev dağılımları ve süreç sahiplikleri geliştirilmeye devam etmektedir.

Yönetim tarafından ERP sisteminin kullanılmasına karar verilmiş ve dijital dönüşüm çalışmaları başlatılmıştır.

2. Operasyonel Yapı

Kuruluşta üretim faaliyetleri ağırlıklı olarak müşteri siparişleri doğrultusunda gerçekleştirilen talaşlı imalat operasyonlarından oluşmaktadır.

İş akışı genel olarak müşteri Purchase Order (PO), teknik resim ve teknik şartnamelerin incelenmesi ile başlamakta, üretim faaliyetleri tamamlandıktan sonra ürün müşteriye sevk edilmektedir.

Birçok projede kullanılan hammadde müşteri tarafından sağlanmaktadır (Customer Supplied Material). Bu nedenle malzeme yönetimi süreçleri müşteri gereksinimleri ile doğrudan ilişkilidir.

Operasyonel faaliyetler yürütülmekte olmakla birlikte süreçlerin standartlaştırılması, sorumlulukların tanımlanması ve kayıt yönetiminin geliştirilmesine yönelik çalışmalar devam etmektedir.

3. Kalite Yönetim Sistemi Altyapısı

Kuruluşta AS9100 Rev.D tabanlı kalite yönetim sisteminin oluşturulmasına yönelik çalışmalar devam etmektedir.

Kalite yönetim sistemine ait prosedürler, süreçler, formlar ve kayıt yapıları proje kapsamında oluşturulmaktadır.

Kalite kontrol faaliyetleri belirli ölçüde uygulanmakla birlikte kontrol kriterleri, kabul şartları, kontrol planları ve kalite kayıtlarının standardizasyon çalışmaları henüz tamamlanmamıştır.

İzlenebilirlik, ürün yaşam döngüsü kayıtları, lot/heat number yönetimi ve kalite kayıtlarının ERP ile bütünleşik şekilde yönetilmesine yönelik altyapı oluşturulmaktadır.

4. ERP Uygulama Durumu

Scienta ERP sistemi kuruluş tarafından satın alınmış ve uygulamaya alınmıştır.

Sistem aktif olmakla birlikte ERP kullanımı pilot uygulama aşamasındadır.

ERP içerisinde temel kullanıcı tanımlamaları yapılmış, ilk müşteri kayıtları, stok kartları ve örnek sipariş girişleri oluşturulmaya başlanmıştır.

Ana veri (Master Data) yapısı, ürün kartları, operasyon rotaları, ürün ağaçları ve diğer temel ERP bileşenlerinin oluşturulmasına yönelik çalışmalar devam etmektedir.

ERP sistemi henüz kuruluşun tüm operasyonlarını kapsayacak olgunluk seviyesine ulaşmamış olup, süreçlerin doğrulanması ve standartlaştırılması proje kapsamında gerçekleştirilecektir.

5. Dokümante Edilmiş Bilgi

Kuruluşta operasyonların önemli bölümü uygulamaya dayalı olarak yürütülmekte olup dokümante edilmiş bilgi altyapısı geliştirme aşamasındadır.

Müşteri Purchase Order'ları, teknik resimler ve müşteri spesifikasyonları operasyonların temel girdilerini oluşturmaktadır.

ERP sistemi ile birlikte operasyonel kayıtların dijital ortamda oluşturulması ve standardize edilmesi hedeflenmektedir.

6. İzlenebilirlik

İzlenebilirlik sistemi geliştirme aşamasındadır.

Malzeme, üretim, operasyon ve sevkiyat bilgilerinin ERP üzerinden uçtan uca izlenebilmesini sağlayacak kayıt yapılarının oluşturulması proje kapsamındadır.

Lot numarası, Heat Number, operasyon geçmişi, kalite kayıtları ve ürün geçmişinin ERP üzerinden yönetilmesi hedeflenmektedir.

7. Yetkinlik ve ERP Kullanımı

ERP sistemi kuruluş içerisinde ilk kez uygulanmaktadır.

ERP'nin aktif kullanımı başlangıç aşamasında sınırlı sayıda kullanıcı tarafından yürütülmekte olup sistem kullanımına yönelik kurumsal bilgi birikimi oluşturulmaktadır.

ERP kullanımına ilişkin görev tanımları, yetkilendirme yapısı, eğitim planları ve yetkinlik değerlendirme sistemi proje ilerleyen fazlarında oluşturulacaktır.

8. Genel Değerlendirme

ERP uygulama projesi, operasyonel süreçlerin ve kalite yönetim sisteminin eş zamanlı olarak oluşturulduğu bir başlangıç döneminde başlatılmıştır.

Kuruluşta operasyonlar fiilen yürütülmekle birlikte süreçlerin standardizasyonu, kayıt yönetimi, kalite kontrol yapısı, izlenebilirlik sistemi ve ERP ana veri yönetimi geliştirme aşamasındadır.

Bu nedenle proje kapsamında yalnızca bir ERP yazılımının devreye alınması değil; AS9100 Rev.D gerekliliklerini destekleyecek süreçlerin, kayıt yapılarının ve dijital operasyon altyapısının sistematik olarak oluşturulması hedeflenmektedir.

## 2 — Operasyonel Süreç Envanteri

Bu çalışma, ERP uygulama projesi kapsamında kuruluşta yürütülen veya ERP sistemi ile birlikte oluşturulması planlanan operasyonel süreçlerin sistematik olarak belirlenmesi amacıyla hazırlanmıştır.

Süreç envanteri; AS9100 Rev.D proses yaklaşımı, IAQG Process Approach ve BPM (Business Process Management) prensipleri esas alınarak hazırlanmıştır.

Bu bölümün amacı mevcut süreçlerin ayrıntılı iş akışlarını tanımlamak değil; ERP sistemi tarafından desteklenecek süreçleri belirlemek, süreç kapsamını oluşturmak ve sonraki proje fazlarında gerçekleştirilecek ERP fonksiyon eşleştirme, ana veri yönetimi, görev dağılımları ve doğrulama çalışmalarına temel oluşturmaktır.

Bu çalışma ile "ERP sistemi hangi operasyonel süreçleri destekleyecek?" sorusuna cevap verilmesi hedeflenmektedir.

Aşağıda yer alan süreçler, kuruluşun mevcut faaliyetleri ile AS9100 Rev.D gereklilikleri dikkate alınarak belirlenmiştir. Süreçlerin mevcut olgunluk seviyeleri değerlendirilmiş ve ERP uygulama projesi kapsamındaki geliştirme ihtiyaçları tanımlanmıştır.

|Süreç|Mevcut Durum|ERP Kapsamı|Geliştirme Durumu|
|---|---|---|---|
|Teklif ve Fırsat Yönetimi|Oluşturulacak|✔|ERP ile yapılandırılacak|
Müşteri Sipariş Yönetimi|Kısmen Mevcut|✔|Standardizasyon gerekli|
|Sözleşme / Sipariş Gözden Geçirme|	Oluşturulacak|✔|AS9100 gerekliliklerine göre oluşturulacak|
|Ana Veri Yönetimi (Master Data)|	Oluşturuluyor	|✔|	Kodlama standartları oluşturulacak|
|Ürün Kartı Yönetimi|	Oluşturuluyor|	✔|	ERP içerisinde geliştiriliyor|
|Stok Yönetimi	|Oluşturuluyor	|✔	|ERP ile yönetilecek|
|Malzeme İzlenebilirliği	| Oluşturulacak|	✔	|ERP üzerinden yönetilecek|
|Üretim Planlama	|Kısmen Mevcut	|✔|	Standardizasyon gerekli|
|İş Emri Yönetimi	|Oluşturuluyor|	✔|	ERP ile oluşturulacak|
|Operasyon Rotaları	|Oluşturuluyor|	✔	|Standart hale getirilecek|
|Ürün Ağacı (BOM) Yönetimi	|Oluşturuluyor	|✔|	ERP altyapısı oluşturuluyor|
|Üretim Operasyonları	|Kısmen Mevcut	|✔|	ERP entegrasyonu geliştirilecek|
|Ara Kontrol|Kısmen Mevcut	|✔	|Kalite sistemi ile birlikte geliştirilecek|
|Final Kontrol|	Kısmen Mevcut|	✔|	GKK yapısı oluşturulacak|
|Uygun Olmayan Ürün Yönetimi	|Oluşturulacak	|✔|	Süreç oluşturulacak|
|Düzeltici Faaliyet (DÖF)	|Oluşturulacak|	Kısmen|	KYS kapsamında geliştirilecek|
|Ölçüm Ekipmanı Yönetimi	|Oluşturulacak|	Kısmen|	Kalibrasyon sistemi ile entegre edilecek|
|Sevkiyat Yönetimi	|Mevcut|	✔|	ERP kayıtları ile desteklenecek|
|Doküman ve Kayıt Yönetimi|	Oluşturuluyor|	✔|	ERP ve KYS entegrasyonu sağlanacak|

### Süreç Gruplandırması

Süreçlerin daha kolay yönetilebilmesi amacıyla operasyonlar aşağıdaki ana süreç grupları altında değerlendirilmiştir.

#### Yönetim Süreçleri
- Proje Yönetimi
- Kalite Yönetim Sistemi
- Risk Yönetimi
- Doküman Yönetimi

#### Operasyonel Süreçler
- Teklif Yönetimi
- Sipariş Yönetimi
- Sözleşme Gözden Geçirme
- Ana Veri Yönetimi
- Üretim Planlama
- İş Emri Yönetimi
- Üretim
- Kalite Kontrol
- Sevkiyat

#### Destek Süreçleri
- Satınalma
- Depo ve Stok Yönetimi
- Kalibrasyon
- Eğitim ve Yetkinlik
- Bakım (ileride kapsam dahilinde değerlendirilmesi planlanmaktadır.)

#### Genel Değerlendirme

Süreç envanteri incelendiğinde kuruluşta temel operasyonel faaliyetlerin yürütüldüğü, ancak süreçlerin önemli bir bölümünün henüz standartlaştırılma aşamasında olduğu görülmektedir.

ERP uygulama projesi kapsamında süreçlerin yalnızca ERP içerisinde dijital ortama aktarılması değil; aynı zamanda süreç sahipliklerinin belirlenmesi, standart operasyonların oluşturulması, kayıt yapılarının geliştirilmesi ve AS9100 Rev.D gereklilikleri ile uyumlu hale getirilmesi hedeflenmektedir.

Bu nedenle süreç envanteri, mevcut operasyonların bir listesi olmanın ötesinde, ERP sistemi tarafından desteklenecek hedef operasyonel yapının kapsamını tanımlayan temel referans dokümandır.

## 3 — Müşteri ve Operasyonel Gereksinimlerin Değerlendirilmesi

Bu çalışma, ERP uygulama projesi kapsamında müşteri gereksinimlerinin, operasyonel ihtiyaçların ve AS9100 Rev.D kalite yönetim sistemi gerekliliklerinin sistematik olarak belirlenmesi amacıyla hazırlanmıştır.

Çalışma; AS9100 Rev.D Madde 8.2 (Ürün ve Hizmetlere İlişkin Şartların Belirlenmesi ve Gözden Geçirilmesi), IAQG süreç yaklaşımı, BABOK gereksinim analizi prensipleri ve IEEE 29148 Gereksinim Yönetimi yaklaşımı dikkate alınarak hazırlanmıştır.

Bu bölümün amacı yalnızca mevcut müşteri taleplerini listelemek değil; ERP sistemi içerisinde yönetilmesi gereken tüm kritik operasyonel bilgileri belirlemek ve sonraki fazlarda gerçekleştirilecek ERP fonksiyon eşleştirme çalışmalarına temel oluşturmaktır.

Bu çalışma ile aşağıdaki sorulara cevap verilmesi hedeflenmektedir:

- Müşteriden hangi bilgiler alınmaktadır?
- Üretimin başlayabilmesi için hangi bilgiler gereklidir?
- ERP sistemi hangi bilgileri yönetebilmelidir?
- AS9100 hangi kayıtların oluşturulmasını beklemektedir?

### Gereksinim Kaynakları

ERP gereksinimleri aşağıdaki bilgi kaynakları dikkate alınarak belirlenmiştir.

|Gereksinim Kaynağı|	Açıklama|
|---|---|
|Müşteri Purchase Order (PO)	|Sipariş kapsamı ve ticari bilgiler|
|Teknik Resimler	|Üretim gereklilikleri|
|Teknik Şartnameler	|Malzeme ve proses gereklilikleri|
|Müşteri Revizyonları	|Güncel teknik gereklilikler|
|AS9100 Rev.D	|Kalite yönetim sistemi gereklilikleri|
|Operasyonel Gözlemler|	Mevcut uygulamalar|
|ERP Uygulama İhtiyaçları	|Dijital süreç yönetimi gereklilikleri|


#### Müşteri Gereksinimleri

ERP sistemi içerisinde aşağıdaki müşteri bilgilerinin yönetilmesi hedeflenmektedir.

- Müşteri adı
- Purchase Order (PO) numarası
- Parça numarası
- Parça açıklaması
- Revizyon bilgisi
- Teknik resim referansı
- İstenen miktar
- Teslim tarihi
- Malzeme bilgisi
- Müşteri tarafından sağlanan malzeme bilgisi (Customer Supplied Material)
- Özel müşteri gereklilikleri (varsa)

#### Operasyonel Gereksinimler

Üretim faaliyetlerinin yönetilebilmesi için ERP sistemi içerisinde aşağıdaki operasyonel bilgilerin oluşturulması hedeflenmektedir.

- Ürün kartı
- Stok kartı
- Operasyon rotası
- Ürün ağacı (BOM)
- İş emri
- Operasyon sırası
- Üretim durumu
- Malzeme tüketimi
- Sevkiyat bilgileri

#### Kalite Yönetim Sistemi Gereksinimleri

AS9100 Rev.D doğrultusunda ERP sistemi tarafından desteklenmesi hedeflenen temel kalite gereklilikleri aşağıda verilmiştir.

- Ürün izlenebilirliği
- Lot / Heat Number takibi
- Doküman revizyon kontrolü
- Operasyon kayıtlarının saklanması
- Kalite kontrol kayıtları
- Uygun olmayan ürün kayıtları
- Düzeltici faaliyet kayıtları
- Ölçüm ekipmanı bilgileri
- Eğitim ve yetkinlik kayıtları
- Dokümante edilmiş bilgi yönetimi

#### Gereksinim Değerlendirme Özeti

Her gereksinim aşağıdaki kriterler doğrultusunda değerlendirilecektir.

|Değerlendirme Kriteri	|Açıklama|
|---|---|
|Gereksinim Tanımlandı mı?	|Bilgi açık olarak belirlenmiş mi?|
|Kaynağı Belirlendi mi?	|Gereksinimin kaynağı tanımlandı mı?|
|ERP'de Yönetilecek mi?	|ERP sistemi içerisinde takip edilecek mi?|
|AS9100 ile İlişkili mi?	|Standart gerekliliği bulunuyor mu?|
|Sonraki Fazda Çalışılacak mı?|	ERP tasarımına aktarılacak mı?|

### Genel Değerlendirme

Yapılan değerlendirme sonucunda kuruluşta üretim faaliyetlerinin temel olarak müşteri siparişleri ve teknik dokümanlar doğrultusunda yürütüldüğü görülmüştür.

Ancak operasyonel bilgilerin önemli bir bölümü standartlaştırılmış kayıt yapıları ile yönetilmemektedir. Bu nedenle ERP uygulama projesi kapsamında müşteri gerekliliklerinin, operasyonel ihtiyaçların ve kalite yönetim sistemi beklentilerinin ortak bir veri yapısı altında yönetilmesi hedeflenmektedir.

Bu çalışma sonucunda belirlenen gereksinimler, sonraki fazlarda hazırlanacak ERP Fonksiyon Eşleştirme Matrisi, Ana Veri Yönetimi Kuralları ve Doğrulama Planlarının temel girdisini oluşturacaktır.

## 4 — AS9100 ve ERP Uyum Boşluk Analizi

Bu çalışma, ERP uygulama projesi kapsamında kuruluşun mevcut operasyonel yapısı ile AS9100 Rev.D kalite yönetim sistemi gereklilikleri arasındaki boşlukların belirlenmesi amacıyla hazırlanmıştır.

Boşluk analizi; AS9100 Rev.D, IAQG süreç yaklaşımı, ISO 9001:2015 proses yaklaşımı ve Fit-Gap Analysis metodolojisi esas alınarak gerçekleştirilmiştir.

Bu bölümün amacı eksiklikleri tespit etmekten ziyade, ERP uygulama projesi kapsamında geliştirilmesi gereken süreçleri, kayıt yapılarını ve sistem fonksiyonlarını belirleyerek sonraki proje fazlarına girdi sağlamaktır.

Bu çalışma ile aşağıdaki sorulara cevap verilmesi hedeflenmektedir:

AS9100 hangi gereklilikleri beklemektedir?
Mevcut durumda hangi uygulamalar bulunmaktadır?
ERP sistemi bu gereklilikleri nasıl destekleyecektir?
Proje kapsamında hangi geliştirmeler yapılacaktır?

### Değerlendirme Metodu

Her konu aşağıdaki dört kriter dikkate alınarak değerlendirilmiştir.

|Kriter|	Açıklama|
|---|---|
|AS9100 Beklentisi	|Standardın ilgili konuda beklediği uygulama|
|Mevcut Durum|	Kuruluşta mevcut uygulama seviyesi|
|ERP ile Hedeflenen Durum|ERP uygulaması sonrasında ulaşılması planlanan yapı|
|Geliştirme İhtiyacı|	Proje kapsamında gerçekleştirilecek çalışmalar|

### Gap Analysis Tablosu

|Konu|AS9100 Beklentisi|Mevcut Durum|ERP ile Hedeflenen Durum|Öncelik|
|---|---|---|---|---|
|Dokümante Edilmiş Bilgi|Kontrollü doküman yönetimi|Geliştirme aşamasında|ERP destekli doküman ve kayıt yönetimi|Yüksek|
|Müşteri Gereksinimleri|	Şartların gözden geçirilmesi ve kayıt altına alınması|	PO ve teknik dokümanlar kullanılmaktadır|	ERP üzerinden sistematik sipariş yönetimi	|Kritik|
|Ana Veri Yönetimi|	Tutarlı ve kontrollü veri yapısı|	Oluşturulmaktadır|	Standart kodlama ve merkezi veri yönetimi|	Kritik
|Ürün Ağacı (BOM)|	Üretim bilgilerinin tanımlanması	|Oluşturulmaktadır|ERP üzerinden yönetilen ürün ağaçları	|Yüksek
|Operasyon Rotaları	|Üretim operasyonlarının tanımlanması	|Oluşturulmaktadır|ERP operasyon yönetimi|	Yüksek|
|İş Emri Yönetimi	|Planlı üretim kayıtları	|Pilot kullanım	|ERP üzerinden uçtan uca iş emri yönetimi	|Kritik|
|İzlenebilirlik|Ürün ve malzeme izlenebilirliği	|Geliştirme aşamasında|	Lot Number ve operasyon geçmişi takibi	|Kritik|
|Giriş Kalite Kontrol|	Girdi doğrulama faaliyetleri	|Süreç oluşturulacaktır|	ERP destekli GKK kayıtları	|Kritik|
|Ara Kontrol|	Operasyon doğrulama|	Süreç oluşturulacaktır	|ERP ile kayıt altına alınacaktır	|Orta|
|Final Kontrol|	Son ürün doğrulaması|	Kısmen uygulanmaktadır|	ERP destekli final kalite kayıtları	|Kritik
|Uygun Olmayan Ürün|	Tanımlama ve kontrol	|Süreç oluşturulacaktır	|ERP destekli uygunsuzluk yönetimi	|Yüksek|
|Kalibrasyon	|Ölçüm ekipmanı yönetimi	|Geliştirilmektedir	|ERP veya KYS kayıtları ile izlenecektir|Orta|
|Eğitim ve Yetkinlik	|Yetkin personel	|Sistem oluşturulacaktır	|Eğitim kayıtları ve yetkinlik değerlendirmeleri|	Orta|
|Görev ve Yetkilendirme	|Sorumlulukların tanımlanması	|Geliştirme aşamasında	|ERP rol ve yetki yönetimi ile desteklenecektir	|Yüksek
|Performans İzleme	|Süreç performansının ölçülmesi	|KPI yapısı oluşturulacaktır	|ERP verileri ile desteklenen performans göstergeleri|	Orta|

### Gap Analizi Sonuçları

Yapılan değerlendirme sonucunda aşağıdaki temel geliştirme alanları belirlenmiştir.

#### Kritik Öncelikli Konular
- Ana veri yönetiminin standardize edilmesi
- Ürün izlenebilirlik yapısının oluşturulması
- Müşteri gerekliliklerinin sistematik olarak yönetilmesi
- İş emri yönetiminin ERP üzerinden yürütülmesi
- Giriş kalite kontrol sürecinin oluşturulması
- Final kalite kontrol kayıtlarının standardize edilmesi

#### Orta Vadede Geliştirilecek Konular
- Eğitim ve yetkinlik yönetimi
- Performans göstergelerinin oluşturulması
- Kalibrasyon kayıtlarının entegrasyonu
- Ara kontrol kayıtlarının oluşturulması

#### Uzun Vadeli İyileştirme Alanları
- Süreç performans analizlerinin otomatik raporlanması
- Dijital onay mekanizmalarının kullanılması
- Yönetim raporlarının ERP üzerinden oluşturulması
- Sürekli iyileştirme göstergelerinin ERP verileri ile desteklenmesi

#### Sonuç

Yapılan boşluk analizi, kuruluşta temel operasyonel faaliyetlerin yürütüldüğünü; ancak AS9100 Rev.D gerekliliklerini tam olarak destekleyecek standart süreçler, kayıt yapıları ve dijital yönetim altyapısının geliştirilmesine ihtiyaç duyulduğunu göstermektedir.

ERP uygulama projesi yalnızca mevcut faaliyetlerin dijital ortama aktarılmasını değil, aynı zamanda süreçlerin standardize edilmesini, izlenebilirliğin artırılmasını, dokümante edilmiş bilgi yönetiminin güçlendirilmesini ve kalite yönetim sistemi gerekliliklerinin sistematik olarak desteklenmesini hedeflemektedir.

Bu çalışma sonucunda belirlenen boşluklar, sonraki proje fazlarında gerçekleştirilecek süreç tasarımı, ERP yapılandırması, ana veri yönetimi, pilot uygulama ve doğrulama faaliyetlerine temel girdi sağlayacaktır.

## 4 — ERP Uygulama Gereksinimleri ve Sistem Entegrasyon Kataloğu

Bu çalışma, ERP uygulama projesi kapsamında belirlenen müşteri gereksinimlerini, operasyonel ihtiyaçları ve AS9100 Rev.D kalite yönetim sistemi gerekliliklerini tek bir izlenebilir yapı altında toplamak amacıyla hazırlanmıştır.

ERP Gereksinim Kataloğu; AS9100 Rev.D, IAQG süreç yaklaşımı, IEEE 29148 Gereksinim Yönetimi ve BABOK Business Analysis prensipleri esas alınarak oluşturulmuştur.

Bu bölümün amacı ERP sisteminden beklenen fonksiyonları tanımlamak, gereksinimlerin kaynağını belirlemek ve proje boyunca gerçekleştirilecek geliştirme faaliyetlerinin izlenebilirliğini sağlamaktır.

Bu çalışma ile aşağıdaki sorulara cevap verilmesi hedeflenmektedir:

- ERP sistemi hangi fonksiyonları desteklemelidir?
- Bu gereksinimin kaynağı nedir?
- Gereksinim hangi AS9100 maddesi ile ilişkilidir?
- Gereksinim hangi ERP modülünü etkilemektedir?
- Gereksinim hangi proje fazında doğrulanacaktır?

#### Gereksinim Öncelik Seviyeleri

|Öncelik	|Açıklama|
|---|---|
|Kritik|	AS9100 uygunluğu veya operasyonun devamı için zorunludur.|
|Yüksek	|ERP'nin etkin çalışması için gereklidir.|
|Orta	|Verimlilik ve standardizasyon sağlar.|
|Düşük	|İleri fazlarda değerlendirilebilir.|

### ERP Gereksinim Kataloğu

ERP tarafından doğrudan yönetilmeyen ancak AS9100 uyumu, süreç etkinliği ve kayıt izlenebilirliği açısından kritik olan gereksinimler ayrıca belirtilmiştir.

|ERP Gereksinimi|	Kaynak|	AS9100	|ERP Modülü	|Öncelik	|Durum|	Doğrulama Yöntemi|
|---|---|---|---|---|---|---|
|Müşteri kartlarının standart yapıda oluşturulması	|Operasyon	|8.2|	Satış	|Kritik	|Planlandı|	Oluşturulan müşteri kartları standart veri alanları açısından incelenerek doğrulanacaktır.|
Purchase Order bilgilerinin kayıt altına alınması|	Müşteri	|8.2|	Satış|	Kritik|	Pilot|	Test amaçlı bir müşteri siparişi ERP'ye girilerek PO bilgilerinin eksiksiz kaydedildiği doğrulanacaktır.|
|Ürün kartlarının standart kodlama ile oluşturulması	|Operasyon	|8.5	|Stok	|Kritik	|Devam Ediyor	|Oluşturulan ürün kartları belirlenen kodlama standardına göre kontrol edilecektir.|
|Stok kartlarının standartlaştırılması	|Operasyon	|8.5|	Stok	|Kritik|	Devam Ediyor	|Örnek stok kartları incelenerek zorunlu alanların eksiksiz doldurulduğu doğrulanacaktır.|
|Ürün Ağacı (BOM) oluşturulması	|Üretim|	8.5|	Üretim	|Kritik	|Planlandı|	Seçilen bir ürün için BOM oluşturularak malzeme ilişkileri kontrol edilecektir.|
|Operasyon rotalarının tanımlanması|	Üretim|	8.5	|Üretim	|Kritik|	Planlandı	|Test ürünü üzerinden operasyon sıralaması oluşturularak doğrulanacaktır.|
|İş emri oluşturulması|	Üretim|	8.5|	Üretim|	Kritik|	Planlandı|	Test siparişinden iş emri oluşturularak süreç uçtan uca kontrol edilecektir.|
|Müşteri tarafından sağlanan malzemenin takip edilmesi	|Müşteri|	8.5.3	|Stok|Kritik|	Planlandı|	Customer Supplied Material içeren örnek sipariş ile malzeme hareketleri doğrulanacaktır.|
|Lot / Heat Number bilgilerinin kayıt altına alınması|	AS9100|	8.5.2|	Stok|	Kritik	|Planlandı|	Test malzemesi üzerinden lot/heat numarası girilerek izlenebilirlik doğrulanacaktır.|
|Üretim operasyonlarının izlenmesi	|Operasyon|	8.5|	Üretim|Yüksek|	Planlandı	|İş emri ilerleme kayıtları ERP üzerinden takip edilerek doğrulanacaktır.|
|Giriş Kalite Kontrol kayıtlarının oluşturulması|	AS9100|	8.6	|Kalite|	Kritik|	Planlandı|	GKK kaydı oluşturularak kontrol sonuçlarının ERP'de saklandığı doğrulanacaktır.|
|Ara kontrol kayıtlarının oluşturulması	|Kalite	|8.6|	Kalite|	Orta|	Planlandı	|Örnek operasyon için ara kontrol kaydı oluşturularak doğrulanacaktır.|
|Final kontrol kayıtlarının oluşturulması|	AS9100	|8.6|	Kalite|	Kritik|	Planlandı	|Final kalite kontrol kaydı oluşturularak ürün serbest bırakma süreci doğrulanacaktır.|
|Uygun olmayan ürün kayıtlarının yönetilmesi|	AS9100	|8.7	|Kalite	|Yüksek	|Planlandı	|Test amaçlı uygunsuz ürün senaryosu oluşturularak kayıt süreci doğrulanacaktır.|
|Sevkiyat kayıtlarının oluşturulması	|Operasyon|	8.6	|Sevkiyat|	Yüksek|	Planlandı	|Tamamlanan test siparişi üzerinden sevkiyat kaydı oluşturularak doğrulanacaktır.|
|Doküman revizyon bilgilerinin yönetilmesi|	AS9100|	7.5	|Doküman Yönetimi veya ERP Dışı KYS	|Yüksek	|Planlandı	|Revizyonlu teknik resim kullanılarak güncel revizyon bilgisinin yönetildiği doğrulanacaktır.|
|Eğitim ve yetkinlik kayıtlarının tutulması|	AS9100|	7.2	|ERP Dışı KYS Yönetimi|	Orta|	Planlandı|	Eğitim katılım kaydı ve eğitim değerlendirme formu incelenerek doğrulanacaktır.|
|Ölçüm ekipmanı bilgilerinin izlenmesi	|AS9100	|7.1.5	|ERP Dışı KYS Yönetimi / Kalibrasyon Takibi|	Orta	|Planlandı	|Örnek ölçüm cihazı oluşturularak kalibrasyon bilgilerinin kaydedildiği doğrulanacaktır.|
|Kullanıcı yetkilendirmelerinin tanımlanması|	Operasyon|	7.1|	Sistem Yönetimi	|Yüksek|Planlandı	|Farklı kullanıcı rolleri ile sisteme giriş yapılarak erişim yetkileri doğrulanacaktır.|
|ERP verilerinden performans göstergelerinin üretilebilmesi	|Yönetim|	9.1	|Raporlama / BI|	Orta|	Gelecek Faz	|ERP verileri kullanılarak belirlenen KPI raporlarının oluşturulabildiği doğrulanacaktır.|

#### Genel Değerlendirme

ERP Gereksinim Kataloğu, ERP uygulama projesi boyunca geliştirilecek fonksiyonların temel referans dokümanıdır.

Her gereksinim; müşteri beklentileri, operasyonel ihtiyaçlar ve AS9100 Rev.D kalite yönetim sistemi gereklilikleri dikkate alınarak tanımlanmıştır. Gereksinimler proje ilerledikçe gözden geçirilecek, gerekli durumlarda revize edilecek ve doğrulama faaliyetleri ile etkinliği değerlendirilecektir.

Bu katalog, sonraki fazlarda hazırlanacak süreç tasarımları, ERP yapılandırmaları, test senaryoları, kullanıcı eğitimleri ve kabul kriterleri için temel girdi olarak kullanılacaktır.

## Sonuç

Bu faz kapsamında kuruluşun mevcut operasyonel yapısı, süreçleri, müşteri gereksinimleri ve ERP uygulamasına ilişkin ihtiyaçları sistematik olarak değerlendirilmiştir. Gerçekleştirilen analizler sonucunda mevcut durum ortaya konulmuş, ERP uygulamasının desteklemesi gereken temel fonksiyonlar belirlenmiş ve AS9100 Rev.D gereklilikleri doğrultusunda geliştirilmesi gereken alanlar tespit edilmiştir.

Yapılan değerlendirmeler, kuruluşun ERP uygulamasına başlangıç seviyesinde olduğunu; süreçlerin, kayıt yapılarının ve kalite yönetim sistemi uygulamalarının önemli ölçüde geliştirilmesi gerektiğini göstermektedir. Bu durum, projenin yalnızca bir yazılım uygulaması değil, aynı zamanda süreçlerin standardizasyonunu ve kalite yönetim sisteminin güçlendirilmesini hedefleyen bir dönüşüm çalışması olduğunu ortaya koymaktadır.

Bu faz sonunda oluşturulan mevcut durum değerlendirmesi, süreç envanteri, gereksinim analizleri, boşluk analizi ve ERP uygulama gereksinimleri; sonraki fazlarda gerçekleştirilecek süreç tasarımı, ERP yapılandırması, ana veri yönetimi, görev ve sorumlulukların belirlenmesi ile doğrulama çalışmalarının temel girdisini oluşturacaktır.

Bir sonraki fazda, bu analizlerden elde edilen çıktılar kullanılarak ERP süreçleri tasarlanacak, süreçler standartlaştırılacak, ERP modülleri ile operasyonel faaliyetler ilişkilendirilecek ve kuruluşun ihtiyaçlarına uygun yönetim yapısı oluşturulacaktır.

## Onaylar

| Rol | İsim | İmza | Tarih |
|---|---|---|---|
| Genel Müdür | Onur AYDÖRE | [FIELD: Signature or digital approval] | [FIELD: YYYY-MM-DD] |
| Proje Yöneticisi | Ezgi ÖZCAN | [FIELD: Signature or digital approval] | [FIELD: YYYY-MM-DD] |


## Değişiklik Geçmişi

| Versiyon | Tarih | Hazırlayan | Değişiklik Açıklaması |
|---|---|---|---|
| 0.0.0 | 24.09.2026 | Ezgi ÖZCAN | Proje Başlatma Fazı  |

 \---