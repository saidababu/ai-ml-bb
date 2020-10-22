# Day 3 - Modeling

Amazon SageMaker provides every developer and data scientist with the ability to build, train, and deploy machine learning models quickly. Amazon SageMaker is a fully-managed service that covers the entire machine learning workflow to label and prepare your data, choose an algorithm, train the model, tune and optimize it for deployment, make predictions, and take action. Your models get to production faster with much less effort and lower cost.

## Bring your Own Model
This lab helps you build your own custom container image with scikit-learn decision treee and then run it on Amazon SageMaker.

https://sagemaker-immersionday.workshop.aws/lab3.html



## Bring your own training-completed model with SageMaker by building a custom container
In this session, you will build a custom container which contains a train-completed Pytorch model, and deploy it as a SageMaker endpoint. Your model is trained elsewhere like on premises perhaps, and you only want to use SageMaker to host the model. The session teaches how to do that. Pyorch/fast-ai model is provided for learning purposes. Once you know how to deploy a custom container with SageMaker, you can use the same approach to deploy the model trained with other machine learning framework.

https://github.com/aws-samples/amazon-sagemaker-custom-container

## SageMaker with Tensorflow2
In this Lab we will train an image classification model using Amazon SageMaker's Tensorflow training container in script mode. https://github.com/githubmg/sagemaker-tensorflow2

