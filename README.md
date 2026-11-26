# LivingGo Pro — yazılım güncellemeleri

Her APK yalnızca kendi dosyasını okur (yanlış APK yüklenmez):

| APK | Dosya |
|---|---|
| Universal (TV kutusu, Android TV, Fire TV) | `universal.json` |
| Telefon-Tablet 64-bit | `arm64.json` |
| Eski cihaz 32-bit (hafif) | `armv7.json` |

Google Play sürümü kendini güncellemez. `apk.json` eski sürümler içindir ve artık değiştirilmez.
