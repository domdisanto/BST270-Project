# BST270-Project

## Dominic DiSanto
## January Session 2023

Individual project for BST270: Reproducible Data Science

Final submission PDF can be accessed via GitHub at [Code/BST270_IndProject_DiSanto.pdf](/Code/BST270_IndProject_DiSanto.pdf) or downloaded directly by [clicking this link](https://github.com/domdisanto/BST270-Project/raw/main/Code/BST270_IndProject_DiSanto.pdf).

Note for the code to execute properly (and re-create the initial results notebook), both the Data and Images folder must be downloaded (with further detail provided in the Code & Results section of this ReadMe). 

# Articles & Background


Articles:
- https://fivethirtyeight.com/features/why-some-tennis-matches-take-forever/ by Carl Bialik
- https://fivethirtyeight.com/features/we-watched-906-foul-balls-to-find-out-where-the-most-dangerous-ones-land/ by Annette Choi

I selected two articles from 538. I initially selected Carl Bialik's article to recreate, but only the data files to recreate Bialik's tables are available (i.e. I could not access data to re-create his figures). I selected an additional, brief article (Choi) with figures to include at least one table and one figure in my submission.

To the best of my ability, I attempt to match the formatting of the tables/figures generated in each article. However the primary focus is on data/result consistency and general structural similarities (mostly due to stylistic limitations in table/figure formatting, specifically using LaTeX/PDF-generation within R).


# Code & Results

Tables and figures were recreated using R, and a PDF output notebook generated using Quarto, all within RStudio. It is necessary to download and set-up Quarto within RStudio ([with useful documentation located on Quarto's website](https://quarto.org/docs/get-started/)).

If Quarto is not installed, saving the file as an RMarkdown file (with extension `.rmd` rather than `.qmd`) should also allow the file to knit to PDF. This has been successfully tested locally (again within RStudio, using the `knitr` package).

The output notebook is available in the [Code](/Code/) section of the repository as a PDF, which includes an Appendix of the code used for table/figure generation. The RMD file used to generate the notebook is also available as a standalone file in the [Code](/Code/) folder as well.

The notebook includes a brief critique/commentary on each article's reproducibility as well, in a Summary section for each respective article.

To ensure data and code can run seamlessly, you should  follow the file structure of this repository, notably including the Data and Images folders.

```
.
|
- Data
  |-- foul-balls
  |-- tennis-time
- Images
  |-- foul-balls
  |-- tennis-time
- Code
```

Detailed information concerning versions of R, Rstudio, and relevant packages are included in Appendix of the knitted PDF document.


# Data & Figures

(Limited) data from Bialik's article are available on GitHub at https://github.com/fivethirtyeight/data/tree/master/tennis-time. The `events.csv` and `players.csv` files were used as noted in the analytic code for each respective, re-created table.

Data from Annette Choi's article can be found at https://github.com/fivethirtyeight/data/tree/master/foul-balls. The `foul-balls.csv` file was used to re-create the article's second figure.

Neither article or analysis required data files that contain sensitive information, so I have also stored all data within my own repository under `Data` in project specific folders `tennis-times` and `foul-balls` respectively. These folders include the respective `README` documentation for each article's data source.
