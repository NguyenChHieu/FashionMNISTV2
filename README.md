This is the first convolutional neural network I have trained on the FashionMNIST dataset.

## Overview
+ This model is trained based on a toy dataset extracted from the `FashionMNIST` - PyTorch built-in dataset.
+ The original model was created here `https://github.com/zalandoresearch/fashion-mnist`
+ FashionMNIST contains ~ 60000 training sets of examples and 10000 training sets of examples, which is perfect for CNNs.
+ I learned and applied the concepts and guides from this video `https://www.youtube.com/watch?v=V_xro1bcAuA` and tried to recreate the model.

## Results:
+ Compared to the normal model (no CNNs) - FashionMNISTV2 was 5% better at accuracy and sligtly better at %loss while running on a T4-GPU in GoogleColab.

<img width="580" alt="image" src="https://github.com/NguyenChHieu/FashionMNISTV2/assets/140675996/703dd437-30e9-483e-ad8f-ab121f68afbd">

+ It has an amazing **88%** in terms of accuracy and 0.32% in terms of test loss.

<img width="226" alt="image" src="https://github.com/NguyenChHieu/FashionMNISTV2/assets/140675996/44ebdb80-e6da-46cb-88ab-5af02a8d4c9a">

+ The user can visualize its predictions and see if the predictions match the test samples or not with the `make_predictions` function.

<img width="487" alt="image" src="https://github.com/NguyenChHieu/FashionMNISTV2/assets/140675996/b1d9ef1f-1eed-4ca8-8ea5-773d85a695d1">

+ Plotted confusion matrix for additional evaluation layers:
  + Identifying the problematic labels such as "T-shirt/top" --> "Shirt".
  + See the overall model's performance.
 
<img width="447" alt="image" src="https://github.com/NguyenChHieu/FashionMNISTV2/assets/140675996/794d69af-c938-4f64-bf7f-17d90695bc72">

+ Saved model to the appropriate file for reusability.
+ Load the saved model to check if the states of the model remained the same.
