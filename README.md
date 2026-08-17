# Evaporatif — Endüstriyel Evaporatif Soğutma Sistemleri

> **CE Belgeli · Türkiye Üretimi · Arge Teknoloji San. Ve Tic. A.Ş.**

Fabrika, atölye, depo ve endüstriyel tesisler için kompresörsüz, **%80'e varan enerji tasarruflu** evaporatif soğutma çözümleri sunan kurumsal web sitesi.

---

## 🚀 Canlı Demo

Bu site tamamen statik HTML/CSS/JS'ten oluşmaktadır ve **GitHub Pages** üzerinde doğrudan yayınlanabilir.


https://thetokur.github.io/evaporatif-demo-site/


---

## 📁 Proje Yapısı

```
DEMO 2/
│
├── index.html              # Ana site dosyası (tüm sayfa burada)
├── catalog.pdf             # E-Katalog (ürün teknik dokümanı)
├── LOGO.png                # Marka logosu
│
├── Banner/                 # Ana sayfa tam ekran banner görselleri
│   ├── 1.png               # Slayt 1 arka planı
│   ├── 2.png               # Slayt 2 arka planı
│   └── 3.png               # Slayt 3 arka planı
│
├── Görseller/              # Ürün ve referans fotoğrafları
│   ├── 1.jpeg              → EVA 20 / Teknoloji bölümü (sol büyük)
│   ├── 2.jpeg              → EVA 40
│   ├── 3.jpeg              → EVA 60
│   ├── 4.jpeg              → EVA 80 / Galeri büyük görsel
│   ├── 5.jpeg              → Teknoloji bölümü (sağ alt)
│   ├── 6.jpeg              → Teknoloji bölümü (sağ üst)
│   ├── 7.jpeg              → EVA 30
│   ├── 8.jpeg              → Galeri
│   ├── 9.jpeg              → Galeri
│   ├── 10.jpeg             → Galeri
│   ├── 11.jpeg             → EVA 20
│   └── 12.png              → Galeri (yapay zeka görseli)
│
└── logos/                  # Referans marka logoları (SVG)
    ├── arcelik.svg
    ├── bosch.svg
    ├── bsh.svg
    ├── vestel.svg
    ├── pinar.svg
    ├── sutas.svg
    ├── temsa.svg
    ├── eca.svg
    ├── orkide.svg
    ├── forum.svg
    ├── macaron.svg
    └── megametal.svg
```

---

## ✨ Özellikler

| Bölüm | Açıklama |
|---|---|
| **Banner Slider** | 3 slaytlı tam ekran banner; otomatik 5s geçiş, yumuşak animasyon, progress bar, ok & dot navigasyonu, swipe desteği |
| **3 Kolonlu Banner** | Her slayt: Ana İçerik + Bilgi Kartı + CTA Kartı olarak 3 bölüme ayrılır |
| **Ürün Sayfası** | EVA 20 / 30 / 40 / 60 / 80 modellerinin teknik özellikleri |
| **ROI Hesaplayıcı** | Fabrika alanı ve çalışma saatine göre aylık/yıllık tasarruf hesabı |
| **Referans Galerisi** | Saha kurulum fotoğrafları |
| **Referans Markalar** | Arçelik, Bosch, BSH, Vestel, Sütaş, Pınar, Temsa vb. logo grid |
| **SSS** | 7 adet sıkça sorulan soru |
| **İletişim Formu** | WhatsApp üzerinden teklif talebi |
| **Scroll Animasyonları** | IntersectionObserver tabanlı reveal animasyonları |
| **Tam Responsive** | Masaüstü, tablet ve mobil uyumlu |

---

## 🌐 GitHub Pages'te Yayınlama

### Adım 1 — Repository Oluşturun

```bash
git init
git add .
git commit -m "İlk yayın"
git branch -M main
git remote add origin https://github.com/<kullanici-adi>/<repo-adi>.git
git push -u origin main
```

### Adım 2 — GitHub Pages'i Etkinleştirin

1. GitHub'da repository sayfanıza gidin
2. **Settings** → **Pages** menüsüne tıklayın
3. **Source** bölümünde **Deploy from a branch** seçin
4. Branch olarak **`main`** ve klasör olarak **`/ (root)`** seçin
5. **Save** butonuna tıklayın

Birkaç dakika içinde siteniz şu adreste yayına girer:

```
https://<kullanici-adi>.github.io/<repo-adi>/
```

---

## ⚠️ Önemli Notlar

- Tüm görsel yolları **URL-encoded** olarak yazılmıştır (Türkçe `ö` karakteri `%C3%B6` olarak encode edilmiştir). Bu sayede GitHub Pages'te sorunsuz çalışır.
- `Banner/` ve `Görseller/` klasörleri **büyük/küçük harf duyarlıdır** — GitHub'a push ederken klasör adlarının birebir aynı olmasına dikkat edin.
- `catalog.pdf` dosyası büyük boyutlu olduğu için Git LFS (Large File Storage) kullanmanız önerilir.

### Git LFS Kurulumu (Opsiyonel)

```bash
git lfs install
git lfs track "*.pdf"
git lfs track "*.png"
git add .gitattributes
git commit -m "Git LFS eklendi"
```

---

## 🛠️ Teknolojiler

- **HTML5** — Semantik yapı
- **CSS3** — Vanilla CSS, CSS Custom Properties, Grid, Flexbox, Glassmorphism
- **JavaScript (ES6+)** — Vanilla JS, IntersectionObserver, requestAnimationFrame
- **Google Fonts** — Nunito Sans
- **Tasarım** — Dark overlay gradient, micro-animasyon, responsive layout

---

## 📞 İletişim

| Kanal | Bilgi |
|---|---|
| Sabit Hat | 0258 215 50 19 |
| WhatsApp | 0532 493 15 06 |
| Instagram | [@evaporatif](https://www.instagram.com/evaporatif) |
| E-posta | info@evaporatif.com.tr |
| Ofisler | Denizli · İstanbul (Beykoz) |

---

© 2026 Evaporatif Soğutma Ve Isıtma Sistemleri Arge Teknoloji San. Ve Tic. A.Ş.
