# FELDA – Homepage Live Mockup

Static HTML mockup of the FELDA homepage redesign (Bahasa Melayu). Single file, no build step.

## Folder structure

```
index.html
assets/
  img/
    logo-felda-70.png   ← 70 Tahun + FELDA logo (top bar logo)
    hero-felda.jpg      ← hero banner (family at sunset)
```

## Setup on GitHub Pages

1. Create a new repo (e.g. `FELDA-2`) under your `ui-mockup` account.
2. Upload `index.html`.
3. Create the folder `assets/img/` and upload your two images with the exact names above.
4. Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch `main`, folder `/ (root)` → Save.
5. Live in ~1 minute at `https://ui-mockup.github.io/FELDA-2/`.

## Notes

- Main menu dropdowns (Peneroka, Perkhidmatan, Berita, Mengenai FELDA, Hubungi) use the same submenu content as FELDA-1. Desktop = hover mega menu; mobile = slide-in drawer with accordion.
- Inisiatif cards: the orange bottom bar morphs into the diagonal "Biasiswa" block on hover (on touch screens the hover state shows by default).
- Placeholder photos load from Unsplash — replace the `background-image` URLs with FELDA's own photos.
- Brand colours are CSS variables at the top of the `<style>` block (`--orange`, `--red`, etc.).
