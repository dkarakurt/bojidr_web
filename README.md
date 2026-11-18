# bojid-R · web sitesi

bojid-R'ın tanıtım sitesi ve tarayıcıda çalışan sürümü.

- `index.html` — tanıtım sayfası (APK indir + web'de dene)
- `app/index.html` — bojid-R web sürümü (tek dosya). `app/?embed=1` tablet görünümünü zorlar; sitede gömülü demo bunu kullanır.
- `assets/` — logo ve ekran görüntüleri

APK bağlantısı her zaman en son sürümü indirir:
https://github.com/dkarakurt/bojid/releases/latest/download/bojid-R.apk
(APK, [dkarakurt/bojid](https://github.com/dkarakurt/bojid) reposunda GitHub Actions ile derlenir.)

## Yayın

`main` dalına her push'ta GitHub Actions siteyi GitHub Pages'e yayınlar.
Başka bir hostinge koymak için klasörün tamamını olduğu gibi yükle; derleme gerekmez.

## Web sürümünü güncellemek

`dkarakurt/bojid` reposundaki `web/index.html` değiştiğinde aynı dosyayı buradaki `app/index.html` üzerine kopyala ve push et.
