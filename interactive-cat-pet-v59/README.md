# Interactive Cat Pet

Open `index.html` in a browser.

V11 update: Idle uses the green-screen tail-swish video frames 04-10. The green background and shadow were chroma-keyed out, with edge despill to reduce green outline.

V12 tweak: slowed Idle tail animation to 420ms per frame and Groom animation to 330ms per frame for a calmer, more natural feel.

V30 update: unified orange fur color across play/groom/walk/eat/sleep using idle as the color reference. White fur and transparency were preserved.

V32 update: adjusted only the sleep cat image to restore more fur detail and reduce the over-softened look from V31.

V33 update: replaced the Sleep image with the newly generated sleeping cat asset, cut out from the checkerboard background and placed on the existing sleep canvas size to avoid layout changes.

Version v42: replaced assets/play/cat_play_2.png with the newly generated play frame.


v44: repaired transparency/missing-fur artifact in Play frame 2.

v46: Cleaned the transparent background/matte for every Play frame. Rebuilt the Play frame near the ball so the page background shows through instead of a white patch.

v59: Repaired a visual artifact in Groom frame 3 (clone-stamped from clean surrounding fur regions) for a seamless grooming loop.

## Play it online
This page is a static site — no build step, no server needed. Enable GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder) and open the generated `https://<username>.github.io/<repo>/` link in any browser.
