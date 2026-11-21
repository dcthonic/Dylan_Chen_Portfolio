# Project asset folders

Each folder matches the project `slug` used in the `PROJECTS` array in the root `index.html`. Keep that project's thumbnail, diagrams, papers, CAD exports, and recordings together in its folder. The `index.html` still holds the project narrative and specifications because the site is intentionally build-free.

| Project slug | Folder | Current files |
| --- | --- | --- |
| `engineering-portfolio-website` | `engineering-portfolio-website/` | `thumbnail.svg` |
| `custom-nh35-watch-dial` | `custom-nh35-watch-dial/` | thumbnail, CAD renders and workplane images from the design portfolio |
| `24-7-shift-roster-generator` | `24-7-shift-roster-generator/` | `thumbnail.png` |
| `physics-extended-essay` | `physics-extended-essay/` | hydraulic-jump diagrams, flume and gate photos, paper, and `recordings/` |
| `idex-water-filtration` | `idex-water-filtration/` | thumbnail, concept sketch, prototype test-rig photo, and IDEX certificate |

## Add or update a project

1. Add its files under `projects/<project-slug>/`.
2. Find or add the project object with the same `slug` in `index.html`.
3. Set `thumb`, gallery, video, paper, or other paths to files inside that folder.
4. Add the new paths to the site file tree in the root `README.md` and rebuild `github-pages-upload.zip`.
