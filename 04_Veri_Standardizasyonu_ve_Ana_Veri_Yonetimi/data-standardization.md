\
---
name: "Data standardization"
template_version: "0.0.0"
status: "Active"
category: "Governance"
authority: "Implementing AS9100 8.5.6"
file_path: "04_Veri_Standardizasyonu_ve_Ana_Veri_Yonetimi/data-standardization.md"
---

# ERP Implementation Project Charter

**Artifact ID:** ERP004  
**Artifact Name:** "Veri Standardizasyonu ve Ana Veri Yönetimi"  
**Template Version:** 0.0.0  
**Status:** Active  
**Authority:** "Implementing AS9100 8.5.6 "  
**File Path:** `04_Veri_Standardizasyonu_ve_Ana_Veri_Yonetimi/data-standardization.md`

> **Usage note:** İsteğe Bağlı olarak işaretlenen alanlar yalnızca proje başlatma aşamasında bilginin gerçekten mevcut olmadığı durumlarda ertelenebilir ve planlama sürecinde tamamlanması için bir yaklaşım belirlenmiş olmalıdır. Proje Başlatma Belgesi, kapsamlı proje yönetim planının yerine kullanılmamalıdır.

---

## Proje Kimliği

| --- | --- |
|---|---|
| **Proje Adı** | Veri Standardizasyonu ve Ana Veri Yönetimi Aşaması |
| **Proje ID / Kodu** | ERP004 |
| **Proje Türü** | Değişiklik Yönetimi Sürecinin Oluşturulması |
| **Başlatma Belgesi Tarihi** | 24.09.2026 |
| **Belge Versiyonu** | .v000 |
| **Hazırlayan** | Ezgi ÖZCAN |

---

## 1 — Amaç

Bu fazın amacı, ERP sisteminde kullanılacak ana verilerin standart, tutarlı ve izlenebilir şekilde oluşturulmasını sağlamak; ürün, malzeme, operasyon ve üretim bilgilerinin belirlenen kurallar doğrultusunda yönetilmesini sağlamaktır.

Bu kapsamda ERP içerisinde oluşturulan ana verilerin AS9100 gerekliliklerini destekleyecek şekilde yapılandırılması ve sürdürülebilir bir veri yönetim sistemi oluşturulması hedeflenmektedir.

## 2 — Kapsam

Bu faz aşağıdaki ERP ana veri yapılarını kapsar:

Malzeme ve stok kartları
Ürün kartları
Ürün ağaçları
Üretim rotaları
Operasyon tanımları
Kodlama ve isimlendirme kuralları
Revizyon bilgileri
İzlenebilirlik bilgileri


## 3 — Veri Yönetim Prensipleri

ERP üzerinde oluşturulan ana veriler aşağıdaki prensiplere göre yönetilir:

Her kayıt benzersiz olmalıdır.
Aynı veri tekrar oluşturulmamalıdır.
Teknik bilgiler mümkün olduğunca standart formatta girilmelidir.
Revizyon değişiklikleri kontrollü şekilde takip edilmelidir.
Üretim ve kalite kayıtlarının izlenebilirliğini destekleyecek bilgiler korunmalıdır.

## 4 — Ana Veri Yapısı

ERP ana veri yapısı, birbirleriyle ilişkili temel veri bileşenlerinden oluşmaktadır.

Ana veri ilişkisi aşağıdaki yapı ile yönetilir:

Ürün Kartı: Ürünün temel tanımı ve ERP üzerindeki ana kimliğidir.

Ürün Kartı ile ilişkili veriler:

Malzeme Kartı: Üretimde kullanılan hammadde ve malzemelerin tanımlandığı veri yapısıdır.

Ürün Ağacı: Ürünün üretimi için gerekli malzeme ve alt bileşen ilişkilerini gösteren yapıdır.

Rota: Ürünün üretim sürecinde takip edeceği operasyon akışını tanımlar.

Operasyonlar: Üretim adımlarının, işlem sırasının ve gerekli kontrol noktalarının tanımlandığı veri yapısıdır.

Üretim / Kalite Kayıtları: Ürün, malzeme ve operasyon bilgilerinin kullanılması sonucunda oluşan üretim ve kalite kayıtlarıdır.

Ana veri yapısı aşağıdaki ilişkiyi temsil eder:

-Ürün Kartı

-Malzeme Kartı ve Ürün Ağacı

-Rota ve Operasyon Tanımları

-Üretim ve Kalite Kayıtları

## 5. Veri Standardizasyon Alanları

### 5.1 Ürün ve Malzeme Kodlama Standardı

#### Amaç:

ERP içerisinde ürün ve malzemelerin standart kod yapısıyla oluşturulmasını sağlamak.

#### Kurallar:

Her ürün/malzeme için tekil kod kullanılır.
Kodlar tekrar kullanılmaz.
Kod yapısı belirlenen isimlendirme sistemine uygun oluşturulur.

Mevcut uygulamalar:

Örnek:

CS-6AL-4V-001

Malzeme örneği:

CS → Malzeme kategorisi (Custemer Supply)
6AL-4V → Malzeme tipi
001 → sıra numarası

(Kodlama yapısı ilerleyen aşamada standart doküman ile kesinleştirilecektir.)

### 5.2 Stok Kartı Standardı

Stok kartlarında aşağıdaki temel bilgiler kontrol edilir:

- Parça numarası
- Tanım
- Malzeme bilgisi
- Birim bilgisi
- Revizyon bilgisi
- Teknik doküman referansı
- Lot/Heat Number takip ihtiyacı

### 5.3 Ürün Ağacı Standardı

Ürün ağaçları ürünün üretimi için gerekli malzeme ve alt bileşenlerin ERP üzerinde tanımlanmasını sağlar.

Kurallar:

- Kullanılan malzemeler doğru miktarda tanımlanır.
- Alt ürün ilişkileri korunur.
- Revizyon değişiklikleri kontrol edilir.

### 5.4 Rota ve Operasyon Standardı

Üretim akışının ERP üzerinde standart şekilde tanımlanması sağlanır.

Operasyon isimleri standart olarak kullanılır.

Rota içerisinde:

- Operasyon sırası
- İş merkezi
- Kontrol noktaları

tanımlanır.

### 5.5 Revizyon Yönetimi

ERP kayıtlarında ürün ve üretim bilgilerinin revizyon takibi sağlanır.

Kurallar:

- Eski revizyonlar silinmez.
- Yeni revizyonlar kontrollü şekilde oluşturulur.
- Revizyon değişiklik nedeni kayıt altına alınır.

## 6. Veri Oluşturma ve Kontrol Süreci

Yeni ana veri oluşturma süreci:

1- Talep 

2- Bilgi Kontrolü

3-ERP Kaydı Oluşturma

4-Kontrol

5-Onaylı Kullanım

## 7. Faz Çıktıları

Bu faz sonunda:

- Standart veri yapısı oluşturulmuş olacaktır.
- ERP kayıtlarının oluşturulma kuralları belirlenmiş olacaktır.
- Ürün, malzeme ve üretim bilgilerinin izlenebilirliği desteklenecektir.
- ERP kullanımında ortak veri dili oluşturulacaktır.


## Onaylar

| Rol | İsim | İmza | Tarih |
|---|---|---|---|
| Genel Müdür | Onur AYDÖRE | [FIELD: Signature or digital approval] | [FIELD: YYYY-MM-DD] |
| Proje Yöneticisi | Ezgi ÖZCAN | [FIELD: Signature or digital approval] | [FIELD: YYYY-MM-DD] |


## Değişiklik Geçmişi

| Versiyon | Tarih | Hazırlayan | Değişiklik Açıklaması |
|---|---|---|---|
| 0.0.0 | 24.09.2026 | Ezgi ÖZCAN | Veri Standardizasyonu Fazı  |

 \---