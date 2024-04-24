## 1. Based on your experience, how would you define ANN and CNN?
Artificial Neural Network (ANN):
ANNs are like a simplified version of the human brain's network. They consist of layers of nodes, or "neurons," connected together. These networks are flexible and can be used for different tasks like recognizing patterns or sorting data into categories. We found ANNs useful for general problems where the data doesn’t have a specific arrangement or pattern.

Convolutional Neural Network (CNN):
CNNs are designed to process data that has a clear arrangement, like images. They work by moving filters over the data to capture patterns such as edges or shapes, which helps in tasks like identifying objects in pictures. Through our tests, CNNs proved to be better for visual data because they focus on the spatial relationships within the data.

Our experiments showed that while both networks can tackle similar challenges, the choice between using an ANN or a CNN often depends on the type of data and what the task involves.

## 2. Which hyper-parameters of the CNN architecture have you fine-tuned?
- Batch Size
- Number of Epochs

we could also have used learning rate

## 3. Which is the role of the activation functions in ANN? Which of them you have implemented?
Illustrate them.



## 4. Can you see any advantages and disadvantages of ANN and CNN used for classification in comparison to the other classification algorithms you are familiar with? Give some examples.
Artificial Neural Networks (ANNs) and Convolutional Neural Networks (CNNs) are powerful for handling complex classification tasks due to their ability to model nonlinear relationships and process large datasets effectively. These networks are particularly adept at identifying intricate patterns in data, which can be crucial in fields such as image and video recognition where CNNs, for example, automatically extract and learn the most relevant features without manual feature engineering.

However, these strengths come with certain drawbacks. Both ANNs and CNNs are computationally intensive, requiring significant resources for training, especially as the network's complexity increases. This can be a limiting factor for smaller projects or organizations with limited computational capacity. Additionally, there is a heightened risk of overfitting with these networks, particularly if the available training data is not sufficiently diverse or extensive. They also require large amounts of labeled data to train effectively, which can be a substantial hurdle compared to more lightweight or unsupervised learning algorithms.

Compared to other classification algorithms like Decision Trees, Support Vector Machines (SVM), and Naive Bayes, ANNs and CNNs generally offer superior capability in handling high-dimensional data and learning from complex datasets. Decision Trees are easier to understand and visualize but tend to overfit and do not perform well on very complex classification tasks. SVMs are robust to high-dimensional spaces and can manage nonlinear relationships with the appropriate kernel, but they may require careful tuning of parameters and kernel selection. Naive Bayes classifiers are extremely efficient and perform well with a smaller amount of data, but their assumption of feature independence often doesn't hold true in real-world data, limiting their effectiveness.
