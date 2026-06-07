# FasTac Project Website

Private preview repository for the FasTac paper project page.

## Local Preview

Run from the repository root:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

The site is a zero-build static project using HTML, CSS, and a small amount of
vanilla JavaScript.

## Content Status

- Manuscript status: under review
- Paper PDF: not included
- Source code: not included
- Dataset: not included
- GitHub Pages: keep disabled during private review

The FPGA energy values described by the page are Vivado estimates combined
with scheduled RTL/HLS latency. They are not presented as board-measured
end-to-end energy.

## Asset Sources

Figures and videos are derived from the private FasTac manuscript workspace
and were converted specifically for this preview. The website contains
web-optimized derivatives rather than manuscript source files or raw videos.

## Public Release Checklist

- Confirm manuscript disclosure approval and final publication status.
- Replace `Under Review` and add the stable paper link.
- Add BibTeX only after publication metadata is available.
- Confirm whether code and dataset repositories can be linked publicly.
- Recheck all reported metrics against the final manuscript.
- Enable GitHub Pages only after the repository is intentionally made public.
- Add the project-page link to the author profile after publication.

## Rights

Paper figures, videos, and project materials remain the property of their
authors. They may not be reused or redistributed without permission.
