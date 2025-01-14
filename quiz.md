1.  Which of the following features best representing the advantage of
    using `initial_split()` over general `sample()` function? Is there
    any crucial features that are not provided by base R functions?
    - [ ] Neat tidy format
    - [ ] Optional stratified argument through `strata`
    - [ ] More simple workflow
2.  Suppose we are going to do some data preprocess steps, and some of
    them need information from the dataset--like mean, standard
    deviation, min-max, etc--which of the following dataset should we
    use if we are going to do train-and-testing a model?
    - [ ] Full dataset
    - [ ] Train dataset
    - [ ] Test dataset
3.  If we want to do hyperparameter tuning, say, for the `mtry`,
    `trees`, and `min_n` of a random forest model, what approach should
    we take to pick a combination of number if we prefer a controlled
    grid search?
    - [ ] Randomized number
    - [ ] Minimum and Maximum extreme values
4.  If we want to search a probability threshold to balancing the value
    of recall and precision, which of the functions below is
    appropriate?
    - [ ] `pr_curve()`
    - [ ] `roc_curve()`
    - [ ] `roc_auc_vec()`
5.  Say, we are building a model, and already did repeated k-folds with
    5 folds and 3 repeat. Consider every experiments (a combination of
    parameters) going through the specified repeated k-folds and we
    already calculated a specified metrics, which of the following
    approach are better to choose the best model?
    - [ ] Use a model which has highest (or lowest) mean of the
        specified accuracy (or error) metrics in all experiment
    - [ ] Use a model which has lowest standard deviation of the
        specified accuracy/error metrics in all experiment
    - [ ] Use a model which has highest (or lowest) mean and lowest
        standard deviation of the specified accuracy (or error) metrics
        in all experiment
