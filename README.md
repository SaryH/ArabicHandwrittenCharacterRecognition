Arabic Handwritten Character Recognition (AHCR) Using Convolutional Neural Networks

This project delves into the challenges and solutions for Arabic Handwritten Character Recognition (AHCR) using various Convolutional Neural Network (CNN) architectures. The work showcases the implementation and comparison of multiple models to identify the most effective approach for AHCR.

Introduction

Recognizing handwritten text, particularly Arabic script, poses a significant challenge in computer vision due to the unique patterns and diverse styles influenced by factors such as age, background, language, and mental state. Arabic script's semi-cursive writing and right-to-left orientation, along with 28 alphabet characters that change shape based on their position in a word, add to the complexity. This project explores the application of advanced CNN architectures, including AlexNet and GoogLeNet, to improve the precision of Arabic handwriting recognition.

Tasks and Methodology

Task 1: Custom CNN Architectures for AHCR

Task 1-1: Building a Custom CNN Network

Designed a CNN with convolutional, pooling, fully connected, and dropout layers.

Achieved a test accuracy of 96.19%.

Task 1-2: Building Another Custom CNN Network

Implemented an alternative CNN architecture.

Achieved a test accuracy of 93.69%.

Task 2: Data Augmentation

Augmented the dataset using techniques like contrast adjustment, salt noise, and rotation.

Retrained the best-performing custom CNN from Task 1-1.

Achieved a test accuracy of 95.41%.

Task 3: AlexNet CNN Network

Employed the AlexNet architecture on the augmented dataset.

Achieved a test accuracy of 96.01%.

Task 4: Pretrained GoogLeNet CNN Network

Applied transfer learning with GoogLeNet, fine-tuning the model for AHCR.

Achieved a test accuracy of 94.99%.

Results and Analysis

Task 1-1's Custom CNN outperformed other models, indicating its effective design for AHCR without the need for data augmentation.

Task 2's Augmentation slightly reduced performance, suggesting the augmentation techniques might have introduced complexity not effectively captured by the validation data.

AlexNet and GoogLeNet demonstrated competent learning but showed higher overfitting compared to the custom CNN from Task 1-1.

Conclusion

The project highlights the efficacy of custom CNN architectures tailored for specific tasks, such as AHCR. The first custom CNN model achieved the highest accuracy and generalization without augmentation, underscoring the importance of model architecture in addressing complex pattern recognition tasks. The comparison with popular models like AlexNet and GoogLeNet further emphasizes the need for well-tuned models specific to the dataset and task.
