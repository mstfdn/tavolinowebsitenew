# Tavolino Cafe & Restaurant

23 Nisan, Mithatpaşa Cd. 17-A, 16130 Nilüfer / Bursa
Her gün 08:00 - 01:00 · (0224) 999 50 56

Kaydırmayla oynayan hero videolu tek sayfalık site.
Düz HTML, CSS ve vanilla JavaScript. Derleme adımı yok, bağımlılık yok.

## Dosyalar

- `index.html` — sayfanın tamamı: yapı, stil ve script
- `assets/hero-scrub.mp4` — kaydırmayla oynayan hero videosu
- `assets/hero-poster.jpg` — video yüklenene kadar görünen ilk kare
- `assets/hero-ending.jpg` — son kare, telefon görünümünün arka planı
- `assets/story.jpg` — hakkımızda bölümünün görseli

## Yerelde çalıştırmak

    npx http-server . -p 8127 -c-1

Sonra tarayıcıda http://localhost:8127 adresini açın.
Dosyaya çift tıklamak da çalışır.

## Notlar

- Telefonlarda video yerine tasarlanmış sabit görsel gösterilir, video hiç indirilmez.
- Adresin sonuna `#tani` eklerseniz videonun teknik durumunu gösteren bir kutu açılır.
