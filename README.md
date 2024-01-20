# Smile Detection Using GENKI Dataset

## Project Overview
This project focuses on the development of a smile detection system using the GENKI dataset. The dataset includes 4,000 photographs of people, annotated for the presence of a smile (1) or absence of a smile (0), thereby framing it as a binary classification problem. Our approach involved training on 70% of the dataset and testing on the remaining 30%.

## Models Used
We employed three different models for this task:
1. **LeNet**: A convolutional neural network suitable for image classification tasks.
2. **ResNet-50**: A more complex, deeper network known for its high accuracy in image recognition.
3. **Custom Attention Model**: Developed in-house to specifically focus on features relevant to smile detection.

## Results
Our experiments revealed that despite its computational intensity, **ResNet-50** outperformed the other models in terms of accuracy. This highlights the effectiveness of deep learning architectures in handling complex image classification tasks like smile detection.

## Dataset
- **Source**: GENKI Dataset
- **Size**: 4,000 images
- **Labels**: Smile (1), No Smile (0)
- **Training Split**: 70%
- **Testing Split**: 30%


## Usage
To replicate our results or to use the models for further research:
1. Download the GENKI dataset.
2. Train the models using the provided scripts.
3. Evaluate the models on the test set.
4. Compare the performance metrics of the different models.

## Conclusion
The project demonstrates the viability of using advanced deep-learning models for the task of smile detection. The superior performance of ResNet-50 underscores the importance of deep and complex architectures in computer vision.

## Future Work
Future enhancements may include experimenting with other advanced neural network architectures, fine-tuning the models for better accuracy, or expanding the dataset for more robust training.

## Acknowledgements
Special thanks to the creators of the GENKI dataset and the contributors to the TensorFlow and Keras libraries, which made this project possible.
