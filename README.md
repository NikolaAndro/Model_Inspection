# Model_Inspection
Inspecting ML models using heat map and TCAV.

In the HW3_Question1_FINAL is where I built a custom CNN for recognizing hand-written digits from cifar10 dataset as well as another custom CNN that has Resnet50 for its base (**Transfer Learning**).

These 2 models are trained and the models are saved (to be used in the other file) as well as their fitting histories (to be used in plotting if a session expires)

In the HW3_Question2_FINAL, I created heatmap for my CNN model from the HW3_Question1_FINAL file on a random image of a horse.

Finally, the most exciting part **TCAV** did not work. I tried to run it on cifar100 images of cloud. However, it seems that TCAV is not capable to cooperate with tensorflow 2 and tf.keras models... 

I did not follow the main repo that they propose since it is fitted for ImageNet. [This post](https://www.kaggle.com/code/mihaelkheel/cifar10-tcav/notebook) has its own version. However, this could not work with tensorflow 2... Did not know how to fix it...
