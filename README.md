# AI07_Project_4-Semantic-Segmentation-for-cell-neuclei
This project show how to do semantic segmentation by taking the images of cell neuclei as the example.<br>
You can find the image data from the [Release](https://github.com/ChernXi/Project_4_Semantic_Segmentation/releases), and follow the code to see how it was done.<br>
I wrote the code using the environment of google colab. If you were to run it in your local machine, you'll need to modify the code a little bit. <br>

Below are some samples of images and masks(labels) that used for training:
![semantic segmentation](https://user-images.githubusercontent.com/108325848/184470998-bbc8e68d-707e-47bd-8961-641bb30f500e.png)

Sample of image, label, and auto-masking(prediction) before training:
![image](https://user-images.githubusercontent.com/108325848/184471263-a40c6211-fd9b-45e6-9031-5d54ae2cdf92.png)

Sample of image, label, and auto-masking(prediction) after training:
![image](https://user-images.githubusercontent.com/108325848/184471134-bb33bbf4-25bb-4711-b657-8d8d37d177cb.png)

## Advantage of using deep learning in Semantic Segmentation
You may be wondering why we need deep learning to do semantic segmentation when we can do it manually and the masking artwork appears to be even more meticulous.<br>
The reason is simple:<br>
<p align="center">
Deep learning allows computers to generalise our meticulous artwork and apply it to previously unseen scenarios.
</p> 
Therefore, by investing a small amount of time in deep learning, we can save an endless amount of time by performing manual masking in the future.<br>
Additionally, even if we are no longer able to perform the masking, our work can be passed down to the next generation.<br>
Hence, in the long term, it is essential to employ deep learning in semantic segmentation.<br>
