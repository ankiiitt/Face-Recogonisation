# Face-Recogonisation
Create a project using transfer learning solving various problems like Face Recognition, Image Classification, using existing Deep Learning models like VGG16, VGG19, ResNet, etc.
We are using face recognition in our daily life activity, like attendance system, monitoring, camera, or in fact, we open our screen lock use our face. So, the Face Recognition program is been part of our daily life.

The main technology work behind the face recognition is Machine Learning.

In this task, we are going to use MobileNet to create a face recognition program.

As we know, any machine learning requires data, so that machine can be trained. For creating the data as an image, harcasscade model is used.

Code for the harcascade Model.
Then, once we start the harcascade programme, it clicks photos for data.
Machine Learning cannot give better accuracy if you do not have sufficient data. So we import the data generator library of Keras.
The main important part of Machine Learning is data
processing. So our next step is to split the collected data into two forms - train & validation.
After this, there is one important part of transfer learning is adding layers. 
Once your data is prepared, and we added the layer then move to the training part of the model.
After 5 epoc, accuracy comes out to be 93 %.

Now save the model, so that we can use it further. 
Once all things we have done, the next process is to test the model. we call the test data using some function.
 The machine predicts the face.
