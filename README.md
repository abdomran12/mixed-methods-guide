# Mixed-Methods Research Guide

A free, self-guided guide to adding quantitative analysis to qualitative research in the humanities and social sciences, and then going back to reading.

- Ten steps in four stages: Read, Build, Scale, Read again
- Working tools in the browser: claim builder, codebook, agreement check, validation, cross-tab, joint display, ethics checklist
- 15 short clips that play in the page, with transcripts
- A section on coding large, multilingual collections with free open-weight models (Ollama, Groq, Google AI Studio, OpenRouter), with Python scripts and real test results
- Example designs across eight disciplines, and a reading list of 104 works with checked links

Open `index.html`, or visit https://abdomran12.github.io/mixed-methods-guide/

## Files

| File | What it is |
|---|---|
| `index.html` | The whole guide in one page |
| `card-sorter.html` | 3D card-sorter simulation (three.js) |
| `*.mp4` | The clips the page plays |

Nothing is sent anywhere. Entries are kept in the visitor's own browser (localStorage).

## Publish for free with GitHub Pages

1. Create a public repository on GitHub, for example `mixed-methods-guide`.
2. Upload every file in this folder (Add file → Upload files). The largest file is under 7 MB, well within GitHub's limits.
3. Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
4. After a minute the site is at `https://<your-username>.github.io/mixed-methods-guide/`.

For a citable version with a DOI, connect the repository to Zenodo and make a GitHub release.

## Worked case and data

The worked case comes from Abdullah Omran's doctoral research on Egyptian family vlogs on YouTube (Indiana University). Only aggregate shares and short translated, anonymised paraphrases appear. The 24 multilingual comments in the Scale up section were invented for practice.

## Third-party material

- *Tutorial: Voyant-Tools zur Textvisualisierung nutzen*, forTEXT, CC BY 4.0, doi:10.5281/zenodo.10354065
- Screen recordings of Voyant Tools (voyant-tools.org) and ReCal2 (dfreelon.org/utils/recalfront) show those public tools in use
- YouTube tutorials are linked, not copied
- Isometric figure built with the Anatomy kit; card sorter built with the Teardown kit and three.js (MIT licences)
- Fonts: Oswald, Source Sans 3, IBM Plex Mono, Noto Naskh Arabic, served by Google Fonts (SIL Open Font Licence)

## Licence

Text, figures and the guide's own videos: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), see `LICENSE-CONTENT.txt`. Code (HTML, CSS, JavaScript, Python examples): MIT, see `LICENSE`. Third-party material listed above keeps its own licence.

Cite as: Omran, Abdullah. 2026. *Mixed-Methods Research Guide*. https://abdomran12.github.io/mixed-methods-guide/
