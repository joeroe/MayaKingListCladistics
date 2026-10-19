# Cladistic analysis of Maya king lists

<!-- TODO Zenodo badge -->

This is a compendium of data and R code accompanying our forthcoming paper:

> Helmke, Christophe, Vepretskii, Sergei, and Roe, Joe. in prep. Hacia una 
> crítica textual de las fuentes históricas mayas del periodo Clásico [Towards 
> a Textual Criticism of Classic Maya Historical Sources]. Under review for
> *Estudios de Cultura Maya*.

It describes a cladistic analysis of Maya king lists with the aim of
reconstructing the sequence of their authorship.

## Usage

`maya_king_list_cladistics.html` is a self-contained HTML file summarising the 
results of our analysis, including the figures used in the paper. It was 
rendered from the markdown and R code in `maya_king_list_cladistics.qmd` with 
[Quarto](https://quarto.org/). The character matrix describing the king lists,
used for the analysis, can be find in Excel format in `data/king-lists.xslx`.

`renv.lock` records the exact dependency versions used to produce our
analysis. You can restore this environment with
[renv](https://rstudio.github.io/renv/articles/renv.html) using
`renv::init()`.

## Citation

Please cite the original paper which this compendium accompanies:

> Helmke, Christophe, Vepretskii, Sergei, and Roe, Joe. in prep. Hacia una 
> crítica textual de las fuentes históricas mayas del periodo Clásico [Towards 
> a Textual Criticism of Classic Maya Historical Sources]. Under review for
> *Estudios de Cultura Maya*.

## License

Code: MIT License  
