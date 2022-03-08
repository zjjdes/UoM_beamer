# UoM_beamer
This is an unofficial LaTeX Beamer presentation template with The University of Melbourne theme.

This repository is forked from [sanhacheong/stanford-beamer-presentation](https://github.com/sanhacheong/stanford-beamer-presentation). The color theme is designed based on [the official UoM color palette](https://brandhub.unimelb.edu.au/guidelines/colour-palette).

Citations are numbered and rendered in the footnotes with author name, journal and year (printed items can be changed around line 42 in [packages.tex](./preambles/packages.tex)). Use `\autocite{paper} \foorpartcite{paper}` to cite for the first time. For subsequent citations, use `\autocite{paper}` only.

To disable footnote citations and print citations in a References section using APA, uncomment the last frame in the slides, comment lines 35-55 and uncomment lines 33-34 in [packages.tex](./preambles/packages.tex).