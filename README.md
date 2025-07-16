# An-interactive-deep-learning-based-brain-tumor-detection-and-classification-system

Detecting a Brain Tumor Early and Well is Important for Brain Tumor Treatment. Manual analysis of MRI images requires substantial time and may be prone to errors. The purpose of this research is to develop an interactive web-based deep learning system that is able to detect the presence of a brain tumor in MRI images and to classify the type as either glioma, meningioma, pituitary tumor or normal. The focal point of the research is whether a user- friendly platform can integrate high-performing Convolutional Neural Network (CNN) models for reliable real-time tumor analysis. The primary modules of the system are a Tumor Presence Checker, and a Tumor Classifier. Users upload brain MRIs via a browser for outcome prediction. Two custom convolutional neural networks (CNNs) and three variations (DenseNet-201, ResNet, and Xception ) were trained on a public brain MRI dataset. We evaluated the performance of our systems based on accuracy, precision, recall and F1. The site was built using Flask (backend) and the SQLite3 (user authentication and management). Xception is the best architecture developed above all for classification with 98% accuracy. It can classify cases above all tumor type and normal ones. The system can competently classify both tumor and normal images. Thus, it can be a complete diagnostic tool. It demonstrates that combining advanced CNN with web-based interaction is effective for brain tumor detection and classification. The system is available, dependable and flexible for use in clinics and studies. Future improvements will focus on generalization, larger datasets, and tumor segmentation.

**Tumor Presence checker .**
In the first stage, it was to detect whether the MRI image of a brain contained a tumor or not. Out of the four, the highest accuracy was achieved by the Xception model as against the others. The results are summarized below.
Xception.
Accuracy: 98%.
Precision: 97.5%.
Recall: 98.2%.
F1-score: 97.8%.
DenseNet-201:
Accuracy: 96.5%.
F1-score: 96.2%.
ResNet:
Accuracy: 95.8%.
F1-score: 95.3%.
CNN:
Accuracy: 91.2%.
F1-score: 90.7%.
These results indicate that all models performed well, but Xception consistently had better classification performance for tumor and non-tumor images.

**Tumor Classification.**
During step two, any image showing a tumor will be classified under any of the three categories which are “glioma,” “meningioma” or a “pituitary tumor.” The system could also find normal MRIs, allowing it to be directly used on mixed datasets.
Once again, outperformance of other architectures was achieved by Xception model.
Xception.
Accuracy: 97.8%.
Precision: 97.6%.
Recall: 97.9%.
F1-score: 97.7%.
The DenseNet-201 and ResNet model had slightly less performance while the

custom CNN model had moderate classification accuracy which shows that the advanced pre-trained networks are more advantageous for the diagnosis of medical images.

**Conclusion**

This study proposes an interactive brain tumor detection and classification system based on deep learning from MRI images. The presence of tumor and classification in glioma, menigioma, pituitary tumor and normal. Four models will be evaluated and compared in two stages. Custom CNN, DenseNet-201, ResNet and Xception. The Xception model proved to be the most effective among them with an accuracy of 98% for detecting tumors and 97.8% for classifying tumors.

Incorporating this model into a web application suits it for practical deployment enabling users to upload MRI images and receive instant diagnostic predictions accordingly. Both clinical professionals and learners will find it easy to access and understand the interactive interface and backend model comparison features.
Although the model shows a lot of promise, the dataset size and limited tumor types indicated that more expansion is needed and iteration. In the future, the classification will further impose some other tumors’ subtypes. Also, applied on larger datasets.
All in all, the proposed solution connects state-of-the-art deep learning techniques with user-oriented design, which has been shown to successfully perform reliable brain tumor analysis in an efficient manner.


