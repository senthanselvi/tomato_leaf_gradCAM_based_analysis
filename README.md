# tomato_leaf_gradCAM_based_analysis

In this research, we focused on developing an efficient and automated method for detecting and analyzing diseases in tomato leaves, specifically targeting Early Blight, Late Blight, and Septoria Leaf Spot. These diseases severely impact crop yield and quality, and traditional manual methods for disease identification are both time-consuming and error-prone. To address this, we leveraged convolutional neural networks (CNNs) like ResNet, DenseNet, and VGG, along with Gradient-weighted Class Activation Mapping (Grad-CAM), to classify diseases and quantify the affected leaf area. DenseNet201 stood out as the most effective model in our evaluations, offering high accuracy and robust performance. Additionally, Grad-CAM enabled us to visualize and highlight disease-specific patterns, which allowed us to assess the severity of the infections both quantitatively and visually.

![image](https://github.com/user-attachments/assets/25cb9e23-aa53-468d-8544-cfa1f01b2d6a)

![image](https://github.com/user-attachments/assets/69649f6e-2b52-4d39-9416-7747e5ecaa19)

While working on this project, we noticed that certain diseases, like Early and Late Blight, often exhibit overlapping percentages of affected areas, making it challenging to differentiate between them. To overcome this, we relied on Grad-CAM heatmaps to pinpoint unique spatial patterns associated with each disease, improving our diagnostic capabilities. We also applied data augmentation techniques and fine-tuned the models to enhance performance and reduce overfitting, ensuring that our approach was scalable and effective across different conditions. This study reinforced the potential of combining advanced CNN architectures with Grad-CAM visualization to provide actionable insights for precision agriculture, helping farmers make timely and informed decisions for better crop management.

![image](https://github.com/user-attachments/assets/91a13ec4-827b-4bc5-aa4c-7dbd73c0f59e)

