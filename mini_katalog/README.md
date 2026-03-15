# Mini Catalog Uygulaması

Software Persona Mobil Projesidir, uygulamada ürünleri arayabilir, inceleyebilir ve sepete ekleyip alanabilir.

## Ekran Görüntüleri

> Add your screenshots here after running the app.


## Flutter Versiyonu

**Flutter 3.41.4** / **Dart 3.11.1**


### Run the App

1. **Repoyu Kopyala**
   ```
   git clone https://github.com/LordWafflous/sp-mobile-project.git
   cd mini_catalog
   ```

2. **Dependency ekle**
   ```
   flutter pub get
   ```

3. **Emulatorde çalıştır**
   ```
   flutter run
   ```

## Proje Yapısı

```
lib/
├── main.dart                   # App giriş noktası ve rotalar
├── models/
│   └── product.dart            # Ürün veri modeli
├── data/
│   └── products_data.dart      # Örnek ürünlerin listesi
└── screens/
    ├── home_screen.dart         # Ana sayfa
    ├── product_list_screen.dart # GridView katalog ve arama
    ├── product_detail_screen.dart # Ürün detayları
    └── cart_screen.dart         # Sepet
```

## Özellikler

- Ana ekrandan katoloğa giriş
- Eşya arama ve filtreleme
- GridView kartları
- Ürün sayfa ve detayları 
- Ürünü sepete ekleme

## Öğrenilenler

- Stateless ve Stateful widgetlar
- Routelarla navigator 
- Route argümanlarının ekranlar arası kullanımı
- ListView ve GridView buildleri
- Durum yönetimiyle sepet oluşturma