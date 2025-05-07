# Skin Cancer Detection
Melanoma Classification Using Deep Learning Across Skin Tones
Melanoma is the most lethal form of skin cancer, with early detection being critical to effective treatment. However, diagnostic accuracy varies significantly across different skin tones. This project investigates the application of deep learning to dermoscopic image classification and evaluates how well existing models perform across Fitzpatrick skin types.

# Description
This work examines the diagnostic performance of five pre-trained Convolutional Neural Network (CNN) architectures—VGG16, ResNet50, Xception, DenseNet201, and MobileNetV2—for melanoma classification using dermoscopic images. A comprehensive pipeline was developed, incorporating:

Contrast enhancement with CLAHE (Contrast Limited Adaptive Histogram Equalization)

Stratified preprocessing for balanced skin tone representation

Real-time data augmentation to reflect clinical variability

Models were evaluated both on overall accuracy and performance across Fitzpatrick skin types, revealing disparities in detection rates. Xception and DenseNet201 achieved the best results, particularly on medium to darker skin tones, while performance dropped on lighter skin types.

These findings underscore the importance of equitable datasets and skin-tone-aware AI in medical imaging, and provide a pathway toward more inclusive and reliable diagnostic tools.
