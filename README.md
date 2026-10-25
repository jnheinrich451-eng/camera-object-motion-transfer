# Camera & Object Motion Transfer — project page

The project page of the honours thesis *Recover, Retarget, Guide: camera and object motion transfer with a frozen video
model* (John Zeng, Australian National University, 2026; supervisor Dr Jing Zhang). It shows the method, the fifteen test
pairs beside the backbone without guidance, the development pairs beside the published methods, how the method got here,
the guidance ablations and the limitations. Served by GitHub Pages from this repository's root: `index.html`, `assets/`,
`videos/`, `figures/`.

The page is generated, not edited by hand: `scripts/make_project_page.py` in the code repository renders it from the
batch export, the sealed result tables and the thesis figures (`configs/project_page.yaml` holds the paths and the prose).
Every number on the page is parsed from those records. Code: https://github.com/jnheinrich451-eng/mixture-motion-transfer
