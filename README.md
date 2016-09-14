# radiohead-sales-analysis
Probabilistic analysis of sales of Radiohead's album, The Bends. Project for UPenn STAT 476 - Probability Models.

In this project, 1995-1996 sales and airplay data for Radiohead's The Bends was provided for analysis. The aim was to build a strong model for fitting sales. Further covariates were obtained and constructed, including Radiohead’s tours with R.E.M., releases of the singles “Fake Plastic Trees,” “Just,” and “Street Spirit,” and the effects of the holiday season/Christmas, in order to improve the analysis.
Nine models were built and evaluated, including exponential-gamma (or Pareto Type II), Weibull, and Weibull-gamma regressions as well as latent class models. Each model was evaluated on BIC and MAPE, as well as on the interpretability of the model parameters. The final model selected was the exponential-gamma, which featured the lowest BIC and 3rd lowest MAPE (Mean Average Percent Error) of the group, while being the most parsimonious. However, a close runner-up was the 3-class Weibull-gamma model, which featured a sizable improvement in MAPE.

| Model  | Log Likelihood | BIC | R^2 | MAPE |
| ------ | -------- | --- | --- | ---- |
| Exponential-gamma  | -1845.28  | 3741.93 | 0.86 | 17.03% |
| 3-class Weibull-gamma  | -1844.06 | 3775.05 | 0.88 | 15.58% |

Finally, two applications of the models were demonstrated. First, by examining model parameters, a strong argument could be made that the peculiar sales pattern was in part due to lack of product awareness. Secondly, the model was able to estimate the sales impact of covariates such as particular singles releases. Both highlight the immense practicality and effectiveness of this approach to modeling timing data.

Full report included.
