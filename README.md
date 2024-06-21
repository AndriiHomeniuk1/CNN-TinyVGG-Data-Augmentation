# TinyVGG with Data Augmentation

## Description

This project presents a practical demonstration of training a custom convolutional neural network (CNN) model using the TinyVGG architecture on the "Horse or Human" dataset.
The project emphasizes the effective use of data augmentation techniques to improve the neural network's training process.
It encompasses the complete workflow, starting from the creation of a specialized dataset to the application of transformation techniques during training.
The results are saved and analyzed to evaluate the model's performance enhancements.

## Project Overview
- Creating a Custom Dataset
- Creating Transformations with Data Augmentation
- Creating Train and Test Datasets and DataLoaders
- Displaying Random Images with Augmentation
- Constructing and Training the Model
- Visualizing Loss Curves
- Making Predictions on Custom Images
- Saving and Loading the Model
- Evaluating the Loaded Model

## Results
### Training Results
| Epoch | Train Loss | Train Accuracy |
|-------|-------------|----------------|
| 0     | 0.6795      | 54.48%         |
| 1     | 0.6262      | 63.32%         |
| 2     | 0.5436      | 70.68%         |
| 3     | 0.5591      | 70.86%         |
| 4     | 0.4769      | 78.03%         |
| 5     | 0.4215      | 79.55%         |
| 6     | 0.4499      | 77.62%         |
| 7     | 0.4512      | 80.24%         |

### Test Results
| Epoch | Test Loss | Test Accuracy |
|-------|-----------|---------------|
| 0     | 0.6779    | 50.00%        |
| 1     | 0.6451    | 54.69%        |
| 2     | 1.3303    | 50.00%        |
| 3     | 0.5888    | 62.11%        |
| 4     | 0.4723    | 75.39%        |
| 5     | 0.3607    | 87.89%        |
| 6     | 0.2936    | 91.41%        |
| 7     | 0.2831    | 89.06%        |

## Repository Structure
- `README.md`: This file provides an overview of the project.
- `TinyVGG_with_Data_Augmentation.ipynb`: Jupyter notebook containing the code for training the model.
- `saved_models`: Directory where the trained model is saved.
