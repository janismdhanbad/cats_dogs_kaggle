# cats_dogs_kaggle
In this repository I have used kaggle's dogs vs cat dataset and vggnet model for classifying the pictures of cats vs. dogs.
The model is made in keras language as it is modular and easy to understand and use. All the pre processing on image is done using opencv 
library. VGG16(which won imagenet 201) net has been used and initially, pretrained weights on Imagenet data are used as weight initialisation and the last layer of the model is
fine tuned for achieving a binary classifier. The original dataset can be downloaded from here (https://www.kaggle.com/c/dogs-vs-cats/data).
I have rearranged the data into separate folders, as required by the keras's generator function.
The training and validation folders are named as train and valid in dogscats folder and the test is in test folder. Everything has been set up according to what is required by keras's function.

Feel free to ping me on janpreetsingh.1@gmail.com for any doubts or further improvemnets that could be made.
