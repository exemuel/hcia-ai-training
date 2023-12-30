# Articial Intelligence Overview

Which of the following are Huawei's full-stack all-scenario AI solutions?
✅ ModelArts
✅ MindSpore
✅ Atlas 800 servers
✅ ModelZoo

Which of the following statements about the three major schools of AI are true?
✅ Symbolicism puts more focus on logical inference. connectionism is relatively weak in terms of being logical and interpretability. Instead, it focuses on results.
✅ Connectionism stems from the study of bionics, especially human brain models.
✅ Actionism puts mode focuc on practive. It believes in constantly adapting actions by learning from the environment.
🔲 Symbolicism puts more focus on practive. It believes in constantly adapting actions by learning from the environment.

ModelArts is one-stop development platform for AI developers. With large-volume data preprocessing, semi-automated data labeling, distributed training, automated model building, and on-demand model deployment across the device, edge, and cloud, ModelArts helps AI developers quickly build and deploy models and efficiently manage the AI development lifecycle.
✅ Right
🔲 Wrong


# Machine Learning Overview

Dirty data refers to data with quality problems. Which of the following statements is false about the data quality?
🔲 Noise: Data contains incorrect records or exceptions.
🔲 Incompleteness: Data lacks attributes or contains some missing values.
✅ Unprocessed: Data for which feature engineering has not been performed.
🔲 Inconsistency: Data contains conflicting records.

Compared with the random forest algorithm, which of the following is false about the GBDT algorithm?
✅ Training uses the GBDT algoritm is faster than that of the random forest algorithm (under the same dataset and tree quantity).
🔲 The GBDT algorithm is easier to overfit than the random forest algorithm.
🔲 The random forest algorithm tends to reduce the variance, while the GBDT algorithm tends to reduce the bias.
🔲 Both the GBDT and random forest algorithms can use the CART as the basic tree model.

Which of the following is not a hyperparameter for model training?
🔲 `batch_size` in a training neural network
🔲 `k` in K-means
✅ `b` in one-dimensional linear regression model $Y=wX+b$
🔲 Number of trees in a random forest

In actual data processing, there are multiple trained models available so that you can choose the optimal one.
✅ Right
🔲 Wrong

Typucally, a larger `k` value in the K-Nearest Neighbors (KNN) algorithm reduces the impact of noise on classification, but makes the boundary between classes less obvious.
✅ Right
🔲 Wrong

Linear regression using a loss function with the L...-Norm regular term is also called ridge regression.
2


# Deep Learning Overview

Which of the following statements is true about optimizers?
🔲 The RMSprop optimizer inherits the advantages of the Adam optimizer. The learning rate is automatically updated.
🔲 Unlike the RMSprop optimizer, the Adagrad optimizer does not automatically update the learning rate.
✅ The SGD and momentum optimizers use the same learning rate for each iteration.
🔲 The learning rate of the momentum optimizer does not need to be manually set.

The ReLu function is often used in deep learning and neural networks. Which of the following statements is true about this function?
🔲 The value range is `[-1,1]`.
✅ The value range is `[0,+∞]`.
🔲 The value range of the derivatives is `[0,1]`.
🔲 The value range of the derivatives is `[-1,0]`.

Which of the following statements are false about the functions of the pooling layers?
✅ They reduce the receptive field.
🔲 Max pooling achieves invariance to some extent.
✅ Pooling reduces the size of the input data at the next layer and the number of parameters, but increases the computation amount.
🔲 Pooling helps prevent overfitting.

Which of the following are used for backpropagation?
🔲 Number of network layers
✅ Activation functions
🔲 Number of neurons at a single layer
✅ Neuron weight

Which of the following statements are true about common activation functions in deep learning?
🔲 The sigmoid function is monotonic, continuous, and easy to derive. Its output is bounded, making the network converge better.
🔲 The sigmoid function can easily cause the gradient to explode.
✅ The tanh function is symmetric with respect to the origin, and the mean of its output is closer to 0.
✅ During training of a deep neural network, the sigmoid, tanh, and softsign functions cannot prevent the vanishing gradient problem.

If a 32 x 32 image (without padding) is input and a 5 x 5 kernel is used for convolution with a step of 2, the size of the output image is 13 x 13.
🔲 Right
✅ Wrong

Assuming the number of hyperparameters is the same, stochastic gradient descent (SGD) combined with manual adjustment achieves a better effect than adaptive learning rates.
🔲 Right
✅ Wrong

Convolutional neural networks cannot be used to process text data.
🔲 Right
✅ Wrong

The softmax function turns a vector of `K` real numbers into another vector of `K` real numbers, where the value of each vector element is within the range of `(0,1)`, and the sum of element values is within the range of `(1,100)`.
🔲 Right
✅ Wrong

At a convolution layer, there are 256 5 x 5 convolution kernels, the size of an input feature map is 32 x 32 x 5, the convolution step is 2, and zero padding is employed (padding size = 1). So, the size of the output feature map is .... x .... x ....
15 x 15 x 256


# AI Development Framework

Which of the following statements about the running process of the MindArmour subsystem is false?
🔲 Configuration policies: Define test policies based on threat vectors and trustworthiness certification requirements and select appropriate test data generation methods.
✅ Fuzzing execution: Generate trusted test data randomly based on the model coverage and configuration policies.
🔲 Evaluation report: Generate an evaluation report based on built-in or user-defined trustworthiness metrics.
🔲 Trustworthiness enhancement: Use preset methods to enhance the trustworthiness of AI models.

The MindInsight subsystem of MindSpore discovers model lineage and compares training results through the collected information about training hyperparametes, datasets, and data augmentation.
✅ Right
🔲 Wrong

MindSpore can be quickly deployed on the cloud, edge, and mobile phone, improving resource utilization and privacy protection and enabling developers to focus on developing AI apps.
✅ Right
🔲 Wrong

Tensor `[[[2,3]]]` is a/an ....-dimensional tensor.
3


# Introduction to Huawei AI Platform

In Huawei Cloud EI, which of the following is a one-stop AI development platform that supports large-volume data preprocessing, semi-automated data labeling, distributed training, automated model building, and on-demand model deployment across the device, edge, and cloud for machine learning and deep learning, and helps AI developers quickly build and deploy models and efficiently managage the AI development lifecycle?
✅ ModelArts
🔲 MindSpore
🔲 MySQL
🔲 Ascend

Which of the following statements about the Da Vinci architecture is incorrect?
✅ A compute unit contains four types of basic compute resources.
🔲 Control units are responsible for the running of AI Cores.
🔲 The storage system consists of on-chip storage units of AI Core and corresponding data paths.
🔲 Transfers data to the L1 buffer through the bus interface unit.

As the cornerstone of Huawei's full-stack, all-scenario AI sulution, Atlas provides modules, boards, and servers powered by the Ascend AI processor to meet customer demand for computing power in all scenarios.
✅ Right
🔲 Wrong


# Cutting-edge AI Applications

Which of the following scenarios can Knowledge Graph can be used?
✅ Search engine
✅ Product keyword search
✅ Q&A bot

The Shor algorithm can efficiently perform integer factorization, which is much faster than the classical algorithm.
✅ Right
🔲 Wrong

In intelligent driving, lidar is the only sensing device.
🔲 Right
✅ Wrong