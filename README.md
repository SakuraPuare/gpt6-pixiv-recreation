# GPT-6 Pixiv Recreation

This project explores how far a browser can take a reference-led illustration using HTML, CSS, and SVG paths. The goal is to make the composition feel hand-layered: background atmosphere first, the vector artwork second, and restrained foreground motion and highlights last. The SVG contains no embedded raster image and no `<image>` or `<img>` element.

The page is deliberately dependency-free. Its responsive stage keeps the original artwork ratio, scales from the full viewport width, clips horizontal overflow, and respects `prefers-reduced-motion`. CSS animation is split by layer so the background drifts behind the artwork while glints appear in front, preserving the visual hierarchy of a hand-composed scene.

## Live page

[Open the GPT-6 vector presentation](https://sakurapuare.github.io/gpt6-pixiv-recreation/)

## Attribution

- Original artwork: [Pixiv artwork 131538488](https://www.pixiv.net/artworks/131538488)
- The original artwork was used only as a visual reference during vectorization and is not loaded by the page.
