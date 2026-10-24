# Welfare Aggregation

A paper written in LaTeX; `Welfare-Aggregation.tex` is where it starts.
One sentence per line, so that changes and conflicts stay small.

It follows TilTeX's template 1:

| Where | What it is for |
| --- | --- |
| `sections/` | The text, one file a section, put in by Welfare-Aggregation.tex in the order it lists them. |
| `figures/` | Figures, as images or PDFs: \includegraphics finds them by name (Welfare-Aggregation.tex's \graphicspath). |
| `tables/` | Tables, each a file put in where it goes with \input. |
| `original upload/` | What the paper was made from - an archive or a .tex file -, as it came: kept, never compiled. |
| `Welfare-Aggregation.tex` | Where the paper begins: what it uses, then each section's file in order. |
| `references.bib` | The references: one bibliography for the whole paper. |

Another document beside it - a supplement - is a `.tex` file of its own at the top, its
sections in a folder named after it (`supplement.tex`, `supplement/`). It shares the
figures, the tables and `references.bib`, and refers to the paper's labels with
`\usepackage{xr-hyper}` and `\externaldocument{Welfare-Aggregation}`.
