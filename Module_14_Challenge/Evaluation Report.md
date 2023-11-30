# Evaluation Report

### Baseline Algorithm:3 month

<p align="center">
  <img src="../Images/baseline_model_3m.png"/>
</p>

<p align="center">
  <img src="../Images/baseline_model_3m_plot.png"/>
</p>

`Baseline model has an accuracy score of 55% and a high recall score (96%) when buying but a low recall score (4%) when selling. This mean the model performs extremely well when enter a position.`

### Baseline Algorithm:6 month

<p align="center">
  <img src="../Images/baseline_model_6m_step_1.png"/>
</p>

<p align="center">
  <img src="../Images/baseline_model_6m_plot_step_1.png"/>
</p>

`Change size data to increasing the training window to 6 months and hass impact the results.`

* Increase to 6 month and not much impact
* Only little movement during 2019-2020 compared with 3 month one
* Accuracy score increase from 0.55 to 0.56

### Baseline Algorithm:6 month short 8 long 40

<p align="center">
  <img src="../Images/baseline_model_s8l40_step_2.png"/>
</p>

<p align="center">
  <img src="../Images/baseline_model_s8l40_plot_step_2.png"/>
</p>

`Change input to increasing the short window to 8 and decreasing the long window to 40 months and impacted the results.`

* Increase to short 8 and long window to 40 and has a bit results impact
* Strategy returns and actual returns has more distance from 2019
* Accuracy score decrease from 0.56 to 0.54

### LogisticRegression:

<p align="center">
  <img src="../Images/LogisticRegression.png"/>
</p>

<p align="center">
  <img src="../Images/LogisticRegression_plot.png"/>
</p>

`The baseline model performed slightly better than LogisticRegression, when determining when to enter (buy) a postion.`

* The LogisticRegression has 66% recall score for the buying target which is not good for the best entry positions.
* We should focus on getting a higher recall score for the buying target because the model we use is to make less mistakes when make decision to enter a position.