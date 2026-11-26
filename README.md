# LivingGo Pro — kanal logoları ve EPG listeleri

Uygulama bu dalı kendisi indirir (günde bir, ya da Ayarlar → Güncellemeler → Logoları şimdi güncelle).

- `logos.zip` — küçük logo paketi (logo başına ~2.5 KB, en fazla 160 px). Kaynak sırası: tv-logo/tv-logos → iptv-org → Türksat picon → erdodo.
- `epgids.json` — kanal adı → EPG kimliği (ör. `TRT1.tr`). Kanala EPG otomatik atanır (varsayılan); kullanıcının kendi "EPG Ata" seçimi her zaman önce gelir.
- `listeler/` — ülke ülke kanal listesi (kanal adı, tvg-id, logo, EPG dosyaları): tr, de, fr, nl, be, gb, se, no, dk, fi. `tr_kanal_logolari.csv` = Türk kanal logo tablosu (743 kanal).
- `logolar/` — logolar tek tek.
