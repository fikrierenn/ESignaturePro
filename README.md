# E-Signature Pro - Kurumsal Web Sitesi

![E-Signature Pro](https://img.shields.io/badge/E--Signature%20Pro-Digital%20Transformation-purple)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

Modern, responsive ve profesyonel kurumsal web sitesi. E-imza ve dijital imza çözümleri sunan E-Signature Pro şirketi için tasarlanmıştır.

## 🚀 Özellikler

### 📱 Responsive Tasarım
- Mobil, tablet ve desktop uyumlu
- Modern ve temiz UI/UX
- Tailwind CSS ile optimize edilmiş

### 🎨 Kurumsal Kimlik
- Mor tema (Kurumsal renk kartelası)
- Profesyonel tipografi (Inter font)
- Tutarlı marka kimliği

### 📄 Sayfa Yapısı
- **Ana Sayfa** (`index.html`) - Hero section, özellikler, CTA
- **Ürünler** (`urunler.html`) - Mevcut ve gelecek ürünler
- **Hakkımızda** (`hakkimizda.html`) - Şirket hikayesi, misyon, vizyon
- **Çözümler** (`cozumler.html`) - Sektörel çözümler
- **SSS** (`sss.html`) - Açılır-kapanır FAQ sistemi
- **İletişim** (`iletisim.html`) - Form, harita, departmanlar

### ⚡ Teknik Özellikler
- SEO optimizasyonu
- Demo modal sistemi
- Form validasyonu
- Smooth transitions
- Mobile menu
- Accordion FAQ

## 🛠️ Teknolojiler

- **HTML5** - Semantic markup
- **CSS3** - Modern styling
- **JavaScript** - Interaktivite
- **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome** - İkon kütüphanesi
- **Google Fonts** - Inter tipografisi

## 📁 Proje Yapısı

```
esign/
├── index.html              # Ana sayfa
├── urunler.html            # Ürünler sayfası
├── hakkimizda.html         # Hakkımızda sayfası
├── cozumler.html           # Çözümler sayfası
├── sss.html               # SSS sayfası
├── iletisim.html          # İletişim sayfası
├── color-palette.css      # Kurumsal renk kartelası
├── brand-guidelines.md    # Marka kimliği rehberi
├── README.md              # Bu dosya
├── .gitignore             # Git ignore dosyası
└── LICENSE                # Lisans dosyası
```

## 🚀 Kurulum

1. **Repository'yi klonlayın:**
```bash
git clone https://github.com/fikrierenn/ESignaturePro.git
cd ESignaturePro
```

2. **Dosyaları görüntüleyin:**
```bash
# Ana sayfayı açın
open index.html
# veya
start index.html
```

3. **Local server başlatın (opsiyonel):**
```bash
# Python ile
python -m http.server 8000

# Node.js ile
npx serve .

# PHP ile
php -S localhost:8000
```

## 📱 Kullanım

### Sayfa Navigasyonu
- **Ana Sayfa**: Şirket tanıtımı ve ana özellikler
- **Ürünler**: Mevcut ve gelecek ürün portföyü
- **Hakkımızda**: Şirket hikayesi ve ekip bilgileri
- **Çözümler**: Sektörel çözümler (İK, Finans, IT, Hukuk)
- **SSS**: Sık sorulan sorular (accordion yapısında)
- **İletişim**: İletişim formu ve departman bilgileri

### Demo Modal
- Tüm sayfalarda "Demo Talep Et" butonu
- Form validasyonu ile güvenli veri toplama
- Responsive modal tasarımı

### Form Özellikleri
- İletişim formu (İletişim sayfası)
- Demo talep formu (Modal)
- Gizlilik politikası onayı
- Real-time validasyon

## 🎨 Tasarım Sistemi

### Renk Paleti
```css
/* Ana Mor Renkler */
--primary-purple: #7c3aed;
--primary-purple-dark: #6d28d9;
--primary-purple-light: #a78bfa;

/* Gradient Mor */
--gradient-purple-start: #8b5cf6;
--gradient-purple-end: #7c3aed;

/* Nötr Renkler */
--white: #ffffff;
--gray-50: #f9fafb;
--gray-800: #1f2937;
```

### Tipografi
- **Font**: Inter (Google Fonts)
- **Ağırlıklar**: 300, 400, 500, 600, 700
- **Responsive**: Mobilde optimize edilmiş

### Bileşenler
- **Header**: Sticky navigation
- **Hero Section**: Gradient background
- **Cards**: Hover efektleri
- **Buttons**: Purple theme
- **Forms**: Focus states
- **Modal**: Overlay design

## 📊 Sayfa İstatistikleri

| Sayfa | Satır Sayısı | Özellikler |
|-------|-------------|------------|
| `index.html` | ~400 | Hero, Features, CTA |
| `urunler.html` | ~500 | Product cards, Comparison table |
| `hakkimizda.html` | ~450 | Company story, Team, Values |
| `cozumler.html` | ~600 | Department solutions, Benefits |
| `sss.html` | ~550 | FAQ accordion, Categories |
| `iletisim.html` | ~500 | Contact form, Map, Departments |

## 🔧 Özelleştirme

### Renk Teması Değiştirme
`color-palette.css` dosyasındaki CSS değişkenlerini düzenleyin:

```css
:root {
    --primary-purple: #7c3aed; /* Ana rengi değiştirin */
    --gradient-purple-start: #8b5cf6; /* Gradient başlangıcı */
    --gradient-purple-end: #7c3aed; /* Gradient bitişi */
}
```

### İçerik Güncelleme
- HTML dosyalarındaki metinleri düzenleyin
- `brand-guidelines.md` dosyasını güncelleyin
- İkonları Font Awesome'dan değiştirin

### Yeni Sayfa Ekleme
1. Yeni HTML dosyası oluşturun
2. Header ve footer yapısını kopyalayın
3. Navigation menüsüne ekleyin
4. Responsive tasarımı test edin

## 🌐 Canlı Demo

Proje canlı olarak görüntülenebilir:
- GitHub Pages: [ESignaturePro](https://fikrierenn.github.io/ESignaturePro/)
- Local: `http://localhost:8000`

## 📈 Performans

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **PageSpeed Insights**: 90+ (Mobile & Desktop)
- **Core Web Vitals**: Optimize edilmiş
- **SEO**: Meta tags, structured data, semantic HTML

## 🔒 Güvenlik

- Form validasyonu (Client-side)
- XSS koruması
- CSRF token (Backend entegrasyonu için)
- HTTPS zorunluluğu (Production)

## 📝 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Branch'inizi push edin (`git push origin feature/AmazingFeature`)
5. Pull Request oluşturun

## 📞 İletişim

- **Website**: [E-Signature Pro](https://e-signature-pro.com)
- **Email**: info@e-signature-pro.com
- **Phone**: +90 224 123 45 67
- **Address**: Uludağ Üniversitesi Teknopark B Bok Kat:2 No:88 Nilüfer, Bursa, Türkiye

## 🙏 Teşekkürler

- [Tailwind CSS](https://tailwindcss.com) - CSS framework
- [Font Awesome](https://fontawesome.com) - İkon kütüphanesi
- [Google Fonts](https://fonts.google.com) - Tipografi
- [GitHub](https://github.com) - Version control

---

⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!
