# Demiral Isı Mühendisliği — Görev Tanımları

## Proje
- Site: https://demiralisimuhendisligi.com.tr
- API: https://demiralisimuhendisligi.com.tr/api.php
- Konum: Ankara Etimesgut | Baymak Yetkili Bayii

---

## 📊 Günlük SEO Analizi Görevi

Her çalıştırıldığında şunları yap:

### 1. Site Erişim Kontrolü
WebFetch ile https://www.demiralisimuhendisligi.com.tr adresine eriş.
HTTP durumunu ve içeriği raporla.

### 2. Google Sıralama Kontrolü
WebSearch ile şu kelimeleri ara, siteni bul, kaçıncı sırada olduğunu yaz:
- "baymak bayii ankara"
- "etimesgut kombi servisi"
- "ankara kombi bakımı"
- "baymak kombi fiyatları"
- "kombi servisi ankara"
- "etimesgut baymak servisi"

### 3. Rakip Analizi
Üstteki aramalarda öne çıkan rakipleri listele.

### 4. Blog İçerik Önerileri
Sektörde trend olan 3-5 konu öner.

### 5. Raporu Kaydet
- Klasör: seo-raporlari/
- Dosya adı: seo-raporlari/YYYY-MM-DD.md
- Format: Türkçe Markdown

### 6. Git Push
git add seo-raporlari/
git commit -m "SEO Raporu: [tarih]"
git push origin main
