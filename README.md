# Kumaş Ölç PRO — Vercel

## Vercel'e yükleme
1. Vercel hesabına giriş yapın.
2. **Add New → Project** seçin.
3. Bu klasörü GitHub üzerinden içe aktarın veya Vercel CLI ile deploy edin.
4. Framework seçimi gerekmez; bu statik HTML projesidir.
5. Build command boş bırakılabilir.
6. Output directory olarak `.` kullanılabilir.

## Uygulama
- Fotoğraf yükleme
- iPhone kamera seçimi
- A4 (21 cm) veya 1 TL (2,7 cm) kalibrasyonu
- Kumaşın 4 köşesini seçme
- Genişlik, uzunluk ve yaklaşık alan hesaplama

Kamera sayfa açılışında otomatik açılmaz.
Fotoğrafı sunucuya gönderen `fetch`/XHR kodu bulunmaz; işlem tarayıcı içinde yapılır.
