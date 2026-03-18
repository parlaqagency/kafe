# KONTRBUS COFFEE — Web Sitesi

## Kurulum

Herhangi bir sunucuya (shared hosting, VPS, Netlify, vb.) yükleyin:

```
kontrbus/
├── index.html          ← Ana sayfa
├── menu.html           ← Menü PDF önizleme (tarayıcıdan yazdırın)
├── assets/
│   ├── logo.png
│   ├── hakkımizda.jpeg
│   ├── arkplan.jpeg
│   ├── kontrbus video.mov
│   ├── kahve frame/    ← 121 adet frame (blend animasyonu)
│   ├── konsept/        ← 8 adet konsept galerisi görseli
│   └── images/
│       ├── hero/
│       ├── sicak-icecekler/
│       ├── soguk-icecekler/
│       ├── tatlilar/
│       └── bouncecard/
```

## Menü PDF

`menu.html` dosyasını tarayıcıda açın → Yazdır (Ctrl+P) → Hedef: "PDF olarak kaydet" → A4, kenar boşluğu yok.

## Video Formatı

`kontrbus video.mov` dosyasını `.mp4` formatına dönüştürmeniz önerilir (geniş tarayıcı desteği için).

```
ffmpeg -i "kontrbus video.mov" -vcodec h264 -acodec aac "assets/kontrbus video.mp4"
```

Sonra `index.html` içinde `kontrbus video.mov` → `kontrbus video.mp4` olarak güncelleyin.

## Notlar

- Fiyatlar `menu.html` içinde `— ₺` kısımları güncellenerek doldurulur.
- İletişim formu için [Formspree.io](https://formspree.io) veya [EmailJS](https://emailjs.com) entegrasyonu önerilir.
- `@kontrbuscoffee` Instagram linki zaten aktif.

---
© 2024 KONTRBUS COFFEE
