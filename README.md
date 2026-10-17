# Legaluga UDF Editor

Windows, macOS ve Linux için Legaluga UDF Editor kurulum paketleri.

[İndirme ve kurulum](https://legaluga.com/udf-editor/indir)

Bu depo yalnızca dağıtım paketlerini, sürüm notlarını ve dağıtım bilgilerini içerir. Uygulama kaynak kodu burada yayımlanmaz.

Her sürümün dosya özetleri SHA256SUMS.txt dosyasında bulunur.

## İndirme sitesi

`site/` klasörü [legaluga.com/udf-editor/indir](https://legaluga.com/udf-editor/indir) sayfasını ve masaüstü uygulamasının sürüm kaynağı olan `https://legaluga.com/downloads/udf-editor/stable.json` dosyasını içerir. Vercel'deki `legaluga-desktop-downloads` projesi bu klasörü derlemeden yayınlar; `main` dalına gelen her değişiklik canlıya çıkar.

Yeni sürümde `scripts/prepare-desktop-publication.mjs` çıktısındaki `site/` klasörünün içeriğini buraya kopyalayın. `stable.json` değişince kurulu uygulamalar altı saat içinde güncelleme bildirimi gösterir; bu yüzden değişikliği GitHub sürümü yayımlandıktan sonra birleştirin.
