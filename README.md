# AI-Tomato-Plant-disease-detection

About My Project

I created this project to identify diseases in tomato leaves using AI. I used a CNN model to predict the disease from an uploaded leaf image.

What My Project Does

- Detects four tomato leaf classes: Healthy, Early Blight, Late Blight, and Leaf Mold.
- Shows the predicted disease and confidence score.
- Gives basic treatment suggestions.
- Shows an estimated severity level based on leaf colors.
- Uses a confusion matrix, precision, recall, and F1-score to evaluate the model.

Technologies I Used

- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Scikit-learn
- Gradio

Dataset

I used the PlantVillage dataset and selected four tomato leaf classes for this project.

Dataset: https://github.com/spMohanty/PlantVillage-Dataset

How It Works

1. I collected tomato leaf images from the dataset.
2. I resized the images for the model.
3. I trained a CNN model using TensorFlow and Keras.
4. I used the model to predict diseases from leaf images.
5. I created a Gradio app where users can upload a leaf image and see the results.


What I Learned

While building this project, I learned about CNNs, image classification, data augmentation, model evaluation, and creating a simple app using Gradio. I also learned how to find and fix coding errors.

Limitations

- The model works with only four selected tomato leaf classes.
- Predictions may not always be correct.
- The severity result is only a basic estimate based on leaf colors.
- Treatment suggestions are general guidance and may not work for every plant.

AI Tools

I used AI tools to help me understand concepts and fix coding errors during development. I also practised running the code and understanding how the different parts work.

Future Improvements

I would like to improve the model's accuracy and make the disease predictions more reliable
