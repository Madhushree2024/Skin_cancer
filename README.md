The project titled "Skin Cancer Classification Using Convolutional Neural Networks" involves the development of a machine learning model to classify skin lesions as either benign or malignant based on image data. The project is implemented using TensorFlow and Keras, leveraging the power of Convolutional Neural Networks (CNNs) to process and analyze images of skin lesions. The primary goal is to assist in the early detection of skin cancer, a critical factor in improving patient outcomes.

The application is built using Streamlit, a popular framework for deploying machine learning models with an interactive web-based user interface. The project begins with a simple login mechanism to restrict access, ensuring that only authorized users can interact with the model. Once logged in, users are presented with a detailed interface where they can upload images of skin lesions for classification.

The model is trained on a dataset of skin lesion images, utilizing an ImageDataGenerator to handle real-time data augmentation, which enhances the model's ability to generalize by creating variations in the training data. The dataset is split into training and validation sets, with images being rescaled and subjected to transformations like shear, zoom, and horizontal flips.

The CNN model consists of two convolutional layers followed by max pooling layers, a flattening layer, and dense layers for classification. A dropout layer is included to prevent overfitting. The model is compiled using the Adam optimizer and trained for a limited number of epochs to balance computational efficiency and performance. After training, the model's accuracy and loss are plotted, providing insights into its learning process.

Once the model is trained, it can predict the class of skin lesions from uploaded images. The prediction results are displayed alongside a bar chart showing the probabilities for each class. Additionally, the application offers audio feedback, powered by the pyttsx3 library, which reads out the predicted class and provides relevant information on symptoms associated with benign or malignant lesions.

In summary, this project integrates deep learning with an accessible user interface to create a tool that could potentially aid in the early detection of skin cancer, making it a valuable contribution to the field of healthcare technology.







