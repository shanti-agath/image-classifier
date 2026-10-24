👕 Image Classifier (CNN)

Classifies clothing images into 10 categories using a Convolutional Neural Network built with Keras. Built as part of my AI/ML learning journey.

🛠️ Tech Stack
Python
TensorFlow / Keras
NumPy
Scikit-learn (metrics)
Matplotlib, Seaborn

📊 What This Project Does
Loads the Fashion-MNIST dataset (70,000 grayscale images, 28x28 pixels, 10 classes)
Normalises and reshapes the images
Builds a CNN with 2 convolution layers, max pooling, dropout and dense layers
Trains for 10 epochs with a validation split
Plots training and validation accuracy and loss
Evaluates on 10,000 unseen test images
Shows a confusion matrix and sample predictions
Saves the trained model

📈 Results
Metric	Value
Test accuracy	fill after running
Test loss	fill after running

Training Curves Confusion Matrix Sample Predictions

💡 Key Findings
Which classes did the model confuse most? (look at the confusion matrix)
Did the model overfit? (compare train and validation curves)
Write 2 to 3 findings from your own results

🔮 Next Steps
Try a deeper CNN and data augmentation
Try the CIFAR-10 dataset (colour images)
Try transfer learning with a pre-trained model

🚀 How to Run
``Bash
pip install -r requirements.txt
jupyter notebook image_classifier.ipynb
``

The dataset downloads automatically the first time you run the notebook.

📁 Project Files
image_classifier.ipynb : full notebook with code, outputs and charts
requirements.txt : libraries needed
*.png : result charts
📚 Dataset

Fashion-MNIST (Zalando Research), loaded through Keras.

👤 Author

Shanti | Aspiring AI/ML Developer | Open to Work
