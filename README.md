# respiratoryDiagnostic
##Abstract
AI-based diagnostic systems have immense potential in transforming healthcare, particularly in the timely detection of 
respiratory diseases. Nonetheless, lack of interpretability in octopus nets remains one of the chief barriers to their 
clinical deployment, particularly in children. Models also promise to empower clinicians, and they cannot be simply 
high-performing systems but rather transparent systems that can explain how and why a given prediction was made so 
that clinical safety and trust can be built. 

This project aims to create an interpretable deep learning pipeline for respiratory sound classification. This paper 
attempts to classify respiratory diseases from lung sound spectrograms using the ICBHI 2017 Lung Sound Dataset. 
We utilize Convolutional Neural Networks (CNNs) because of their success in learning spatial patterns from audio 
spectrogram images. In an effort to address the black-box nature of CNNs, we appended Grad-CAM++, a state-of
the-art explainability technique, to produce visual explanations identifying which parts of spectrograms contribute 
most to the model’s predictions. 
With this approach, we seek to achieve not just accurate classification performance, but also robust and clinically 
relevant local visualizations that render decisions interpretable to healthcare providers. Early results show good 
accuracy and intuition in visual interpretation. We hope this project will thus fill the first steps gap between AI 
performance and clinical trust in their plausible use and therefore provide the basis for future real-world validation and 
deployment of explainable AI in a health-care context. 
## Objective
* Convolutional neural networks (CNNs) are well-suited to analyzing spectrograms of respiratory sounds due to their 
ability to extract spatial patterns. However, their decision-making processes remain opaque, limiting their usefulness 
in real-world medical settings. This project focuses on integrating explainability techniques, specifically Grad
CAM++, to make CNN predictions more transparent and clinically actionable. 
* Through this project we address the lack of interpretability in convolutional neural networks (CNNs) used for 
classifying respiratory sounds from spectrograms. By applying Grad-CAM++, we aim to generate detailed 
explanations that highlight the regions of spectrograms contributing to each classification. Using the ICBHI 2017 
Respiratory Sound Dataset, our goal is to improve clinical trust in CNN-based models by making their predictions 
transparent and easier for physicians to validate.-

https://bhichallenge.med.auth.gr/ICBHI_2017_Challenge,.
