# Assets Klasörü

Bu klasör web sitesinin tüm görsel dosyalarını içerir.

## Klasör Yapısı

```
assets/
├── images/
│   ├── wrof-logo.png (veya .svg) - Ana logo dosyası
│   └── logo-placeholder.txt - Logo yükleme talimatları
└── README.md - Bu dosya
```

## Logo Yükleme

1. Logo dosyanızı `images/` klasörüne kopyalayın
2. Dosya adını `wrof-logo.png` veya `wrof-logo.svg` olarak değiştirin
3. Desteklenen formatlar: PNG, SVG, JPG, WEBP

### Önerilen Logo Boyutları:
- **PNG**: 200x200px (yüksek çözünürlük için 400x400px)
- **SVG**: Vektör format (en iyi kalite, her boyutta net)

## Otomatik Fallback

Logo yüklenmezse veya bulunamazsa, otomatik olarak Font Awesome kurt ikonu gösterilir.

## Diğer Görseller

İleride ek görseller için:
- `hero-bg.jpg` - Hero bölümü arka plan resmi
- `about-image.jpg` - Hakkımızda bölümü görseli
- `team-photos/` - Ekip fotoğrafları klasörü
