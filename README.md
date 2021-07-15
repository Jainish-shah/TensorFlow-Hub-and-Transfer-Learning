# TensorFlow-Hub-and-Transfer-Learning
In this repository, I have used transfer learning where the pre-trained models are taken from TensorFlow Hub.

**Transfer Learning**: A technique that reuses a model that was created by machine learning experts and that has already been trained on a large dataset. When performing transfer learning we must always change the last layer of the pre-trained model so that it has the same number of classes that we have in the dataset we are working with.

![Screenshot (582)](https://user-images.githubusercontent.com/47889375/125836421-ed8de828-1e04-4c75-becc-737458e60a03.png)

**Freezing Parameters**: Setting the variables of a pre-trained model to non-trainable. By freezing the parameters, we will ensure that only the variables of the last classification layer get trained, while the variables from the other layers of the pre-trained model are kept the same.

*NOTE*, Not to change the pretrained part of the model during the training process. This is done so by setting the variables of the pretrained model to **non trainable**.
One of the benefits of not changing the pre-trained part is, it reduces the training time.

**MobileNet**: A state-of-the-art convolutional neural network developed by Google that uses a very efficient neural network architecture that minimizes the amount of memory and computational resources needed, while maintaining a high level of accuracy. MobileNet is ideal for mobile devices that have limited memory and computational resources.
