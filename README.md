# IR-Document-Clustering-using-K-Means-Algorithm
Perform document clustering using the K-Means algorithm on a subset of the NewsGroup20 dataset, evaluating the results based on Purity. Implement feature selection approaches and utilize Word2Vec embedding for enhanced clustering.

**Dataset**
The dataset for this assignment is a subset of the NewsGroup20 dataset. It consists of 50 documents categorized into 5 different classes. The ground truth information of all clusters is provided for evaluation purposes.

**Feature Selection for Clustering**
Two baseline approaches are recommended for feature selection:

Baseline-I: Use all term frequency (TF) based features with a filtering criterion, such as TF scores for selected terms.
Baseline-II: Enhance the baseline by incorporating TF-IDF feature selection. Use TF-based features with filtering criteria based on both TF scores and document frequency (DF).
Additionally, Word2Vec embedding of selected TF can be used as a semantic feature for clustering. The evaluation of clustering results should be based on purity.

**Implementation and Tools**
You can choose to implement the assignment in Java, Python, C/C++, or C#. For the K-Means algorithm, you can utilize the implementation provided by the SKLearn library in your preferred programming language.

The project code and relevant files should be organized and shared on GitHub.

**Assignment Evaluation**
The evaluation of your assignment will be based on the following criteria:

**Correct implementation of the K-Means algorithm for document clustering.**

Proper feature selection using the specified baseline approaches and Word2Vec embedding.
Accurate evaluation of clustering results using the purity measure.
Well-structured and documented code.
