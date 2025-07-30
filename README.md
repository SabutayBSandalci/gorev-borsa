# Finans Uygulaması - 3 Sayfalık Responsive Web Arayüzü

Bu proje, referans görsellere birebir uygun olarak geliştirilmiş 3 sayfalık finans uygulaması kullanıcı arayüzünü içerir.

## Sayfalar

### 1. Login Sayfası (`login.html`)
- **3 Slaytlı Kart Yapısı**: "Risk Ready", "Tradeoffs", "Risk Averse"
- **CSS Grid Layout**: Yatay hizalanmış kartlar
- **Animasyonlu Geçişler**: CSS ile slayt geçişleri
- **Top Bar**: Sinyal göstergeleri ve Skip butonu
- **Bottom Buttons**: Log In ve Sign Up butonları
- **Navigation Dots**: Slayt geçiş noktaları

### 2. Exchange Rate Sayfası (`kur.html`)
- **Koyu Tema**: Siyah arka plan
- **Büyük Dolar Değeri**: $1324.26
- **Döviz Türleri**: USD, EUR, BTC, ETH grid yapısında
- **Responsive Grid**: Üstte değer, altta para birimleri

### 3. Dashboard Sayfası (`dashboard.html`)
- **2x2 Grid Butonları**: Add Money, Exchange, Details, More
- **Font Awesome İkonları**: Sarı renkli ikonlar
- **İşlem Geçmişi**: NVIDIA ve Tesla işlemleri
- **Koyu Tema**: Siyah arka plan, gri kartlar

## Teknolojiler

- **HTML5**: Semantik yapı
- **CSS3**: Modern stillendirme
- **CSS Grid**: Layout sistemi (tüm sayfalarda)
- **Font Awesome**: İkonlar
- **Google Fonts**: Nunito Sans font ailesi

## Grid Layout Yapısı

### Login Sayfası
```css
.login-container {
    display: grid;
    grid-template-rows: auto 1fr auto auto;
}
```

### Exchange Rate Sayfası
```css
.kur-container {
    display: grid;
    grid-template-rows: auto auto auto auto;
}
```

### Dashboard Sayfası
```css
.dashboard-container {
    display: grid;
    grid-template-rows: auto auto auto auto;
}
```

## Özellikler

- ✅ CSS Grid layout kullanımı (zorunlu)
- ✅ Responsive tasarım
- ✅ Koyu tema (Exchange Rate ve Dashboard)
- ✅ Modern UI/UX tasarım
- ✅ Font Awesome ikonları
- ✅ Sayfalar arası navigasyon
- ✅ Hover efektleri
- ✅ Slayt animasyonları (CSS)
- ✅ Birebir görsel uyumluluk

## Kullanım

1. Dosyaları indirin
2. `login.html` dosyasını tarayıcıda açın
3. Sayfalar arasında geçiş yapmak için navigation linklerini kullanın

## Dosya Yapısı

```
├── login.html          # 3 slaytlı giriş sayfası
├── kur.html           # Exchange Rate ekranı
├── dashboard.html     # Dashboard ekranı
├── styles.css         # Ortak CSS dosyası
└── README.md          # Bu dosya
```

## Sayfa Geçişleri

- **Login** → Log In butonu → Dashboard
- **Login** → Skip butonu → Exchange Rate
- **Exchange Rate** → Dashboard linki → Dashboard
- **Dashboard** → Exchange Rate linki → Exchange Rate

## Responsive Tasarım

Tüm sayfalar mobil cihazlarda da düzgün görünecek şekilde tasarlanmıştır:
- Mobil cihazlarda grid layout optimize edilir
- Font boyutları küçük ekranlara uyarlanır
- Spacing ve padding değerleri ayarlanır

## Notlar

- JavaScript kullanılmamıştır (sadece HTML ve CSS)
- Tüm layout'lar CSS Grid ile oluşturulmuştur
- Font Awesome CDN kullanılmıştır
- Google Fonts CDN kullanılmıştır
- Slayt geçişleri CSS animation ile yapılmıştır 