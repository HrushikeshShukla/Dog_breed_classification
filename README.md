# Dog_breed_classification
It provides a model to detect 10 distinct models.
This is a Dog Breed classification project. It detects the breeds of dogs namely 'beagle', 'chihuahua', 'doberman', 'french_bulldog', 'golden_retriever', 'malamute', 'pug', 'saint_bernard', 'scottish_deerhound', and 'tibetan_mastiff'.
I got the dataset from Kaggle from here: https://www.kaggle.com/c/dog-breed-identification/data
Further I explored the data for total number of breeds and reduced these 10 breeds.
Then I applied Image Augmentation which included horizontal and vertical flips, change of brightness, zoom range and many more.
I used pretrained ResNet50 followed 2 fully layers for classification.
The model is later trained on the entire reduced dataset for better performance. The saved model can be downloaded from here: https://drive.google.com/drive/folders/15LmYdef0gJ1bzZV7j9tFuHWbLWOSfGsP?usp=sharing
I also further tested the model on 2 images namely img1 and img2 and the classification was accurate.
