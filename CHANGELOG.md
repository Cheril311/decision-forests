# Changelog

## 0.1.6 - ????

### Features

-   Add hyper-parameter `sorting_strategy` to disable the computation of the
    pre-sorted index (slower to train, but consumes less memory).

## 0.1.5 - 2021-05-26

### Features

- Raise an error of the number of classes is greater than 100 (can be disabled).
- Raise an error if the model's task does not match the `pd_dataframe_to_tf_dataset`'s task.

### Bug fix

- Fix failure when input feature contains commas.

## 0.1.4 - 2021-05-21

### Features

-   Stop the training when interrupting a colab cell / typing ctrl-c.
-   `model.fit` support training callbacks and a validation dataset.

### Bug fix

-   Fix failure when there are not input features.

## 0.1.3 - 2021-05-19

### Features

-   Register new inference engines.

## 0.1.2 - 2021-05-18

### Features

-   Inference engines: QuickScorer Extended and Pred

## 0.1.1 - 2021-05-17

### Features

-   Migration to TensorFlow 2.5.0.
-   By default, use a pre-compiled version of the OP wrappers.

### Bug fix

-   Add missing `plotter.js` from Pip package.
-   Use GitHub version of Yggdrasil Decision Forests by default.

## 0.1.0 - 2021-05-11

Initial Release of TensorFlow Decision Forests.

### Features

-   Random Forest learner.
-   Gradient Boosted Tree learner.
-   CART learner.
-   Model inspector: Inspect the internal model structure.
-   Model plotter: Plot decision trees.
-   Model builder: Create model "by hand".
