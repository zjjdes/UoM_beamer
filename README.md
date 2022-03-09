# UoM_beamer
This is an unofficial LaTeX Beamer presentation template with The University of Melbourne theme.

This repository is forked from [sanhacheong/stanford-beamer-presentation](https://github.com/sanhacheong/stanford-beamer-presentation). The color theme is designed based on [the official UoM color palette](https://brandhub.unimelb.edu.au/guidelines/colour-palette).

Citations are numbered and rendered in the footnotes with author name, journaltitle and year (printed items can be changed around line 53 in [packages.tex](./preambles/packages.tex)). Use `\cite{bibitem}` to cite. The footnote citation will be printed for the first time only.

To disable footnote citations and print citations in a References section using APA or IEEEtran, uncomment the last frame in the slides, comment lines 36-77 and uncomment lines 33 in [packages.tex](./preambles/packages.tex).