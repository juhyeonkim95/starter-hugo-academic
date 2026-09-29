---
title: "Light-Cone Shell Queries for Scalable Time-Gated Rendering"
# summary: "Uses light-cone range queries to efficiently sample time-valid light paths in geometrically complex scenes."
authors:
- Jack Cui
- admin
- Adithya Pediredla
- Wojciech Jarosz

author_notes:
date: "2026-07-01T00:00:00Z"
doi: "10.1111/cgf.70536"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Graphics Forum (EGSR 2026)*"
publication_short: ""

# abstract: Monte Carlo time-gated rendering requires sampling light paths that not only connect a sensor to an emitter, but which also have a total travel time that falls within a narrow interval, a constraint that is difficult to importance sample. We show that this problem has an underlying geometric structure: in the joint space of position and accumulated travel time, the points yielding a time-valid connection to a given query point form a light-cone shell bounded by two cones. We store the vertices of traced light subpaths in a 4D spatiotemporal hierarchy and recast time-gated connection as a range query, using pruning and importance sampling over the shell to select time-valid vertices without intersecting scene geometry. Within a bidirectional path tracing framework, our method significantly reduces variance over existing approaches on scenes with up to 2.4M triangles.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://jackcui.ca/publications/lightcone.pdf'
url_code: 'https://github.com/dartmouth-vcl/light-cone-shell-queries'
url_dataset: ''
url_poster: ''
url_project: 'https://jackcui.ca/publications/lightcone/'
url_slides: ''
url_source: 'https://diglib.eg.org/items/2942e21c-a70a-43e3-8b6a-4676361f553c'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
