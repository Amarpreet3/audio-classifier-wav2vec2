# Audio Classifier with Wav2Vec 2.0

This repository contains the implementation of an audio classifier using Wav2Vec 2.0. The model is designed to distinguish between fake and real audio samples.

## Dataset

The dataset used for training, testing, and evaluation can be found on Kaggle: [The Fake or Real Dataset](https://www.kaggle.com/datasets/mohammedabdeldayem/the-fake-or-real-dataset).

## Model Training

Due to the extensive time required for training, the model was trained on only 5% of the dataset. The model used for this task is Wav2Vec 2.0, a powerful framework for audio classification tasks.

## Evaluation

The model was evaluated using audio samples provided by Trebble. The results and performance metrics of the evaluation are included in this repository.

## Repository Contents

- `wav2vec.ipynb`: Jupyter notebook containing the code for training, testing, and evaluating the audio classifier.
- `README.md`: This file, providing an overview of the project.
- Other relevant scripts and files related to the project.

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/audio-classifier-wav2vec2.git
    cd audio-classifier-wav2vec2
    ```

2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook wav2vec.ipynb
    ```

## Dependencies

The project requires the following dependencies:

- Python 3.8+
- Jupyter Notebook
- PyTorch
- Transformers
- Other dependencies specified in `requirements.txt`

## Results

The performance of the model was evaluated using the Trebble audio samples. Detailed results and metrics can be found in the `wav2vec.ipynb` notebook.

## Contributing

Contributions to this project are welcome. If you have any suggestions or improvements, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- The dataset was provided by [Mohammed Abdeldayem](https://www.kaggle.com/mohammedabdeldayem) on Kaggle.
- The model architecture is based on Wav2Vec 2.0 by Facebook AI Research.

