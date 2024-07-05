### **Iris Classification using Neural Network**

**Introduction**

The Iris dataset is a well-known dataset in the field of machine learning and statistics. It contains 150 samples of iris flowers, with 50 samples each from three species: Iris-setosa, Iris-versicolor, and Iris-virginica. Each sample has four features: Sepal Length, Sepal Width, Petal Length, and Petal Width. The goal is to classify the species of the iris flower based on these features. In this project, we used a neural network implemented in PyTorch to classify the iris species.

Data Preparation

The dataset was loaded using Pandas and visualized using Matplotlib and Seaborn. The species column was converted from categorical to numerical values (0, 1, and 2) for Iris-setosa, Iris-versicolor, and Iris-virginica respectively.

**Data Visualization**

Visualized the Sepal Length for each species to get a sense of the distribution.

![Screenshot 2024-07-06 010605](https://github.com/KanchanaWijesooriya/Machine-Learning-Classification-and-Regression/assets/160541254/c992bf44-db6a-4449-a530-7d61fc9b83f8)

**Model Definition**

We defined a neural network model with two hidden layers. The input layer has four neurons (one for each feature), the first hidden layer has eight neurons, the second hidden layer has seven neurons, and the output layer has three neurons (one for each species).

**Training the Model**

The model was trained using the Adam optimizer and ‘CrossEntropyLoss’ as the loss function. The dataset was split into training and test sets. We trained the model for 100 epochs and recorded the training and validation losses.

![Screenshot 2024-07-06 010548](https://github.com/KanchanaWijesooriya/Machine-Learning-Classification-and-Regression/assets/160541254/47da71a6-1d56-484a-96fc-6cc7b09bbf6f)

**Results**

The training and validation losses decreased consistently over the epochs, indicating that the model was learning well. We achieved 100% accuracy on the test set.

**Evaluation Metrics**

We evaluated the model's performance using precision, recall, and F1 score, all of which were perfect.

**Conclusion**

The neural network model successfully classified the Iris dataset with high accuracy. The loss curves indicated proper learning, and the evaluation metrics confirmed the model's effectiveness. This project demonstrates the power of neural networks for classification tasks and the importance of proper data preprocessing and visualization.

**Future Work**

Further improvements can be made by experimenting with different network architectures, regularization techniques, and hyperparameter tuning. Additionally, implementing cross-validation can provide a more robust evaluation of the model's performance.
