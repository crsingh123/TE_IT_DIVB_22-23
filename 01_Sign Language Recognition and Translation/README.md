Title: Sign langage Recognition and Transalation

Group Members:
Pooja Sharma,
Nainisha Sharma,
Disha Bendale

Implementation:

Sign Language Recognition: 
1. First, the dataset for training and testing the model is collected. This dataset consists of images of different hand gestures representing letters or words in ISL.
2. Next, the VGG16 model is imported and initialized in Python using the Keras library. This model is pre-trained on the ImageNet dataset, which includes millions of images. 
3. After initializing the VGG16 model, the dataset is pre-processed by resizing the images to a fixed size and normalizing the pixel values. 
4. Then, the dataset is split into training and testing sets. The training set is used to train the VGG16 model on the ISL images, while the testing set is used to evaluate the performance of the model. 
5. The VGG16 model is then trained using the training set of ISL images. The model is trained using a process called backpropagation, which adjusts the weights of the model based on the errors made during training. 
6. Once the VGG16 model is trained, it is used to predict the ISL gestures from the testing set of images. The accuracy of the model is evaluated by comparing the predicted labels to the actual labels of the testing set. 
7. Finally, the trained VGG16 model can be used to recognize ISL gestures in real-time using a webcam or other input devices. The model takes in the input images and predicts the corresponding ISL gesture in real time. 
  In summary, the implementation of the project that uses VGG16 for recognizing ISL through Python and its libraries involves data collection, pre-processing, model initialization and training, evaluation, and real-time recognition.

Text To Sign Language: 
1. Data Collection: We first collected images containing the gesture regarding the sign and named the image accordingly. 
2. GUI: Using Tkinter we then created a window that contains a text field and a button that will help the user translate the text into sign language. 
3. NLP: The entered text will then be processed through NLP 
4. Fetch: The processed text will then read and then find the image name similar to the input text. 
5. Display: The most similar image will then be displayed to the user as the output.
