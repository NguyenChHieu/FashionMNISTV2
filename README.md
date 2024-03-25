This is the first convolutional neural network I have trained on the FashionMNIST dataset.

## Overview
+ This model is trained based on a toy dataset extracted from the `FashionMNIST` - PyTorch built-in dataset.
+ The original model was created here `https://github.com/zalandoresearch/fashion-mnist`
+ FashionMNIST contains ~ 60000 training sets of examples and 10000 training sets of examples, which is perfect for CNNs.
+ I learned and applied the concepts and guides from this video `https://www.youtube.com/watch?v=V_xro1bcAuA` and tried to recreate the model.

## Results:
+ Compared to the normal model (no CNNs) - FashionMNISTV2 was 5% better at accuracy and sligtly better at %loss while running on a T4-GPU in GoogleColab.

<img width="580" alt="image" src="https://github.com/NguyenChHieu/FashionMNISTV2/assets/140675996/703dd437-30e9-483e-ad8f-ab121f68afbd">

+ It has an amazing **89%** in terms of accuracy and 0.29% in terms of test loss.

<img width="236" alt="image" src="https://github.com/NguyenChHieu/FashionMNISTV2/assets/140675996/7fb91336-6a40-4886-a86e-157dc5d960ae">

+ The user can visualize its predictions and see if the predictions match the test samples or not with the `make_predictions` function.

<img width="487" alt="image" src="https://github.com/NguyenChHieu/FashionMNISTV2/assets/140675996/b1d9ef1f-1eed-4ca8-8ea5-773d85a695d1">

+ Working on plotting confusion matrix for additional evaluation aspects.
