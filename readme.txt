Each cell of the code has been explained as below:-

## 1. Mount Google Drive
- Mounts Google Drive to access files.

## 2. Extract Zip File
- Extracts contents of a zip file in Google Drive to a specified folder.

## 3. Check Video Corruption
- Checks and validates videos for corruption using OpenCV and PyTorch transformations.
- Prints information about corrupted videos.

## 4. Load Preprocessed Videos
- Loads preprocessed videos into memory.
- Shuffles and displays information about the number of frames per video.

## 5. Load Labels and Split Data
- Loads labels from a CSV file.
- Splits the dataset into training and validation sets.

## 6. Define Video Dataset Class
- Defines a custom dataset class for loading videos and labels.

## 7. Visualize a Video Frame
- Displays a sample video frame using matplotlib.

## 8. Define the Model
- Defines a custom neural network model using a pre-trained ResNeXt50 as the backbone.

## 9. Training and Testing Functions
- Defines functions for training and testing the model.
- Calculates and prints accuracy and loss during training and testing.

## 10. Average Meter Class
- Defines a class for calculating and storing average and current values.

## 11. Train the Model
- Trains the defined model using the training dataset.
- Saves the model's state dictionary and plots training/validation loss and accuracy.

## 12. Evaluate the Model
- Evaluates the trained model on the validation dataset.
- Prints and plots confusion matrix and accuracy.

## 13. Calculation of the F1 score
- Calculates the F1 score using confusion matrix as mentioned in the document provided.

Note: Adjust file paths and ensure necessary libraries are installed when running the code outside of a Colab environment.
