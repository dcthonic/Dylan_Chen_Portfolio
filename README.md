[README.md](https://github.com/user-attachments/files/35022767/README.md)
# Dylan Chen — Engineering Portfolio

A responsive, single-file portfolio for GitHub Pages. The site is built with HTML, embedded compiled Tailwind CSS, and vanilla JavaScript. It has no build step, backend, or database.

**Live site:** <https://dcthonic.github.io/Dylan_Chen_Portfolio/>

## Repository layout

```text
index.html                     Main site and portfolio content
assets/site/                   Shared site graphics
documents/                     CV, education records, and award certificates
projects/<project-slug>/       Each project's media and supporting documents
development/plugins/           Local design reference; not required by the site
github-pages-upload.zip        Upload bundle for current assets and project files
```

The upload ZIP intentionally excludes `index.html` and this README. Upload the HTML file separately. GitHub Pages serves the files at the paths referenced in `index.html`, so preserve folder names and filenames.

## Publish or update the site

1. In the GitHub repository, choose **Add file → Upload files**.
2. Upload `index.html` and the contents of the latest `github-pages-upload.zip` to the repository root. Keep the `assets/`, `documents/`, and `projects/` folders intact.
3. Add or replace any new media files at the exact paths referenced by `index.html`.
4. Commit the changes to the branch used by GitHub Pages (currently `main`).
5. Check the repository's **Actions** tab for the Pages deployment, then open the live site.

For future updates, the ZIP in this folder is only a snapshot of the assets at the time it was created. If you add files, upload those new files separately or create a refreshed bundle. Do not rely on an older ZIP to contain new media.

## Add a project

1. Create `projects/<project-slug>/` using a short lowercase slug, such as `projects/example-project/`.
2. Put that project's thumbnail, diagrams, videos, papers, and other evidence in its folder. Keep media with the project it belongs to.
3. In `index.html`, add or update the matching project in the `PROJECTS` data array. Use the same slug and repository-relative paths, for example `projects/example-project/thumbnail.png`.
4. If the project needs a custom editorial page, add its content to the `PAGES` data in `index.html`. Link media with paths relative to the repository root.
5. Upload the changed `index.html` and the new project folder contents, preserving the folder structure, then commit.

## Add an award or certificate

1. Place the certificate PDF in `documents/awards/` (create a subfolder if you want to keep multiple files for one award together).
2. Add the award details to the award entries in `index.html` and link to the PDF with its repository-relative path, such as `documents/awards/example-certificate.pdf`.
3. Upload the updated HTML file and certificate, preserving the path, then commit.

Education records belong in `documents/education/`. The CV is stored at `documents/Dylan Chen CV.pdf`; if you rename or move it, update the CV path configured in `index.html` as well.

## Current project folders

- `engineering-portfolio-website/` — portfolio thumbnail
- `custom-nh35-watch-dial/` — watch dial thumbnail and IDEX certificate is kept with the IDEX project instead
- `24-7-shift-roster-generator/` — roster generator thumbnail
- `physics-extended-essay/` — hydraulic jump diagram, essay PDF, and experiment videos
- `idex-water-filtration/` — project thumbnail and IDEX certificate

The design reference under `development/plugins/` is for local editing workflow only. It is not required to host or run the portfolio.
