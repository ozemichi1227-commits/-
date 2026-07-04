# cure-vas English site

English version of **cure-vas.jp** — the information site of the research group on drug
therapy for intractable vascular tumors and vascular malformations (AMED Ozeki Group /
Sirolimus Research Group), Department of Pediatrics, Gifu University Hospital.

MICHI制作

## Approach

Each page is a faithful English rendering of the original Japanese page: the exact same
design, layout, colours, illustrations (Mol Friends), and images are preserved, and **only
the Japanese text is replaced with English**. Pages were captured from the live site with
SingleFile (all CSS and images embedded), then the Japanese text nodes were translated in
place. Furigana (ruby readings) are removed because they are not meaningful in English.

## Pages (mirrors the original site structure)

| Path | Original | Page |
|------|----------|------|
| `index.html` | `/` | Home |
| `beginners/` | `/beginners/` | Newly Diagnosed |
| `list/` | `/list/` | How to Tell the Diseases Apart |

More pages will be added as the remaining originals are provided.

## Notes

- Internal links between translated pages are rewired to the local English pages; links to
  pages not yet translated still point to the live Japanese site (cure-vas.jp).
- Pages are self-contained (images embedded as data URIs), so each file is a few MB.
- Sections that explain Japanese-specific terminology (e.g. 血管奇形 vs 脈管奇形) currently
  keep a romanized reading in English; how to handle these is under review.
