# PDF Küçültücü

Ghostscript ile büyük PDF dosyalarını küçülten, canlı ilerleme gösteren komut satırı aracı. Tasarım programlarından çıkan ağır katalogları e-postayla gönderilebilir boyuta indirmek için yazıldı.

> Bu depo bir proje vitrinidir. Kaynak kod paylaşılmamaktadır.

## Özellikler

- Kalite profilleri: `ebook` (150 dpi, varsayılan), `screen` (en küçük boyut)
- JPEG kalitesinde ince ayar
- Sayfa sayfa canlı ilerleme yüzdesi
- **Güvenli mod:** Bazı Illustrator veya InDesign PDF'lerinde bozuk bir sayfa Ghostscript'in iç durumunu bozar ve sonraki sayfalar boş çıkar. Güvenli modda her sayfa ayrı bir Ghostscript sürecinde işlenip sonra birleştirilir.

## Teknolojiler

`Python` · `Ghostscript` · `subprocess`
