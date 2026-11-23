# 🛡️ Bilgi Güvenliği Farkındalık Kitapçığı

**Kurum çalışanları, yöneticiler, uzaktan çalışanlar ve yardımcı teknoloji kullananlar için kapsayıcı, erişilebilir ve uygulamaya dönük siber güvenlik rehberi.**

> **Yazar:** Cuma Kurt · [cuma.kurt@nscsoft.com](mailto:cuma.kurt@nscsoft.com)
> **Kurum:** NSCSOFT
> **Sürüm:** 3.0 (Kapsayıcı ve Güncel Baskı)
> **Çıktı:** [`Bilgi_Guvenligi_Farkindalik_Kitapcigi.pdf`](./Bilgi_Guvenligi_Farkindalik_Kitapcigi.pdf)

---

## 📋 İçindekiler

- [Proje Hakkında](#proje-hakkında)
- [Kitapçık Yapısı](#kitapçık-yapısı)
- [Teknik Gereksinimler](#teknik-gereksinimler)
- [PDF Üretme](#pdf-üretme)
- [İçerik Mimarisi](#i̇çerik-mimarisi)
- [Katkı ve Güncelleme](#katkı-ve-güncelleme)
- [Erişilebilirlik](#erişilebilirlik)
- [Lisans ve Kullanım Şartları](#lisans-ve-kullanım-şartları)

---

## Proje Hakkında

Bu kitapçık, bir kurumda teknik bilgi düzeyi ne olursa olsun **tüm çalışanların anlayabileceği** bir dille hazırlanmıştır. Siber saldırıların büyük çoğunluğu insan kaynaklı zafiyetlerle başlar; bu rehber o zafiyetleri kapatmak için gereken farkındalığı ve refleksleri kazandırmayı hedefler.

Her bölüm şu unsurları içerir:

| Bileşen | Amaç |
|---|---|
| Konu açıklaması | Konunun sade ve anlaşılır tanımı |
| Neden önemli? | Riskin kuruma ve çalışana etkisi |
| Gerçek saldırı senaryosu | Gerçek olaylardan esinlenen somut örnek |
| Yapılması / yapılmaması gerekenler | Net davranış kuralları |
| Adım adım kılavuz | Doğru davranışın sırayla uygulanışı |
| Kontrol listesi | İşaretlenebilir, uygulanabilir maddeler |
| Bölüm sonu sınavı | 5 soruluk değerlendirme ve cevap anahtarı |

---

## Kitapçık Yapısı

Kitapçık, 34 ana bölüm ve ek bölümlerden oluşur. Bölümler yedi tematik grupta düzenlenmiştir:

### Grup 1 — Temel Kavramlar (Bölüm 1–5)
Bilgi güvenliğinin temel ilkeleri (CIA üçlüsü), tehdit, zafiyet ve risk kavramları, güvenlik kültürü.

### Grup 2 — Kimlik ve Erişim Güvenliği (Bölüm 6–10)
Parola yönetimi, çok faktörlü kimlik doğrulama (MFA), passkey teknolojisi, ayrıcalıklı erişim, kimlik doğrulama saldırıları.

### Grup 3 — Sosyal Mühendislik ve Kimlik Avı (Bölüm 11–15)
Phishing, spear phishing, smishing, vishing, quishing (QR), BEC dolandırıcılığı, deepfake tabanlı saldırılar.

### Grup 4 — Zararlı Yazılımlar ve Cihaz Güvenliği (Bölüm 16–20)
Fidye yazılımı, infostealer, USB/çıkarılabilir medya güvenliği, cihaz şifreleme, güvenli ekran kilidi.

### Grup 5 — Veri ve İletişim Güvenliği (Bölüm 21–25)
Veri sınıflandırma, güvenli dosya paylaşımı, e-posta güvenliği, yapay zeka araçlarında veri gizliliği, kaynak kodu ve fikri mülkiyet koruması.

### Grup 6 — Uzaktan Çalışma ve Fiziksel Güvenlik (Bölüm 26–30)
Ev ve uzaktan çalışma güvenliği, VPN, halka açık Wi-Fi riskleri, iş seyahati güvenliği, fiziksel erişim ve temiz masa politikası, gizlice gözetleme (shoulder surfing).

### Grup 7 — Olay Yönetimi ve İleri Konular (Bölüm 31–34)
Güvenlik olayı bildirme ve müdahale, tedarik zinciri riskleri, bulut güvenliği.

### Ek Bölümler
- **Erişilebilirlik** (Bölüm 31): PDF/UA uyumluluğu, ekran okuyucu desteği, yardımcı teknoloji kullananlar için uyarlamalar.
- **Yapay Zeka Ajanları** (Bölüm 32): Kurum verilerini yapay zeka araçlarında güvenli kullanma.
- **Kuantum Sonrası Kriptografi** (Bölüm 33): Post-quantum şifreleme standartlarına hazırlık.
- **Dijital Dayanıklılık** (Bölüm 34): Uzun vadeli siber dayanıklılık alışkanlıkları.
- **Senaryo Kataloğu** (Bölüm 35): Farklı rollere özel gerçekçi saldırı senaryoları.
- **Güncel Tehdit Panoraması**: 2025–2026 itibarıyla öne çıkan tehdit aktörleri ve saldırı teknikleri.
- **Farkındalık Programı Rehberi**: Kurum içi eğitim programı tasarlama kılavuzu.
- **Karar Ağacı**: Şüpheli durumda ne yapılacağını gösteren adım adım karar akışı.
- **Ekler**: Siber güvenlik sözlüğü, referans kaynaklar, rol bazlı başlangıç yolları.



### Proje Yapısı

└── Bilgi_Guvenligi_Farkindalik_Kitapcigi.pdf
```

## İçerik Mimarisi

### Markdown Kuralları

Her bölüm dosyası standart bir şablona uymaktadır. Özel div sınıfları kullanılarak yapısal bloklar tanımlanır:

```markdown
::: info
Bilgi kutusu içeriği
:::

::: warning
Dikkat / uyarı içeriği
:::

::: checklist
- Madde 1
- Madde 2
:::

::: summary
Bölüm özeti
:::

::: a11y
Erişilebilirlik notu
:::
```

---

## Katkı ve Güncelleme

Bu kitapçık **yaşayan bir belgedir**. Yeni tehdit türü, mevzuat değişikliği veya kurum içi olay yaşandığında ilgili bölüm güncellenir ve sürüm numarası artırılır.

### Hata veya Öneri Bildirme

Okurken not aldığınız her noktayı (bölüm, cümle, gerekçe) bilgi güvenliği ekibine iletin. Bunlar sonraki baskının en değerli girdisidir:

- **E-posta:** [cuma.kurt@nscsoft.com](mailto:cuma.kurt@nscsoft.com)

### Güncelleme Politikası

- Kritik tehdit değişikliklerinde → anında
- Mevzuat güncellemelerinde → 30 gün içinde
- Yıllık kapsamlı gözden geçirme → Her yıl

---

## Erişilebilirlik

Üretilen PDF, **PDF/UA** standardına uygun olarak etiketlidir:

- Ekran okuyucular başlık hiyerarşisini, listeleri ve tabloları tanır.
- Tüm görsellerin alternatif metni (alt text) bulunur.
- Bağlantılar altı çizili ve yüksek kontrastlıdır.
- Anlam hiçbir zaman yalnızca renge bağlı kurulmaz; her uyarı kutusu metin etiketiyle adlandırılır.
- Metin yeniden akış (reflow) desteklenir; iki sütunlu düzen kullanılmaz.

Erişilebilirlikle ilgili ek gereksinimler için **Bölüm 31**'e ve bilgi güvenliği ekibine başvurun.

---

## Lisans ve Kullanım Şartları

Bu kitapçık **kurum içi eğitim amacıyla** hazırlanmıştır.

- Buradaki öneriler genel iyi uygulamalardır; kurumunuzun kendi bilgi güvenliği politikaları önceliklidir.
- Bu belge hukuki danışmanlık, kurumsal politikanın yerine geçen bir belge veya teknik yapılandırma rehberi değildir.
- Çelişki durumunda kurum politikası ve bilgi güvenliği ekibinin yönlendirmesi geçerlidir.

---

<div align="center">

**NSCSOFT** · Bilgi Güvenliği Ekibi
Sürüm 3.0 · Kasım 2026

</div>
