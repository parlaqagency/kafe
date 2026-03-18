# KONTRBUS COFFEE — Site Geliştirme Listesi

## Mevcut Güçlü Yönler
- GSAP + Lenis + SplitType altyapısı kurulu
- Custom cursor, preloader, particle hero hazır
- Scroll-driven frame animasyon çalışıyor
- Interactive menu + lightbox mevcut

---

## Yapılacaklar (Öncelik Sırasına Göre)

### 1. 🧲 Magnetic Buttons
**Etki:** Çok yüksek | **Süre:** ~30 dk
- "Keşfet" ve franchise CTA butonlarına cursor yaklaştıkça "çekilen" efekt
- GSAP `quickTo` ile smooth hareket
- 15-20 satır JS

---

### 2. 🎞️ Horizontal Scroll Showcase
**Etki:** Çok yüksek | **Süre:** ~1.5 saat
- Kahve çeşitleri veya brand story milestone'larını yatay kaydırma ile anlat
- GSAP ScrollTrigger pinned horizontal scroll
- Rakipte yok = direk fark yaratır

---

### 3. 🌾 Noise / Grain Texture Overlay
**Etki:** Orta-Yüksek | **Süre:** ~15 dk
- Sayfanın tamamına ince film grain dokusu
- CSS `::after` + SVG filter ile
- "Premium baskı malzeme" hissi katar
- 5-10 satır CSS

---

### 4. 📢 Marquee Text Band
**Etki:** Orta | **Süre:** ~30 dk
- `SPECIALTY COFFEE · COLD BREW · 1971 · KONTRBUS ·` — sonsuz kayan bant
- Hero ile About arasına veya Stats Bar yerine
- Hem boşluk doldurucu hem karakter katıcı
- CSS animation veya GSAP

---

### 5. 🃏 Menu Card 3D Tilt
**Etki:** Yüksek | **Süre:** ~45 dk
- Mevcut kartlarda sadece `translateY(-8px)` var
- `mousemove` bazlı perspektif tilt ekle
- GSAP ile ~20 satır
- Premium e-ticaret hissi verir

---

### 6. 💬 Testimonials Section
**Etki:** Yüksek (dönüşüm açısından) | **Süre:** ~1 saat
- Şu an sosyal kanıt **sıfır**
- 3 müşteri alıntısı — minimal kart tasarımı
- Bebas Neue + altın accent
- Franchise bölümünün hemen öncesine

---

### 7. 📍 Konum Section
**Etki:** Orta | **Süre:** ~45 dk
- Gerçek harita değil — stilize şehir/semt gösterimi
- Büyük tipografi + minimal tasarım
- "İzmir'in kalbinde" gibi bir yaklaşım

---

### 8. 🔢 Animasyonlu Sayaç (Stats Bar)
**Etki:** Orta | **Süre:** ~20 dk
- Stats Bar mevcut, ama sayılar statik mi kontrol et
- GSAP ile sıfırdan hedefe çıkan sayaç animasyonu
- ScrollTrigger viewport'a girince tetiklenir

---

## Notlar
- Grain overlay → magnetic buttons → marquee → 3D tilt sırası en az çabayla en yüksek etki
- Testimonials + konum bölümleri içerik gerektiriyor, önce metinleri hazırla
- Horizontal scroll büyük iş ama en "wow" faktörü o
