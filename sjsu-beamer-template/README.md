# SJSU Beamer template

This template is a Beamer starting point aligned to San José State University’s published University Marks page and Brand Style Guide.

## Compile

```bash
xelatex main.tex
xelatex main.tex
```

The two passes resolve the total slide count in the footer.

If XeLaTeX or LuaLaTeX is not installed, `pdflatex main.tex` also works with the fallback sans-serif font.

## Included

- `sjsu-beamer.sty`: theme, colors, title page, frame title, footer, blocks and spacing.
- `main.tex`: small example deck showing the intended usage.
- `assets/sjsu-primary-mark.png`: official primary mark downloaded from SJSU’s published asset bundle.

## Brand-use notes

- SJSU Blue: `#0055A2`; Gold: `#E5A823`; Gray: `#939597`; Dark Gray: `#53565A`.
- The primary logo is kept intact and placed with generous clear space.
- The title-page mark is larger than the published 1-inch minimum width for the primary logo.
- Do not rotate, distort, recolor, shadow, separate, or add elements to official marks.
- Use the official university seal only for formal uses and only with the required approval.
- Replace the example figure with approved, authentic imagery or figures appropriate to your audience.

The university’s standards can change. Before distributing a final deck, verify the current guidance at:
<https://www.sjsu.edu/communications/brand/visual-style/university-marks/index.php>
