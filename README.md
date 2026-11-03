# Rawia Mhiri — Personal portfolio (selected work and demos)

A minimal academic-style static site for GitHub Pages. Three pages: `index.html`, `experience.html`, and `publications.html`.

## New in this version

- Preserved the homepage `About`, `Selected Work`, `Featured` (including the Adok Medium interview), and `Outside of Work` (Lille Marathon) sections.
- Added four user-supplied photos to Experience: GoPro object tracking, Adok interactive projection, Giroptic 360° imaging, and PhD multi-camera vehicle rig. Photos open at full resolution when selected.
- Added public demo links:
  - GoPro: [Tracking demo on Google Drive](https://drive.google.com/file/d/1K36116cVzpAuXo-okKpgn88uL-rQt2rN/view?usp=sharing)
  - Giroptic: [Demo 1](https://www.youtube.com/watch?v=HIu3Fz293rE) and [Demo 2](https://www.youtube.com/watch?v=QjvDdjy3CzE)
  - PhD research: [Video 1](https://www.youtube.com/watch?v=GycIlKgzkQ8) and [Video 2](https://www.youtube.com/watch?v=d3gp0YabA7k)
- Added contextual demo links from Home and the Publications page. Kept publication thumbnails, citations, and existing media links.
- No video files are bundled: external links load on YouTube / Google Drive.
- The CV PDF was omitted from the prior package and is **not** re-added here.

## Publishing

1. Extract the ZIP archive.
2. **Copy the contents of the extracted folder** (not the folder itself) into the root of your local `rawiamhiri.github.io` repository. Overwrite `index.html`, `experience.html`, `publications.html`, `style.css`, and the `assets` directory.
3. Run:

   ```bash
   git add -A
   git commit -m "Add research demos and project photos"
   git push
   ```

4. Check GitHub Actions → `pages build and deployment`, then refresh `https://rawiamhiri.github.io/`.

## Notes

- **Google Drive permission:** Verify that the video is shared publicly with viewers (e.g., anyone with the link) before publishing the link. Test it in a private/incognito tab.
- **Confidentiality:** Before sharing GoPro or other employer screenshots/demos publicly, confirm that publication is allowed.
- The two pairs of YouTube videos are labeled generically; no unsupported video titles or project-specific claims have been inferred from the URLs.
- Images are compressed JPEGs, kept at their original aspect ratios; no invented images are used.
