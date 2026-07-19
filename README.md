# Selase Hilal Çay — Landing Page

Stitch ile tasarlanan tek sayfalık ürün/marka tanıtım sitesi. Statik bir
HTML sayfası; build adımı gerekmez, doğrudan GitHub Pages ile
yayınlanabilir.

## Bu sürümde nelere dokunulmadı

Kullanıcının isteği üzerine sipariş linklerine dokunulmadı:
- Hero ve nav'daki "Satın Al / Sipariş" butonları bilinçli olarak
  `gardrops.com` sayfasına gidiyor.
- Footer'daki "İletişim" ve WhatsApp CTA'ları `https://wa.me/905318581834`
  adresine gidiyor.

## Düzeltilen ölü linkler

Footer'daki üç yasal sayfa linki (`Kullanım Koşulları`, `Gizlilik
Politikası`, `Mesafeli Satış Sözleşmesi`) hiçbir yere gitmiyordu (`href="#"`).
Şimdi gerçek dosyalara bağlandılar: `kullanim-kosullari.html`,
`gizlilik-politikasi.html`, `mesafeli-satis-sozlesmesi.html`. Bu dosyalar
**taslak şablon** — gerçek hukuki içerik değil. Yayına almadan önce kendi
metninizle (tercihen bir avukatın gözden geçirmesiyle) doldurun.

Footer'daki iki sosyal medya ikonu (kamera / paylaş) hâlâ `href="#"` —
gerçek Instagram/sosyal medya hesap linkiniz varsa bana iletin, bağlarım.
Uydurma bir hesap linki eklemedim.

## Yapmadan önce: eksik görseller

`index.html` içinde dört görsel, Stitch'in geçici önizleme adresi yerine
yerel dosya yoluna bağlandı:

- `assets/images/hero-product.jpg` — hero bölümü ana ürün görseli
- `assets/images/composition-bg.jpg` — hero'daki dekoratif arka plan görseli
- `assets/images/story-product.jpg` — "Bu Bizim Hikâyemiz" bölümü görseli
- `assets/images/detail-product.jpg` — ürün detay bölümü görseli

Bu dosyalar şu anda **repoda yok**. Yayınlamadan önce:

1. Stitch canvas'ındaki görsellere sağ tıklayıp "Resmi kaydet" ile indirin
   (ya da bu sohbette hazırladığımız stüdyo fotoğrafı promptunu bir görsel
   AI aracında çalıştırıp çıktıyı indirin).
2. Dört dosyayı `assets/images/` klasörüne, yukarıdaki isimlerle koyun.

Görselleri eklemezseniz o alanlar kırık resim ikonu olarak görünür.

## Yerel önizleme

```bash
python3 -m http.server 8000
# tarayıcıda http://localhost:8000 adresini açın
```

## GitHub'a yükleme

```bash
git init
git add .
git commit -m "İlk sürüm: Selase Hilal Çay landing page"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADIN/REPO_ADIN.git
git push -u origin main
```

## GitHub Pages ile yayınlama

1. GitHub'da depo sayfasında **Settings → Pages** bölümüne gidin.
2. **Source** olarak `Deploy from a branch` seçin (Actions/Jekyll değil).
3. **Branch**: `main`, klasör: `/ (root)` seçip kaydedin.
4. Birkaç dakika içinde siteniz şu adreste yayında olur:
   `https://KULLANICI_ADIN.github.io/REPO_ADIN/`

## Yapı

```
.
├── index.html
├── kullanim-kosullari.html       # taslak, doldurulmalı
├── gizlilik-politikasi.html      # taslak, doldurulmalı
├── mesafeli-satis-sozlesmesi.html # taslak, doldurulmalı
├── assets/
│   └── images/
│       ├── favicon.svg
│       ├── hero-product.jpg       # eklenmeli
│       ├── composition-bg.jpg     # eklenmeli
│       ├── story-product.jpg      # eklenmeli
│       └── detail-product.jpg     # eklenmeli
├── DESIGN.md
└── README.md
```
