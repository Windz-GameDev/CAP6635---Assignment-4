# Classification Model Comparison

## Overview

This project involves building and comparing different classification models using the Wine and Iris datasets. The goal is to evaluate the performance of three classification algorithms—Decision Tree, Naive Bayes, and SVM—using metrics such as accuracy, precision, and recall.

## Datasets

The datasets used in this project are:

1. **Wine Dataset**: [Wine Data Set](http://archive.ics.uci.edu/ml/datasets/Wine)
2. **Iris Dataset**: [Iris Data Set](https://archive.ics.uci.edu/dataset/53/iris)

## Methods

The classification models were evaluated using the following validation method:

- **10-fold Cross Validation**: This method was chosen to ensure that each instance of the dataset had the chance to be used as both training and test data.

## Algorithms

The following algorithms were tested:

- **Decision Tree**
- **Naive Bayes**
- **SVM (Support Vector Machine)**

## Software and Tools

The analysis was conducted using Python in a Jupyter Notebook environment. Libraries used include:

- `scikit-learn` for building and evaluating models
- `matplotlib` and `numpy` for data visualization and numerical operations

## Results

The results include the average prediction accuracy, standard deviation, precision, and recall for each classification technique. Plots are provided to show which algorithm performed the best/worst in terms of accuracy, precision, and recall metrics.

## Running the Notebook

To run this notebook:

1. Ensure that Python and Jupyter Notebook are installed on your machine.
2. Install the required libraries using pip (Alternatively, use Anaconda):

```
pip install numpy matplotlib scikit-learn
```

3. Clone this repository:

```
git clone <repository-url>
```

4. Navigate to the directory containing the notebook and start Jupyter Notebook:

```
jupyter notebook
```

5. Open the `Classification_Model_Comparison.ipynb` notebook and run the cells sequentially.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
