**#🧠 Brain Tumor Detection using Deep Learning | CNN, VGG16, MobileNetV2, EfficientNetB0, ResNet50**

This project focuses on the development of an automated system for detecting brain tumors from MRI scans using deep learning techniques. The goal was to reduce reliance on manual diagnosis and accelerate detection with high precision and generalizability.

We designed a custom CNN and implemented transfer learning models such as VGG16, MobileNetV2, ResNet50, and EfficientNetB0. These models were trained and evaluated on a labeled MRI image dataset. To enhance model performance and avoid overfitting, we applied data augmentation, normalization, and hyperparameter tuning techniques.

🔹 Key Highlights:

1.Achieved 86.84% accuracy with MobileNetV2, the highest among tested models.
2.VGG16 showed strong training performance (99.44%) but moderate validation accuracy (84.21%), indicating slight overfitting.
3.Custom CNN model achieved a solid 84% accuracy with balanced precision and recall.
4.Explored ensemble learning using majority voting, though it yielded only 53.95% accuracy — suggesting a need for more advanced ensembling strategies.
5.Used bounding box localization for highlighting tumor regions in MRI scans.
6.Evaluated models using accuracy, precision, recall, F1-score, and confusion matrices for robust assessment.

🔬 Future Scope:

1.Integration of deeper models like EfficientNetB3, ResNet101, and InceptionV3.
2.Building real-time diagnostic tools for clinical use3.
3.Improved generalization through advanced augmentation and larger datasets.

This project demonstrates the potential of AI in medical imaging and has strengthened my skills in model comparison, transfer learning, and interpretability in healthcare AI applications
