# Next Word Prediction Using LSTM

This repository contains the implementation of a next word prediction model using Long Short-Term Memory (LSTM) neural networks. The model is designed to predict the next word in a sequence based on the previous words, similar to text prediction systems used in smartphones and search engines.

## Overview

Next word prediction is a natural language processing task that involves predicting the most likely word to follow a given sequence of words. This implementation uses LSTM networks, which are a type of recurrent neural network (RNN) architecture well-suited for sequence prediction tasks due to their ability to maintain long-term dependencies in text.

## Features

- Text preprocessing and tokenization
- LSTM model implementation for sequence prediction
- Training and evaluation scripts
- Interactive prediction interface
- Support for custom datasets

## Requirements

- Python 3.6+
- TensorFlow 2.x or PyTorch (depending on implementation)
- NumPy
- Pandas
- NLTK
- Matplotlib (for visualization)

## Installation

```bash
# Clone the repository
git clone https://github.com/himanshumishra2359/Next-Word-Prediction-Using-LSTM.git

# Navigate to the project directory
cd Next-Word-Prediction-Using-LSTM

# Install required packages
pip install -r requirements.txt
```

## Usage

### Data Preparation

```bash
python src/data_preparation.py --input_file path/to/your/text/file.txt
```

### Training the Model

```bash
python src/train.py --epochs 50 --batch_size 64
```

### Making Predictions

```bash
python src/predict.py --input "The quick brown fox"
```

## Model Architecture

The implementation uses an LSTM-based architecture with the following components:

1. Embedding layer to convert words to dense vectors
2. One or more LSTM layers to capture sequential patterns
3. Dropout layers to prevent overfitting
4. Dense layer with softmax activation for word prediction

## Performance

The model achieves the following performance metrics on the test dataset:

- Accuracy: ~30-40% (depending on dataset and hyperparameters)
- Perplexity: ~50-100

## Examples

Input: "The quick brown"
Predicted next word: "fox"

Input: "I want to"
Predicted next word: "go"

## Customization

You can customize the model by adjusting the following hyperparameters:

- Number of LSTM layers
- LSTM hidden units
- Dropout rate
- Embedding dimensions
- Sequence length
- Vocabulary size

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Special thanks to all contributors
- Inspired by various NLP research papers on sequence prediction
- Dataset sources (add specific sources if applicable)

## Contact

Himanshu Mishra - [@himanshumishra2359](https://github.com/himanshumishra2359)

Project Link: [https://github.com/himanshumishra2359/Next-Word-Prediction-Using-LSTM](https://github.com/himanshumishra2359/Next-Word-Prediction-Using-LSTM)
