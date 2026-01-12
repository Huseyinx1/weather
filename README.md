# Hava Durumu Uygulaması

API anahtarı gerektirmeden çalışan, modern ve responsive hava durumu uygulaması. Open-Meteo servislerini kullanır.

## Özellikler
- API anahtarı gerektirmez (Open-Meteo)
- Şehir adına göre arama ve otomatik koordinat bulma
- Anlık sıcaklık, hissedilen sıcaklık, nem, rüzgar hızı, görüş mesafesi
- Emoji tabanlı hava durumu ikonları
- Tailwind CSS ile modern, cam efekti (glassmorphism) ve animasyonlu arayüz
- Mobil uyumlu (responsive)

## Kurulum ve Çalıştırma
1. Depoyu indirin veya klasöre gidin:
   ```bash
   cd havadurumu
   ```
2. `index.html` dosyasını bir tarayıcıda açın.
3. Şehir adını girip Enter'a basın veya arama butonuna tıklayın.

## Teknolojiler
- HTML, CSS, JavaScript (tek sayfa)
- Tailwind CSS CDN
- Open-Meteo Geocoding API (şehirden koordinat bulma)
- Open-Meteo Forecast API (hava durumu verisi)

## Yapı
- `index.html`: Tüm HTML, CSS ve JS tek dosyada.

## Notlar
- İnternet bağlantısı gerekir (CDN ve API çağrıları için).
- İsterseniz stil ve animasyonları `style` bloğu içinde düzenleyebilirsiniz.

## Örnek Kullanım
- İstanbul, Ankara, Izmir, London gibi şehir adlarını girin; sonuçlar anında görüntülenir.
