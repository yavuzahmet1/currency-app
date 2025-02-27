# Döviz Çevirici Uygulaması

Bu proje, **React** ile geliştirilmiş basit bir **Döviz Çevirici Uygulaması**dır. Gerçek zamanlı döviz kuru verilerini bir API'den alır ve farklı para birimleri arasında dönüşüm yapılmasını sağlar.

## Özellikler

- [Free Currency API](https://freecurrencyapi.com/) kullanılarak canlı döviz kurları alınır.
- Belirli bir para birimindeki miktarı başka bir para birimine dönüştürme imkanı sunar.
- `From` ve `To` döviz seçimleri, API'den dinamik olarak yüklenir.
- Dönüştürülen miktar gerçek zamanlı olarak görüntülenir.
- Kullanıcı dostu ve responsive bir arayüz sunar.

# Döviz Çevirici Projesi

Bu proje, kullanıcıların farklı döviz birimleri arasında kolayca çevrim yapabilmelerini sağlayan bir web uygulamasıdır.

```plaintext
doviz-cevirici/
├── public/                  # Statik dosyalar (HTML, resimler, vs.)
├── src/                     # Uygulama kaynak kodları
│   ├── components/          # React bileşenleri
│   │   └── Currency.jsx     # Döviz çevirici ana bileşeni
│   ├── css/                 # Stil dosyaları
│   │   └── currency.css     # Uygulama için stiller
│   ├── App.js               # Ana bileşen
│   └── index.js             # Giriş noktası
├── package.json             # Proje bağımlılıkları ve scriptler
└── README.md                # Proje dokümantasyonu

## Kullanılan Teknolojiler

- **React**: Arayüz geliştirme.
- **Bootstrap**: Responsive tasarım.
- **Axios**: API taleplerini gerçekleştirme.
- **React Icons**: İkon kullanımı.

##Bağımlılıkları Yükleyin
- **pnpm install
- **pnpm start
