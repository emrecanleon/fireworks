# FireWorks

Bağımlılıksız, tek dosyalık HTML5 Canvas havai fişek oyunu. Çevrimdışı çalışır, telefona PWA olarak yüklenebilir.

## Kurulum

**GitHub Pages:** Repoyu yükle → Settings → Pages → Branch: `main` / `(root)` → Save.

**Cloudflare Pages:** Repoyu bağla → Build command: boş bırak → Output directory: `/`.

**Netlify:** Repoyu bağla; `netlify.toml` otomatik okunur.

## Telefona yükleme

- **Android (Chrome):** Menü → "Ana ekrana ekle" / "Uygulamayı yükle".
- **iOS (Safari):** Paylaş → "Ana Ekrana Ekle".

## Güncelleme

`sw.js` içindeki `VERSION` değerini artır; kullanıcılar bir sonraki açılışta otomatik güncellenir.

## Yapı

```
index.html  manifest.webmanifest  sw.js
_headers  netlify.toml  .nojekyll  LICENSE  README.md
icons/  (apple-touch-icon.png, icon-192.png, icon-512.png)
```

## Lisans

MIT — © 2026 A. Emre Canaslan
