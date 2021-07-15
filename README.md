# TensorFlow-Hub-and-Transfer-Learning
In this repository, I have used transfer learning where the pre-trained models are taken from TensorFlow Hub.

**Transfer Learning**: A technique that reuses a model that was created by machine learning experts and that has already been trained on a large dataset. When performing transfer learning we must always change the last layer of the pre-trained model so that it has the same number of classes that we have in the dataset we are working with.

*NOTE*, Not to change the pretrained part of the model during the training process. This is done so by setting the variables of the pretrained model to **non trainable**.
One of the benefits of not changing the pre-trained part is, it reduces the training time.

