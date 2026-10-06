# KAMYON_BASINC OTA

Bu depo, `KAMYON_BASINC` firmware'inin yayin dosyalarini tutar.
Basarili `master` build'inden sonra GitHub Actions,
`ota/esp32/prod/firmware.bin` ve `ota/esp32/prod/metadata.json` dosyalarini
bu deponun `main` dalina gonderir. Cihaz metadata dosyasini
`raw.githubusercontent.com` uzerinden HTTPS ile okur.

Ilk OTA uyumlu firmware yeni partition tablosuyla seri porttan yuklenmelidir.
