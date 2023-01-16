# BST270-Project

## Dominic DiSanto
## January Session 2023

Individual project for BST270: Reproducible Data Science


# Articles & Background


Articles:
- https://fivethirtyeight.com/features/why-some-tennis-matches-take-forever/ by Carl Bialik
- https://fivethirtyeight.com/features/we-watched-906-foul-balls-to-find-out-where-the-most-dangerous-ones-land/ by Annette Choi

I selected two articles from 538. I initially selected Carl Bialik's article to recreate, but only the data files to recreate Bialik's tables are available (i.e. I could not access data to re-create his figures). I selected an additional, brief article (Choi) with figures to include at least one table and one figure in my submission.

To the best of my ability, I attempt to match the formatting of the tables/figures generated in each article. However the primary focus is on data/result consistency and general structural similarities (mostly due to stylistic limitations in table/figure formatting, specifically using LaTeX/PDF-generation within R).


# Code & Results

Tables and figures were recreated using R, and a PDF output notebook generated using Quarto, all within RStudio. The output notebook is available in the [Code](/Code/) section of the repository as a PDF, which includes an Appendix of the code used for table/figure generation. The RMD file used to generate the notebook is also available as a standalone file in the [Code](/Code/) folder as well. 


# Data & Figures

(Limited) data from Bialik's article are available on GitHub at https://github.com/fivethirtyeight/data/tree/master/tennis-time. The `events.csv` and `players.csv` files were used as noted in the analytic code for each respective, re-created table.

Data from Annette Choi's article can be found at https://github.com/fivethirtyeight/data/tree/master/foul-balls. The `foul-balls.csv` file was used to re-create the article's second figure.

Neither article or analysis required data files that contain sensitive information, so I have also stored all data within my own repository under `Data` in project specific folders `tennis-times` and `foul-balls` respectively.
