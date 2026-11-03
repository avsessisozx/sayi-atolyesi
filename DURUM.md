# DURUM (Sayı Atölyesi)

## Sürüm 0.1.0 — 2026-11-03
Yapıldı:
- Toplama: onluk/birlik blokları, eldeli toplama, sesli anlatım
- Çarpma: sütun×satır ızgara, satır satır sayma, 5'e bölme
- İzle ve Sen yap modu, yanlışta ceza yok
- Hata raporu ekranı (kopyalanabilir), geri tuşu
- GitHub Actions ile APK derleme + release

Doğrulandı:
- Tarayıcıda (Playwright) tüm adımlar, hata yok
- CI derlemesi başarılı, APK içinde dex+assets+manifest var

Doğrulanmadı (gerçek telefonda denenmedi):
- APK kurulumu/açılışı, WebView içinde ses, Türkçe TTS (Android köprüsü)
- Geri tuşu, hata raporu kopyalama

Bilinen sorunlar / eksikler:
- İmza anahtarı her derlemede rastgele: güncelleme için eski sürümü silmek gerekebilir (çözüm: GitHub secret ile sabit anahtar)
- Sadece toplama ve çarpma. Çıkarma, bölme, parmak/ritim yolları yok
- Kullanıcının hangi öğrenme biçimine uyduğu henüz denenmedi

Sıradaki: kullanıcı denesin, hangi kısım oturdu söylesin; ona göre yön.
