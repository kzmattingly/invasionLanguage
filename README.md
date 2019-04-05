# invasionLanguage

## This repository includes R scripts and data files associated with Mattingly et al.'s analysis of language use in the invasion biology literature.

### `Extract word frequencies.Rmd` - script to parse text files to calculate frequency of a given word. As an example, loops through `Text files` for frequency of "invasive"
### `Text files` folder - text files for all 202 papers included in Mattingly et al. analysis
### `GallardoEffectSizes.csv` - Gallardo et al. (2016) data on 150 papers, including effect sizes and additional variables collected for Mattingly et al.
### `newdata.csv` - update of Gallardo et al. by Mattingly et al., extracted effect sizes and other variables for 52 papers
### Coming soon: `Effect size aggregation.Rmd` - script for aggregating multiple effect sizes for the same focal species from a single paper 
###  `mattinglyetal_data.csv` - merged data for all 202 papers, with aggregated effect sizes
### `mattinglyetal_data_permanova.csv` - abbreviated version of data file with only one row per paper, to be used in PERMANOVA calculations.
### `Word frequency ordination.Rmd` - script to perform ordination of multiple word frequency values across papers and example of PERMANOVA.
### Coming soon: `Regression trees.Rmd` - script for calculating regression trees that predict word use based on predictors (including effect size and contextual factors) 
### Coming soon: `Non-resampled random forests.Rmd` - script for calculating random forests that predict word use based on predictors 
### Coming soon: `Resampled random forests.Rmd` - script for iteratively calculating random forests resampled to even out an imbalanced factor, to give confidence intervals around importance values
### `RF runs` folder - csv file outputs from regular and resampled random forest runs
### Coming soon: Shiny app for data exploration