# Face Emotion Detection

This repository contains the implementation of a **Face Emotion Detection** system using the FER-2013 dataset and Convolutional Neural Networks (CNNs). The goal of this project is to accurately classify facial expressions into different categories, such as happy, sad, angry, surprise, etc.

## Features
- **Dataset**: Utilizes the FER-2013 dataset for training and testing.
- **Model Architecture**: Built with Convolutional Neural Networks (CNNs) for high accuracy.
- **Emotion Categories**: Includes common emotions like:
  - Happy
  - Sad
  - Angry
  - Neutral
  - Surprise
- **Visualization**: Displays loss, accuracy, and confusion matrices for better evaluation.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/face-emotion-detection.git
    cd face-emotion-detection
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the FER-2013 dataset:
   - The dataset can be found [here](https://www.kaggle.com/datasets/msambare/fer2013).
   - Place the dataset in the `data/` directory of the project.

## Usage

1. Train the model:
    ```bash
    python train.py
    ```

2. Evaluate the model:
    ```bash
    python evaluate.py
    ```

3. Predict emotions on new images:
    ```bash
    python predict.py --image path/to/image.jpg
    ```

## Project Structure
```
face-emotion-detection/
├── data/               # Dataset directory
├── models/             # Saved models
├── notebooks/          # Jupyter notebooks for exploration
├── src/                # Source code for the project
│   ├── train.py        # Training script
│   ├── evaluate.py     # Evaluation script
│   ├── predict.py      # Prediction script
│   └── utils.py        # Helper functions
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

## Results
- Training Accuracy: ~XX%
- Validation Accuracy: ~YY%
- Example Predictions:

| Input Image        | Predicted Emotion |
|--------------------|-------------------|
| ![Example1](path/to/example1.jpg) | Happy             |
| ![Example2](path/to/example2.jpg) | Sad               |

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- FER-2013 dataset contributors.
- Open-source libraries and tools used in the project.

---

Happy coding!
