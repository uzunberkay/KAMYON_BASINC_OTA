# KAMYON_BASINC OTA

Bu depo, `KAMYON_BASINC` firmware'inin yayin dosyalarini tutar.
Basarili `master` build'inden sonra GitHub Actions,
`ota/esp32/prod/firmware.bin` ve `ota/esp32/prod/metadata.json` dosyalarini
bu deponun `main` dalina gonderir. Cihaz metadata ve firmware dosyalarini
GitHub Pages uzerinden HTTPS ile okur:

`https://uzunberkay.github.io/KAMYON_BASINC_OTA/ota/esp32/prod/metadata.json`

Metadata `version`, `url` ve `sha256` alanlarini icerir.

Ilk OTA uyumlu firmware yeni partition tablosuyla seri porttan yuklenmelidir.
