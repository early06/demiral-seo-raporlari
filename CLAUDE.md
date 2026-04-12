# Demiral Isı Mühendisliği — Görev Tanımları

## Proje
- Site: https://demiralisimuhendisligi.com.tr
- API: https://demiralisimuhendisligi.com.tr/api.php
- Konum: Ankara Etimesgut | Baymak Yetkili Bayii

---

## ⚠️ Mevcut Durum (Güncel Tut)

Aşağıdakiler ZATEN YAPILDI. Raporlarda "yapılmalı" diye tekrar önerme:

- ✅ Google Search Console kurulu (28 Mart 2026'dan beri)
- ✅ Google Analytics 4 kurulu (G-9PT9C58VRF)
- ✅ Google Ads kurulu (AW-18052236146)
- ✅ Schema.org markup tüm sayfalarda (LocalBusiness, Service, FAQPage)
- ✅ Blog bölümü aktif (blog.html, DB üzerinden çalışıyor)
- ✅ İlçe bazlı hizmet sayfaları mevcut:
  - etimesgut-kombi-servisi.html (SSS, bakım takvimi, fiyat tablosu, mahalle listesi)
  - etimesgut-baymak-servisi.html (arıza kodları tablosu, model rehberi, garanti bilgileri)
  - ankara-baymak-bayii.html (ürün karşılaştırma tablosu, taksit, hizmet bölgeleri, kombi seçim rehberi)
  - urunler.html (ürün kataloğu + statik SEO içeriği)
- ✅ Sitemap.xml güncel ve GSC'ye gönderildi
- ✅ robots.txt düzgün yapılandırılmış
- ✅ Meta Ads kampanyası aktif (Instagram Direct mesaj hedefli)
- ✅ Instagram profili: @demiralisimuhendisligi
- ✅ Dizine eklenen sayfa sayısı: 6

## ⚠️ Cloudflare 403 Uyarısı

Site Cloudflare arkasında çalışıyor. WebFetch ile erişim denediğinde 403 Forbidden alabilirsin. Bu NORMAL — Cloudflare bot koruması seni engelliyor.

**ÖNEMLİ:** Bu 403 hatası Googlebot'u ETKİLEMİYOR. Google Search Console'da tüm sayfalar başarıyla taranıyor ve dizine ekleniyor. Raporlarda bunu "ACİL" veya "KRİTİK" olarak işaretleme. Sadece "Cloudflare bot koruması nedeniyle WebFetch 403 alıyor, Googlebot erişiminde sorun yok" şeklinde not düş.

---

## 📊 Günlük SEO Analizi Görevi

Her çalıştırıldığında şunları yap:

### 1. Site Erişim Kontrolü
WebFetch ile https://www.demiralisimuhendisligi.com.tr adresine eriş.
- 200 alırsan: normal, içeriği raporla
- 403 alırsan: "Cloudflare bot koruması — Googlebot erişiminde sorun yok" yaz, panik yapma
- 5xx alırsan: ASIL SORUN, bunu kritik olarak raporla

### 2. Google Sıralama Kontrolü
WebSearch ile şu kelimeleri ara, siteni bul, kaçıncı sırada olduğunu yaz:
- "baymak bayii ankara"
- "etimesgut kombi servisi"
- "ankara kombi bakımı"
- "baymak kombi fiyatları"
- "kombi servisi ankara"
- "etimesgut baymak servisi"

Önceki raporlardaki sıralamalarla karşılaştır, iyileşme veya kötüleşme varsa belirt.

### 3. Rakip Analizi
Üstteki aramalarda öne çıkan rakipleri listele. Armut.com'u dahil etme.

### 4. Blog İçerik Önerileri
Sektörde trend olan 3-10 arası konu öner. Daha önce önerilen ve henüz yazılmamış konuları tekrar öner.

### 5. En Önde Olabilmemiz İçin Yapılacak Şeyler Öner
Rakip firmalardan daha öne çıkmamız için yapılabilecek şeyleri öner. Zaten yapılmış şeyleri tekrar önerme (yukarıdaki "Mevcut Durum" bölümünü kontrol et).

### 6. Raporu Kaydet
- Klasör: seo-raporlari/
- Dosya adı: seo-raporlari/YYYY-MM-DD.md
- Format: Türkçe Markdown

### 7. Git Push
git add .
git commit -m "SEO Raporu: [tarih]"
git push origin main
