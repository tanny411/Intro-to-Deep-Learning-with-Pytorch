## Lesson 6: CNN

### MLP:
- Working with MNIST Dataset (basics)
- Important steps are flattening and **Normalization**(/255)
- The distribution of such data should resemble a Gaussian function centered at zero. For image inputs we need the pixel numbers to be positive, so we often choose to scale the data in a normalized range [0,1].
- Search codes for hidden layer and nodes numbers intuition
- MLP model training the MNIST Dataset (2 ff layers) (Videos 12-13)
- Explore various kinds of Loss functions and optimizers
- Training and Validation and Test sets
- Validation set in code (Video 15, uses subset random sampler and keeps saving the minimum validation loss model; but not stopping training)
- The pipeline:
![image classification pipeline](images/mlp.png)


### CNN
From Video 17: CNNS

