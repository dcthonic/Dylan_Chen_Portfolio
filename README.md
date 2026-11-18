[README.md](https://github.com/user-attachments/files/35012675/README.md)
# Dylan Chen — Mechanical Engineering Portfolio

Live site: [dcthonic.github.io/Dylan_Chen_Portfolio](https://dcthonic.github.io/Dylan_Chen_Portfolio/)

A project portfolio covering mechanical design, prototyping, experimental research, and automation. The site is a static GitHub Pages project: its layout, styles, and interactions live in `index.html`; it has no server, database, or build step.

## Projects

- **Engineering Portfolio Website** — responsive, single-page portfolio with project filters and shareable project pages.
- **Custom NH35 Watch Dial** — CAD design, FDM prototypes, manufacturing constraints, and SLM titanium plans.
- **24/7 Shift Roster Generator** — scheduling and fairness tools across Excel/Python and Google Sheets/Apps Script.
- **Physics Extended Essay: Hydraulic Jumps** — acrylic flume experiment, measured results, paper, and four video recordings.
- **IDEX Water Filtration** — a portable, non-electric water-filtration prototype.

The home page includes the latest projects and an interactive exhibit for the hydraulic-jump experiment. The full collection has category filters; each project page combines its narrative with relevant diagrams, images, specifications, and evidence. Education, experience, awards, certificate scans, CV, and contact links are also available from the site.

## Publish with GitHub Pages

Upload the files and folders listed below to the repository root. Keep `videos/` as a folder with all four MP4 files inside it. In GitHub, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.

If you use the prepared `github-pages-upload.zip` bundle, extract it locally and upload its contents to the repository root. Do not upload the ZIP file as the website itself.

### Site files

```text
index.html
README.md
Dylan Chen CV.pdf
ee-paper.pdf
IB_Results_&_Cert.pdf
Cert_ACSI.pdf
IDEX_Cert.pdf
SYPT_Cert.pdf
physics-hydraulic-jump-diagram.png
roster-generator-preview.png
watch-dial-preview.png
idex-water-filter-preview.jpg
engineering-portfolio-preview.svg
engineering-background-graphic.svg
videos/
  ee-01.mp4
  ee-02.mp4
  ee-03.mp4
  ee-04.mp4
```

File paths are case-sensitive on GitHub Pages. If you rename a file or move it into a folder, update its matching path in `index.html`.

## Local preview

Open `index.html` in a browser for a quick preview. To test PDFs and videos under normal web hosting behavior, serve the repository folder with a local static-file server, then open its local URL.

The page uses Jost and Source Serif 4 from Google Fonts when available, with local system font fallbacks. All site content and interactions work without a build tool.
