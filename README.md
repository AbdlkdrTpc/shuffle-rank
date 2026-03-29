# Shuffle & Rank

A browser-based ranking video creator for social media. Add your items, shuffle, rank them, and record the result as a professional video — all from a single HTML file, no setup required.

Sosyal medya icin tarayici tabanli siralama videosu olusturucu. Ogelerinizi ekleyin, karistirin, siralamaya yerlestirin ve sonucu profesyonel bir video olarak kaydedin — tek bir HTML dosyasiyla, kurulum gerektirmeden.

## Live Demo / Canli Demo

**[https://abdlkdrtpc.github.io/shuffle-rank/](https://abdlkdrtpc.github.io/shuffle-rank/)**

## Features / Ozellikler

- **Shuffle & Rank** — Add up to 10 items, shuffle and place them into ranking slots / 10'a kadar oge ekleyin, karistirin ve siralama slotlarina yerlestirin
- **Image Upload** — Bulk image upload or manual text entry / Toplu gorsel yukleme veya manuel metin girisi
- **Video Recording** — Record 1080x1920 (9:16) video directly in the browser / Tarayici icinden 9:16 formatta video kaydi
- **Mic & Camera** — Voice commentary and webcam support / Sesli yorum ve webcam destegi
- **Sound Effects** — Synthesized SFX via Web Audio API / Web Audio API ile sentezlenmis ses efektleri
- **Color Themes** — 15 header colors with auto-generated gradient cards / 15 farkli baslik rengi ve otomatik gradient kartlar
- **Animations** — Shuffle, placement, confetti and final reveal animations / Karistirma, yerlestirme, konfeti ve final reveal animasyonlari
- **Intro Animation** — Dynamic or minimal intro options / Dinamik veya minimal intro secenekleri
- **Duration Control** — Shuffle duration from 1.5s to 7s / 1.5s ile 7s arasi karistirma suresi
- **Background Options** — Solid color, transparent or custom image/video background / Duz renk, seffaf veya ozel gorsel/video arka plani
- **Single File** — Standalone, no server or framework needed / Bagimsiz calisir, sunucu veya framework gerektirmez

## Usage / Kullanim

1. Open the [live demo](https://abdlkdrtpc.github.io/shuffle-rank/) or run `shuffle-rank.html` in your browser / [Canli demoyu](https://abdlkdrtpc.github.io/shuffle-rank/) acin veya `shuffle-rank.html` dosyasini tarayicinizda calistirin
2. Add items from the side panel (upload images or type names) / Sol panelden ogelerinizi ekleyin
3. Set the title, color and duration / Baslik, renk ve sure ayarlarini yapin
4. Click **Apply** / **Uygula** butonuna basin
5. Click the shuffle area and place cards into ranking slots / Karistir alanina tiklayin ve kartlari siralama slotlarina yerlestirin
6. Use recording mode to create your video / Kayit modu ile videonuzu olusturun

## Recording Mode / Kayit Modu

| Shortcut | Action / Islem |
|----------|----------------|
| `R` | Start/stop recording / Kaydi baslat/durdur |
| `M` | Toggle microphone / Mikrofon ac/kapat |
| `S` | Toggle sound effects / Ses efektleri ac/kapat |
| `C` | Toggle camera / Kamera ac/kapat |

## Tech Stack / Teknoloji

- Pure HTML + CSS + JavaScript (single file, ~116 KB) / Saf HTML + CSS + JavaScript (tek dosya, ~116 KB)
- Canvas API for 1080x1920 video rendering
- MediaRecorder API for in-browser video capture
- Web Audio API for synthesized sound effects

## License / Lisans

MIT
