# brunograuesp.github.io

Personal portfolio site for **Bruno Grau Espinosa**, a Mechanical Engineering student
and NCAA Division I diver at the University of Wyoming.

Static site: plain HTML, CSS, and a small JavaScript file. No build step. Every file
lives at the repository root.

## Local preview

Open `index.html` directly in a browser, or run a tiny local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Files

```
index.html              All page content
style.css               Styles (Wyoming brown & gold, warmed with sand / khaki / terracotta)
main.js                 Mobile nav, scroll reveal, active-link highlighting
favicon.svg             Browser tab icon
*.jpg / *.mp4           Photos and the project video
Bruno_Grau_Resume.pdf   Linked from the nav and Contact section
```

## Editing content

Everything is in `index.html`, section by section:
`#home` · `#about` · `#experience` · `#projects` · `#athletics` · `#leadership` · `#skills` · `#contact`.

## Swapping photos

Replace a file with the **same name**, or change the `src="..."` in `index.html`.

| Slot | File |
| --- | --- |
| Hero portrait | `hero-portrait.jpg` |
| About | `about.jpg` |
| Diving action shot | `diving.jpg` |
| Autonomous platform | `project-car.jpg`, `project-car.mp4`, `project-car-poster.jpg` |
| Composite wall | `project-wall-setup.jpg`, `project-wall-result.jpg` |
| Myriam Espinosa Art | `art-1.jpg`, `art-2.jpg`, `art-3.jpg` |
| Social share | `og-image.jpg` |

## Deploy (GitHub Pages)

Repo **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
The site publishes at `https://brunograuesp.github.io`.
