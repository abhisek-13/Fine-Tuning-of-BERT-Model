# Fine-Tuning-of-BERT-Model

## Overview
This project demonstrates how to fine-tune the BERT model using a custom dataset. The model is trained on spam-ham data from Kaggle to classify messages as spam or ham. This project was created while learning about transformers, large language models (LLM), and generative AI. Users can fine-tune this model with other sentiment data to customize predictions. The repository contains a single Jupyter Notebook (ipynb) file with the complete code for preprocessing, model training, and prediction.

## Features
- **Spam-Ham Classification:** Predicts whether a message is spam or ham.
- **BERT Fine-Tuning:** Uses the BERT model, fine-tuned on custom data.
- **Customizable:** Users can fine-tune the model with their dataset for specific sentiment analysis tasks.
- **Reference Notebook:** Includes a Jupyter Notebook with all the necessary code for preprocessing, training, and prediction.

## Technologies Used
- **Python:** Programming language used for model development.
- **TensorFlow:** Machine learning framework used for building and training the BERT model.
- **Transformers Library:** Used for working with the BERT model.
- **Jupyter Notebook:** Interactive notebook used for code development and demonstration.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/abhisek-13/Fine-Tuning-of-BERT-Model.git
    cd Fine-Tuning-of-BERT-Model
    ```
2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook bert_spam_ham_classification.ipynb
    ```
2. Follow the steps in the notebook to preprocess the data and train the model.
3. Fine-tune the model with your dataset by replacing the spam-ham data with other sentiment data.
4. Use the trained model to make spam-ham predictions.

## Project Structure
- `bert_spam_ham_classification.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and prediction.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For any questions or feedback, please contact [abhisekmaharana9861@gmail.com](abhisekmaharana9861@gmail.com).
