# Shuffle & Rank

**Shuffle & Rank**, sosyal medya icin siralama videolari olusturmaya yarayan tarayici tabanli bir aractir. Ogelerinizi ekleyin, karistirin, siralamaya yerlestirin ve sonucu profesyonel bir video olarak kaydedin — tek bir HTML dosyasiyla, kurulum gerektirmeden.

## Canli Demo

**[https://abdlkdrtpc.github.io/shuffle-rank/](https://abdlkdrtpc.github.io/shuffle-rank/)**

## Ozellikler

- **Karistir & Sirala** — 10'a kadar oge ekleyin, karistirin ve siralama slotlarina yerlestirin
- **Gorsel Yukleme** — Toplu gorsel yukleme veya manuel metin girisi
- **Video Kayit** — Tarayici icinden 1080x1920 (9:16) formatta video kaydi
- **Mikrofon & Kamera** — Sesli yorum ve webcam destegi ile icerik uretimi
- **Ses Efektleri** — Web Audio API ile sentezlenmis ses efektleri
- **Renk Temalandirma** — 15 farkli baslik rengi ve otomatik gradient kartlar
- **Animasyonlar** — Karistirma, yerlestirme, konfeti ve final reveal animasyonlari
- **Intro Animasyonu** — Dinamik veya minimal intro secenekleri
- **Sure Ayari** — 1.5s ile 7s arasi karistirma suresi
- **Arka Plan Secenekleri** — Duz renk, seffaf veya ozel gorsel/video arka plani
- **Tek Dosya** — Bagimsiz calisir, sunucu veya framework gerektirmez

## Kullanim

1. [Canli demoyu](https://abdlkdrtpc.github.io/shuffle-rank/) acin veya `shuffle-rank.html` dosyasini tarayicinizda calistirin
2. Sol panelden ogelerinizi ekleyin (gorsel yukleyin veya isim yazin)
3. Baslik, renk ve sure ayarlarini yapin
4. **Uygula** butonuna basin
5. **Karistir** alanina tiklayin ve kartlari siralama slotlarina yerlestirin
6. Kayit modu ile videonuzu olusturun

## Kayit Modu

| Kisa Yol | Islem |
|----------|-------|
| `R` | Kaydi baslat/durdur |
| `M` | Mikrofon ac/kapat |
| `S` | Ses efektleri ac/kapat |
| `C` | Kamera ac/kapat |

## Teknoloji

- Saf HTML + CSS + JavaScript (tek dosya, ~116 KB)
- Canvas API ile 1080x1920 video render
- MediaRecorder API ile tarayici icinde video kaydi
- Web Audio API ile sentezlenmis ses efektleri

## Lisans

MIT
