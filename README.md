# Marathi Word Sense Disambiguation using Elmo+CNN

This repository contains a project for Marathi Word Sense Disambiguation (WSD) using the Elmo+CNN model. The goal of this project is to disambiguate words in a Marathi sentence by accurately part-of-speech (POS) tagging each word. The developed Elmo+CNN model achieves an accuracy of 86%, making it the world's first model for Marathi WSD and aiding millions in better understanding the Marathi language.

## Dataset
The project utilizes a Marathi language dataset specifically curated for Word Sense Disambiguation. The dataset consists of annotated Marathi sentences where each word is labeled with its corresponding part-of-speech tag.

## Workflow
The project workflow can be summarized as follows:

1. Data Preprocessing: The Marathi dataset is preprocessed to clean and tokenize the text. This involves removing any special characters, normalizing the text, and splitting the sentences into individual words.

2. Embedding Generation: Word embeddings are generated using the Elmo (Embeddings from Language Models) approach. Elmo captures contextual information by leveraging deep bidirectional language models, resulting in rich and meaningful word representations.

3. Model Development: The Elmo+CNN model is developed for POS tagging. The Elmo embeddings are fed into a CNN (Convolutional Neural Network) architecture, which captures local dependencies and context information to accurately predict the POS tags.

4. Training: The Elmo+CNN model is trained on the preprocessed Marathi dataset. During training, the model learns to disambiguate the words by predicting their corresponding POS tags based on the provided labeled examples.

5. Evaluation: The trained model's performance is evaluated using suitable metrics such as accuracy, precision, recall, and F1 score. These metrics quantify the model's ability to accurately assign the correct POS tags to words in Marathi sentences.

6. Deployment: The trained Elmo+CNN model can be deployed to disambiguate words in Marathi sentences in real-time. By accurately POS tagging the words, the model aids in improving the understanding and interpretation of Marathi language text for millions of users.

## Usage
To utilize the Marathi Word Sense Disambiguation model using Elmo+CNN, follow these steps:

1. Set up the environment by installing the necessary dependencies listed in the `requirements.txt` file.

2. Download or clone the repository to your local machine.

3. Obtain the Marathi WSD dataset used for training and evaluation.

4. Preprocess the dataset by cleaning the text, tokenizing the sentences, and generating word embeddings using the Elmo approach.

5. Open the provided Jupyter Notebook file that contains the step-by-step implementation of the Marathi Word Sense Disambiguation using Elmo+CNN.

6. Follow the instructions in the notebook to develop the Elmo+CNN model, train it on the preprocessed Marathi dataset, evaluate its performance, and deploy it for real-time word sense disambiguation.

7. The notebook includes code snippets and explanations for each step to facilitate understanding and execution. Make sure to run each cell sequentially to ensure correct execution.

## Results
After training and evaluation, the Elmo+CNN model achieves an accuracy of 86% on the Marathi WSD task. This indicates the model's ability to accurately POS tag words in Marathi sentences and disambiguate their sense.

## License
The code in this repository is licensed under the [MIT License](LICENSE).

## Acknowledgments
- The creators of the Marathi WSD dataset for providing the labeled Marathi sentences and POS tags.
- The developers and maintainers of the Elmo and CNN architectures for natural language processing.
- The Marathi language

 community for contributing to language understanding and research.
