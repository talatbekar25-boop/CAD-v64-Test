# CAD Reader v64 Test APK

Bu paket GitHub Actions ile test APK üretmek için hazırlanmıştır.

1. Bu paketin içindeki dosyaları GitHub deposunun ana dizinine yükle.
2. GitHub'da Actions sekmesine gir.
3. `Build Android APK` iş akışını aç.
4. `Run workflow` düğmesine bas.
5. İşlem yeşil tamamlanınca sayfanın altındaki `Artifacts` bölümünden `CAD-Reader-v64-test-APK` dosyasını indir.
6. İndirilen ZIP'i aç ve `app-debug.apk` dosyasını telefona kur.

Testte özellikle kontrol et:
- Uygulama açılıyor mu?
- DXF açılıyor mu?
- DWG açılıyor mu?
- Büyük DWG'de yakınlaştırma/kaydırma akıcı mı?
- Ölçü değerleri doğru mu?
- Metraj ayrı çalışıyor mu?
- Metrajdan Hakediş & Maliyet bölümüne aktarım çalışıyor mu?
- Uygulamayı kapatıp açınca kayıt/kurtarma çalışıyor mu?
