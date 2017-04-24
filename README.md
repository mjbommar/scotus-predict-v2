# A General Approach for Predicting the Behavior of the Supreme Court of the United States
==================
  * __N.B.__: This version supercedes the prior pre-print of the paper, which can be found at [mjbommar/scotus-predict](https://github.com/mjbommar/scotus-predict/).
  *  __Title__: A general approach for predicting the behavior of the Supreme Court of the United States
  *  __Authors__: [Daniel Martin Katz](http://www.law.msu.edu/faculty_staff/profile.php?prof=780), [Michael J Bommarito II](http://bommaritollc.com/), [Josh Blackman](http://joshblackman.com)
  * __Publication URL__: [PLOS One](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0174698)
  * __Publication Cite__: Katz DM, Bommarito MJ II, Blackman J (2017) A general approach for predicting the behavior of the Supreme Court of the United States. PLoS ONE 12(4): e0174698. https://doi.org/10.1371/journal.pone.0174698
  *  __Paper URL__: [http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2463244](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2463244)
  *  __Blog URL__: [http://lexpredict.com/portfolio/predicting-the-supreme-court/](http://lexpredict.com/portfolio/predicting-the-supreme-court/)

## Paper Abstract
Building on developments in machine learning and prior work in the science of judicial prediction, we construct a model designed to predict the behavior of the Supreme Court of the United States in a generalized, out-of-sample context.  Our model leverages the random forest method together with unique feature engineering to predict nearly two centuries of historical decisions (1816-2014). Using only data available prior to decision, our model outperforms null (baseline) models at both the justice and case level under both parametric and non-parametric tests.  Over nearly two centuries, we achieve 70.2\% accuracy at the case outcome level and 71.9% at the justice vote level. More recently, over the past century, we outperform a high quality null model by nearly 5%.  Our performance is consistent with, but improves upon, the general level of prediction demonstrated by prior work;  however, our model is distinctive because it can be applied out-of-sample to the entire past and future of the Court, not just one year.  Our results represent an  advance for the science of quantitative legal prediction and portend a range of other potential applications. 

## Source Description
The source and data in this repository allow for the reproduction of the results in this paper.  

## Source Highlights

  * Model run used for publication figures: https://github.com/mjbommar/scotus-predict-v2/blob/master/src/model_growing_random_forest_cv_5.ipynb
  * "Always guess reverse" model: https://github.com/mjbommar/scotus-predict-v2/blob/master/src/baseline_model_always_reverse.ipynb
  * Sample alternative model run: https://github.com/mjbommar/scotus-predict-v2/blob/master/src/model_growing_random_forest_1.ipynb
  * Disposition coding map: https://github.com/mjbommar/scotus-predict-v2/blob/master/src/legacy_model.py#L73
  * Publication figures: https://github.com/mjbommar/scotus-predict-v2/blob/master/src/publication_figures.ipynb
  
## Data Description
The data used in this paper is available from the [Supreme Court Database (SCDB)](http://scdb.wustl.edu/); both the Modern and Legacy databases were used in this analysis.

## Version
The latest version of this model was released in December 2016.
