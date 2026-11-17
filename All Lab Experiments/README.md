# Artificial Intelligence Laboratory Experiments:
https://github.com/Rajibul029/Artificial_Intelligence_Lab

A weekly running log of all Artificial Intelligence Lab Exp.

---

### 📍 Week 1: Introduction to Python Libraries for AI

* **Core Implementations:**
  * **NumPy & Pandas:** Formatted structural databases and calculated essential array metrics (Sum, Mean, Max).
  * **Matplotlib:** Plotted static data visualizations using a Student Marks bar chart layout.
  * **Scikit-Learn:** Preprocessed text data by transforming categorical student strings into numerical digits.
  * **TensorFlow & OpenCV:** Evaluated math matrices and generated basic coordinate shapes on a digital raw canvas.

---

### 📍 Week 2: Graph Traversal Algorithms (BFS & DFS)

* **Core Implementations:**
  * **NetworkX:** Structured a node matrix layout (`add_edges_from`) to map out graph nodes and visual coordinate connections.
  * **Matplotlib:** Rendered dynamic color configurations to map traversed routes and generated interactive animation sequences (`FuncAnimation`).
  * **Breadth-First Search (BFS):** Deployed a FIFO matrix mapping strategy (`queue.popleft()`) to explore layers level-by-layer across connected neighbors.
  * **Depth-First Search (DFS):** Programmed a LIFO structural branch layout (`stack.pop()`) to traverse deep structural vectors before backtracking.

---

### 📍 Week 3: Uniform Cost Search (UCS)

* **Core Implementations:**
  * **NetworkX:** Built a weighted graph using adjacency lists and visualized nodes, edges, and edge weights with a custom layout.
  * **Matplotlib:** Developed an interactive visualization that dynamically updates node colors, explored paths, and cumulative path costs during execution.
  * **Priority Queue (Heap):** Implemented a min-priority queue using Python's heapq to always expand the node with the lowest accumulated path cost.
  * **Uniform Cost Search (UCS):** Designed a cost-based graph traversal algorithm that computes the optimal (minimum-cost) path by maintaining cumulative costs (g(n)) and updating the frontier until the goal node is reached.

---

### 📍 Week 4: A* Search Algorithm

* **Core Implementations:**
  * **NetworkX:** Built a weighted graph with nodes, edges, edge weights, and fixed coordinates to visualize the search space.
  * **Matplotlib:** Created step-by-step graph visualizations to highlight the currently expanded node and the final optimal path.
  * **Priority Queue (Heap):** Used Python's heapq to prioritize nodes based on the lowest evaluation function f(n) = g(n) + h(n).
  * **Heuristic Function:** Assigned heuristic values h(n) to estimate the remaining cost from each node to the goal.
  * **A Search:** Implemented a heuristic-based search algorithm that combines the actual path cost g(n) with the estimated cost h(n) to efficiently find the optimal path from the start node to the goal.

---

### 📍 Week 5: Beam Search Algorithm

* **Core Implementations:**
  * **NetworkX:** Constructed a directed graph with nodes, edges, heuristic values, and fixed coordinates to visualize the search structure.
  * **Matplotlib:** Created a graph visualization with color-coded nodes to distinguish the final path, selected nodes, unselected nodes, and discarded candidates.
  * **Heuristic Evaluation:** Assigned heuristic values h(n) to each node and sorted candidate nodes based on their estimated distance to the goal.
  * **Beam Width:** Implemented a configurable beam width to retain only the best W candidate nodes at each search level, reducing memory and search complexity.
  * **Beam Search:** Developed a heuristic-based search algorithm that explores the most promising nodes level-by-level while discarding less promising candidates to efficiently reach the goal.

---

### 📍 Week 6: AO* Search Algorithm

* **Core Implementations:**
  * **AND-OR Graph:** Represented a problem using an AND-OR graph where OR nodes select the most promising alternative and AND nodes require multiple child nodes to be solved together.
  * **Heuristic Function:** Assigned heuristic values h(n) to estimate the remaining cost from each node to the goal and guide the search toward promising solutions.
  * **Cost Calculation:** Calculated the cost of OR and AND branches to determine the minimum-cost solution. For an OR node, the minimum-cost child is selected, while an AND node combines the costs of all required children.
  * **Backtracking:** Updated the estimated costs of parent nodes after solving their child nodes and propagated the improved values backward through the graph.
  * **AO_star Search:** Implemented a heuristic-driven algorithm that recursively expands the most promising solution graph and continues updating costs until the optimal solution subgraph is identified.
  * **Graph Visualization:** Used NetworkX and Matplotlib to visualize AND/OR relationships, explored nodes, selected solution branches, and the final optimal solution graph.

---

### 📍 Week 7: Logistic Regression

* **Core Implementations:**

  * **Dataset Preparation:** Created a binary classification dataset with feature values X and class labels 0 and 1 for training the Logistic Regression model.
  * **Logistic Regression Model:** Implemented Logistic Regression using Scikit-learn to learn the relationship between the input feature and binary class labels.
  * **Sigmoid Function:** Used the sigmoid function to convert the linear model output z = \beta_0 + \beta_1X into a probability between 0 and 1.
  * **Probability Prediction:** Calculated P(Class 1) and P(Class 0) for a given test input and used these probabilities to determine the predicted class.
  * **Decision Boundary:** Calculated the decision boundary using -\beta_0/\beta_1, where the model probability reaches the classification threshold of 0.5.
  * **Interactive Visualization:** Used Matplotlib and IPyWidgets to dynamically display the training data, sigmoid probability curve, threshold, decision boundary, and test prediction.
  * **User Interaction:** Added controls for loading sample data, adding Class 0/Class 1 points, training the model, resetting the dataset, and changing the test input using a slider.

---

### 📍 Week 8: K-Nearest Neighbors (KNN) Classification

* **Core Implementations:**

  * **Dataset Preparation:** Loaded a user-provided CSV or Excel dataset and cleaned empty rows, columns, and missing values before classification.
  * **Feature Selection:** Used interactive widgets to select two numerical features for 2-D KNN visualization and selected the target classification column.
  * **Target Encoding:** Applied LabelEncoder to convert categorical target classes into numerical labels for model training.
  * **Train-Test Split:** Divided the dataset into training and testing sets using an 80/20 split, with stratification when possible.
  * **Feature Scaling:** Applied StandardScaler to standardize the selected features before calculating distances.
  * **KNN Model:** Implemented KNeighborsClassifier using Euclidean distance and a user-selected value of K.
  * **Distance Calculation:** Calculated Euclidean distances between the test point and training samples to identify the nearest neighbors.

---

### 📍 Week 9: Support Vector Machine (SVM)

* **Core Implementations:**

  * **Iris Dataset:** Loaded the Iris dataset containing four numerical features and three classes: Setosa, Versicolor, and Virginica. 
  * **Train-Test Split:** Divided the dataset into training and testing sets using an 80/20 split with stratification to preserve the class distribution. 
  * **Feature Scaling:** Applied StandardScaler to standardize the training and testing features before SVM classification. 
  * **Linear SVM:** Implemented SVC with a linear kernel and C=1.0 to construct decision boundaries between the Iris classes. 
  * **Hyperplane and Margin:** Used the SVM concept of a decision hyperplane that separates classes while maximizing the margin from the nearest data points, known as support vectors. 
  * **Model Training:** Trained the SVM classifier using the scaled training data and generated predictions for the test dataset. 
  * **Accuracy Evaluation:** Calculated classification accuracy using accuracy_score to evaluate the SVM model’s predictions. 
  * **Data Visualization:** Visualized the Iris classes using Sepal Length vs Sepal Width and Petal Length vs Petal Width scatter plots.

---

### 📍 Week 10: Decision Tree Classification

* **Core Implementations:**

  * **Iris Dataset:** Loaded the Iris dataset containing 150 samples from three classes: Setosa, Versicolor, and Virginica, with four numerical features. 
  * **Train-Test Split:** Divided the dataset into training and testing sets using an 80/20 split with a fixed random state. 
  * **Decision Tree Classifier:** Created a DecisionTreeClassifier to classify Iris flowers based on their feature values. 
  * **Tree Training:** Trained the Decision Tree model using the training dataset and learned feature-based decision rules for classification.
  * **Prediction:** Used the trained model to predict the classes of the test samples. 
  * **Gini Impurity:** Used the Decision Tree splitting concept where Gini impurity measures the quality and class homogeneity of a node. 
  * **Accuracy Evaluation:** Calculated classification accuracy by comparing the predicted classes with the actual test classes. 
  * **Confusion Matrix:** Generated a confusion matrix to compare actual and predicted Iris classes, where diagonal values represent correct predictions and off-diagonal values represent incorrect predictions. 
  * **Decision Tree Visualization:** Visualized the trained tree using feature names, class names, filled nodes, and rounded node boxes to understand the classification decisions. 
  * **Scatter Plot:** Visualized the relationship between Sepal Length and Sepal Width to observe the distribution and separation of the three Iris classes.

---

### 📍 Week 11: Random Forest Classification

* **Core Implementations:**

  * **Iris Dataset:** Loaded the Iris dataset containing 150 samples, four numerical features, and three classes: Setosa, Versicolor, and Virginica.
  * **Train-Test Split:** Divided the dataset into training and testing sets using an 80/20 split with stratification to maintain class distribution.
  * **Random Forest Classifier:** Implemented RandomForestClassifier using 100 decision trees (n_estimators=100) and Gini impurity as the splitting criterion.
  * **Ensemble Learning:** Combined predictions from multiple decision trees to improve classification performance and produce the final predicted class.
  * **Model Training:** Trained the Random Forest model using the training dataset and learned patterns from the input features.
  * **Prediction:** Used the trained model to predict the Iris species of the test samples.
  * **Accuracy Evaluation:** Evaluated model performance using accuracy_score and classification_report, including precision, recall, and F1-score.

---

### 📍 Week 12: Convolutional Neural Network (1D CNN) Classification

* **Core Implementations:**

  * **Iris Dataset:** Loaded the Iris dataset containing 150 samples, four numerical features, and three flower classes: Setosa, Versicolor, and Virginica.
  * **Dataset Preprocessing:** Divided the dataset into training and testing sets using an 80/20 split with stratification to maintain class distribution.
  * **Feature Scaling:** Applied StandardScaler to standardize numerical features and improve model training.
  * **Data Reshaping:** Reshaped the input data into a 3D format (samples, features, channels) to make it compatible with the 1D CNN architecture.
  * **One-Hot Encoding:** Converted target class labels into categorical format using to_categorical() for multiclass classification.
  * **1D CNN Architecture:** Developed a 1D Convolutional Neural Network using Conv1D, BatchNormalization, and ReLU activation layers to extract feature patterns.
  * **Global Average Pooling:** Applied GlobalAveragePooling1D to reduce feature dimensions and extract important feature representations.
  * **Dense Classification Layers:** Used fully connected Dense layers with ReLU activation, Dropout for regularization, and Softmax for multiclass probability prediction.

---

### 📍 Week 13: Convolutional Neural Network (2D CNN) Classification

* **Core Implementations:**

  * **Fashion-MNIST Dataset:** Loaded the Fashion-MNIST dataset containing 70,000 grayscale images of 10 fashion categories, with 60,000 training images and 10,000 testing images.
  * **Image Preprocessing:** Normalized pixel values from 0–255 to 0–1 and reshaped images into a 4D tensor format (samples, height, width, channels) for 2D CNN processing.
  * **One-Hot Encoding:** Converted target class labels into categorical format using to_categorical() for multiclass classification.
  * **Training and Validation Split: Divided the training dataset into training and validation sets using an 85/15 split with stratification.
  * **2D CNN Architecture:** Developed a Convolutional Neural Network using three Conv2D layers with 32, 64, and 128 filters to extract spatial features from fashion images.
  * **Batch Normalization and Max Pooling:** Applied BatchNormalization, ReLU activation, and MaxPooling2D to improve training stability and reduce feature dimensions.
  * **Global Pooling Feature Fusion:** Combined GlobalMaxPooling2D and GlobalAveragePooling2D to capture important spatial feature representations.
  * **Dense Classification Layers:** Used fully connected Dense layers with ReLU activation, Dropout for regularization, and Softmax for predicting probabilities across 10 fashion categories.

---

### 📍 Week 14: Time Series Analysis and Forecasting

* **Core Implementations:**

  * **Dataset Creation:** Generated a sample monthly sales dataset containing 60 observations from January 2020 using trend, seasonality, and random noise.
  * **Time Series Visualization:** Plotted monthly sales data to understand its overall pattern and variations over time.
  * **Moving Average:** Applied a 3-month rolling average to smooth fluctuations and identify underlying trends.
  * **Time Series Decomposition:** Used seasonal_decompose() with an additive model and period 12 to separate the series into trend, seasonal, and residual components.
  * **Stationarity Testing**: Applied the Augmented Dickey-Fuller (ADF) test to check whether the time series is stationary using its p-value.
  * **First Order Differencing:** Used .diff() to calculate differences between consecutive observations and reduce non-stationarity.
  * **ADF Test After Differencing:** Repeated the ADF test on differenced data to check whether stationarity improved.
  * **ACF Plot:** Used the Autocorrelation Function to identify correlations between observations and their previous time steps.

---

### 📍 Week 15: [Coming Soon - Every Thursday]

* **Core Implementations:**
  * [Coming Soon]
  * [Coming Soon]

