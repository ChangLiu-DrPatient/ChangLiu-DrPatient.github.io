# changliu-drpatient.github.io

Personal academic homepage, served at <https://changliu-drpatient.github.io/>.

A single static page — no build step, no framework, no external requests.
Edit `index.html` directly and push; GitHub Pages serves the default branch as-is.

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: markup, CSS, and JS inline |
| `Chang.jpg` | Headshot referenced by `index.html` |
| `cv_changliu.pdf` | Linked by the Curriculum Vitae button (add when compiled) |
| `.nojekyll` | Tells Pages to serve files verbatim instead of running Jekyll |

The publication filter counts are computed from the list at page load, so adding a
paper to the `<ul id="pubs">` list is the only edit needed — the chip totals follow.

The previous Hugo site lives in the `hugo-site-archive` repository.
