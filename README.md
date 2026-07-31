# FasTac Project Website

Standalone static homepage for the FasTac research project and its arXiv preprint:

- Paper: <https://arxiv.org/abs/2607.28416>
- Project page: <https://jayvenlu.github.io/fastac-website/>
- Repository: <https://github.com/JayvenLu/fastac-website>

Intended GitHub Pages URL:

```text
https://jayvenlu.github.io/fastac-website/
```

## Local Preview

Run from the repository root:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

The site is a zero-build static project using HTML, CSS, and a small amount of
vanilla JavaScript.

## Content

The page embeds web-optimized copies of the final paper figures and supplementary
videos. The public project repository contains only the website; research source
code, datasets, manuscript sources, and internal project files are not included.

The FPGA energy value described by the page is based on Vivado estimates combined
with scheduled RTL/HLS latency, not a board-measured end-to-end energy value.

## Maintenance

- Keep the title, author order, abstract claims, and metrics aligned with the current arXiv version.
- Replace the arXiv citation with final publication metadata after acceptance.
- Re-encode replacement videos as H.264/YUV420P MP4 with fast-start metadata.
- Verify responsive layouts and external links before each Pages deployment.

## Rights

Paper figures, videos, and project materials remain the property of their
authors. Reuse or redistribution requires author permission.
