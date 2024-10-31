Melanoma accounts for 75% of skin cancer deaths and detecting it early is crucial. In my latest project, I took on the challenge of designing and training a custom convolutional neural network (CNN) model in TensorFlow to classify nine types of skin lesions, including melanoma.

🚀 Project Highlights:
Objective: Develop a model to aid dermatologists by detecting melanoma and other skin lesions automatically, helping reduce the manual diagnosis workload.
Data: Used a dataset of 2,357 images from the International Skin Imaging Collaboration (ISIC) with classes like Actinic keratosis, Melanoma, Basal cell carcinoma, and more.

Pipeline:
Data Preprocessing: Images resized and normalized for optimal input.
Data Augmentation: Applied transformations like rotation, zoom, and shifts to tackle overfitting.
Class Imbalance Handling: Augmented underrepresented classes to balance the dataset, essential for fair and accurate predictions across all categories.

🧠 Model Architecture:
Built a custom CNN model from scratch without transfer learning, featuring multiple convolutional and pooling layers to extract crucial image features. Selected Adam as the optimizer and categorical cross-entropy for multiclass classification.

🔍 Results & Insights:
Trained on ~20 epochs initially and adjusted for signs of overfitting/underfitting by fine-tuning data augmentation and regularization.
Improved performance by balancing class distribution, ensuring the model generalizes better across all nine classes.

💡 Takeaways:
This project reinforced my knowledge in CNN architectures, data augmentation techniques, and strategies to handle class imbalance effectively. Working on this has been an incredible experience, and I'm excited to apply these learnings to future data science challenges in healthcare and beyond!
