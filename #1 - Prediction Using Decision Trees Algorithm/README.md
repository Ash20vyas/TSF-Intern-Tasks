<h1 align="center">Task 1 : Prediction Using Decision Trees Algorithm</h1>

<h2>Problem Statement</h2>

 ● Create the Decision Tree classifier and visualize it graphically.
 
<div id="about_dataset">
    <h2>About the dataset</h2>
    The Iris dataset was used in R.A. Fisher's classic 1936 paper, <b>The Use of Multiple Measurements in Taxonomic Problems</b>, and can also be found on the <a href="https://archive.ics.uci.edu/ml/datasets/iris">UCI Machine Learning Repository</a>.
    <br>
    <br>
    This is perhaps the best known database to be found in the pattern recognition literature. The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other.
    <br>
    <br>
    Our job is to build a classifier model such that if we feed any new data to this classifier, it would be able to predict the right class accordingly.
    <br>
    <br>
    This is a multiclass classifier, where we used the training part of the dataset to build a decision tree, and then used it to predict the class of testing part of the dataset.
</div>
 
<h2>Libraries Used</h2>
<ul>
 <li>numpy (as np)</li>
 <li>pandas</li>
 <li>DecisionTreeClassifier <i>from</i> sklearn.tree</li>
 <li>train_test_split <i>from</i> sklearn.model_selection</li>
 <li>metrics <i>from</i> sklearn</li>
 <li>classification_report <i>from</i> sklearn.metrics</li>
 <li>StringIO <i>from</i> io</li>
 <li>pydotplus</li>
 <li>Image <i>from</i> IPython.display</li>
 <li>export_graphviz <i>from</i> sklearn.tree</li>
</ul>

<h2>Decision Tree Visualization</h2>
<p align="center">
<img src="https://github.com/Ash20vyas/TSF-Intern-Tasks/blob/main/%231%20-%20Prediction%20Using%20Decision%20Trees%20Algorithm/speciesTree.png">
  </p>
