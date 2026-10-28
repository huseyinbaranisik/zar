# ⚄ Zar At

Neo Brutalism tasarımlı, telefonda ve bilgisayarda çalışan basit bir zar atma sitesi. d4, d6, d8, d10, d12 ve d20 zarlarını destekler; telefonu sallayarak da atılabilir.

**Canlı:** https://huseyinbaranisik.github.io/zar/

<p>
  <img src="screenshot.png" alt="Açık tema" width="300">
  <img src="screenshot-dark.png" alt="Karanlık tema" width="300">
</p>

## Özellikler

- Sade arayüz: sağ üstte minik zar ikonları, ortada sadece zar — zara dokun, at
- Her zar kendi silüetinde (d4 üçgen, d6 kare, d8 eşkenar dörtgen, d10 uçurtma, d12 beşgen, d20 altıgen) döner, zıplar ve sonuca oturur
- Boşluk / Enter ile ya da telefonu sallayarak da atılabilir (iOS'ta izin zara ilk dokunuşta istenir)
- Kritik sonuçlar: en yüksek değerde konfeti + yeşil gölge, 1 gelince sarsılma + kırmızı gölge
- `crypto.getRandomValues` ile sapmasız rastgelelik
- Web Audio ile kodda üretilen ses efektleri (ses dosyası yok): zar takırtısı, buton klik sesi, en yüksek sayıda kutlama, 1 gelince başarısızlık sesi; açılıp kapatılabilir
- Açık / karanlık tema (ilk açılışta sistem temasına uyar)
- `prefers-reduced-motion` desteği; zar tipi, tema ve ses tercihi hatırlanır

## Çalıştırma

Tek bir `index.html` dosyası; build adımı ya da bağımlılık yok. Dosyayı tarayıcıda açman yeterli.
