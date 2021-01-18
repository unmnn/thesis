# Bookdown tutorial {.unnumbered}

- custom (sub-)section label: `{#id}`
- citation: `[@PechenizkiyEtAl:CBMS10]`
- reference to figure or table: `\@ref(tab:cha_questionnaires)`
- reference to (sub-)section: `\@ref(cha)` 
- custom label outside of code chunk header: 
  - figures: (ref:04_prospector) xxx
  - tables: Table: (\#tab:03-costmatrix)
- equations (\#eq:shapley)


- replace LaTex references with bookdown references
  - replace ~?\\ref\{(.*?)\} with \\@ref(\1)
- replace LaTex citations with bookdown citations
  - replace \\cite\{(.*?)\} with [@\1]
  

## Special symbols

- checkmark: \\ding{51} (LaTeX), \U2713 (Unicode)
- cross: \\ding{55} (LaTeX), \U2717 (Unicode)

## Additional LaTeX packages

In YAML:

```
header-includes:
  - \usepackage{pifont}
```
