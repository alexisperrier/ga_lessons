<!-- Bias Variance -->
<section  data-background-color="#22c8c6">
    <h1>Bias - Variance</h1>
    <p class = 'big_title'>Bias - Variance</p>
    <p>The bias–variance tradeoff is a central problem in supervised learning.</p>
</section>

<section data-markdown>
# Bias - Variance
### General problem

* Prediction Task: regression, classification
* Dataset: split between train and test (unseen data)
* Model: trained on the train data

You want that model to
1. get good predictions on the train data, be well trained
2. generalize to the unseen data with good performance.


Ideally, one wants to choose a model that both accurately captures the regularities in its training data, but also generalizes well to unseen data.

For that you need the model to minize to distinct types of error: Bias and Variance
</section>

<section data-markdown>
# Bias - Variance

### Bias
* Error due to bias is calculated at the difference between the expected prediction of our model and the correct value we are trying to predict.

* Imagine creating multiple models on various datasets.
Bias measures how far off in general models’ predictions are from the correct value.

</section>

<section data-markdown>
# Bias - Variance

### Variance
* Error due to variance is taken as the variability of a model prediction for a given point.

* Imagine creating multiple models on various datasets.
The variance is how much the predictions for a given point vary between different realizations of the model.

</section>

<section data-markdown>
# Bias Variance

Over fitting: performs highly on training dataset but poorly on new data \\( \Leftrightarrow \\) High variance

Underfitting: Your model performs poorly on training and unseen data \\( \Leftrightarrow \\) High Bias
</section>


<section data-markdown>
# Knowledge Check
</section>
