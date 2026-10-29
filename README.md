# FMC1278 Transient Generator (Düşük Maliyetli Yapım)

Ford FMC1278 standardındaki besleme hattı geçici gerilim (transient) testleri için kullanılan darbe jeneratörü devresinin düşük maliyetle yeniden üretimi. Komponent seçimi, tedarik, kutulama ve doğrulama testi tamamlandı.

## Amaç

Standartta tanımlı test devresini (Pulse A1, A2 ve C darbeleri) hazır cihaz satın almadan, kendi seçtiğim komponentlerle üretmek ve çalıştığını doğrulamak.

## Devre

Devre; giriş anahtarı (SW0), seri bobin (L1), röle (RLY1) ve transistör (Q1) ile yapılan tetik katı, zener diyot (D1) koruması, anahtarlanabilir yük ağı (R2, C1, L2, R3, R4 ve SW2, SW3, SW4) ve test fikstürü için BNC konnektörlerinden oluşur.

- **CI 220 testi:** TF IN ve TF OUT kısa devre edilir.
- **RI 130 testi:** Test fikstürü TF IN ve TF OUT arasına takılır.
- **Harici tetik:** TR-IN girişinden verilir.

## Yapım

1. Şemadaki gerekli komponentleri seçtim ve sipariş verdim.
2. Alüminyum bir kutuya anahtarları ve banana konnektörleri monte ettim.
3. Pulse A1/A2, Pulse C, TR-IN ve BNC çıkışlarını kutu üzerine çıkardım.
4. Kutu gövdesini transient jeneratörünün toprağına bağladım.

## Test

20 Hz tetik sinyali ile çalıştırıldı, devre beklenen şekilde çalıştı.

Fotoğraflar `images/` klasöründe.

## Güvenlik

Devre yüksek enerjili darbeler üretir. Bağlantıları enerji vermeden önce yapın, kutuyu topraklayın ve test sırasında açık uçlara dokunmayın.

## Not

Bu proje bağımsız bir yapım ve doğrulama çalışmasıdır. Standardı yayınlayan firma ile bağlantısı yoktur. Standardın kendisi bu repoda yer almaz.
