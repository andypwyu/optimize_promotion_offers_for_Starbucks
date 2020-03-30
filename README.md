# optimize_promotion_offers_for_Starbucks
DSND Term 2 Portfolio Exercise: Optimize promotion offers for Starbucks

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#description)
4. [Acknowledgements](#acknowledgement)
5. [Result](#result)


### Installation <a name="installation"></a>

The code should run with no issues using Python versions 3.*. If you use Anaconda, please make sure install below libraries:

1. imblearn.over_sampling
2. xgboost
3. seaborn


### Project Motivation<a name="motivation"></a>
This portfolio exercise was originally used as a take-home assignment provided by Starbucks for their job candidates. This exercise is to leverage Uplift Model to optimize promotion strategy, considering whether customers purchase a specific product priced at $10 and it costs the company 0.15 to send out each promotion. Ideally, we aim to limit the offers to those receptive to the promotion.

Our promotion strategy will be evaluated on 2 key metrics

1. Incremental Response Rate (IRR)
2. Net Incremental Revenue (NIR)

### File Descriptions<a name="description"></a>
1. **Starbucks.ipynb** - Uplift Modeling
2. **test_results.py** - Strategy performance evaluation 


### Acknowledgements<a name="acknowledgement"></a>
Credit to **Starbucks** and **Udacity** for the data.


### Result <a name="result"></a>
Model performance: 
* **IRR = 0.0205**
* **NIR = 216.75**

The performance is better than the Starbucks baseline model with an **IRR of 0.0188** and a **NIR of 189.45** on the test set.
