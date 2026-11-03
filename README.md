# Screen Stream Mirroring (64-Bit Edition for OBS Studio & VLC)

Ushbu loyiha Android 10–15+ (`arm64-v8a` 64-bit) smartfonlar ekranini va ichki ovozini (**Internal Audio + Microphone**) **TCP protokoli (`MPEG-TS` H.264 + AAC)** orqali **OBS Studio** va **VLC** dasturlariga kechikishsiz (<80 ms) uzatib beruvchi to'liq, barqaror Android ilova hisoblanadi.

## APK faylni 2 xil usulda olishingiz mumkin:

### 1-usul (Kompyutersiz — GitHub orqali 2 daqiqada tayyor APK olish):
1. GitHub'da yangi repository oching va ushbu papkadagi barcha fayllarni yuklang.
2. **Actions** bo'limiga o'ting — `.github/workflows/build-apk.yml` avtomatik ishga tushadi.
3. 2 daqiqadan so'ng **OBS-TCP-Screen-Streamer-64bit-APK** bo'limidan tayyor 64-bitli `.apk` faylni yuklab olib telefoningizga o'rnating!

### 2-usul (Android Studio orqali):
1. Loyihani **Android Studio** dasturida oching (`Open`).
2. `Build -> Build Bundle(s) / APK(s) -> Build APK(s)` tugmasini bosing.
