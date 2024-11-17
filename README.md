# Conversational Model with Transformers

## Project Overview

This project implements a conversational model using Transformers. The model is trained on the Cornell Movie Dialogues Corpus to generate responses based on input sentences. The project is structured to download, process, and train on the dataset, and evaluate the performance of the model.

## Implemented Features

1. **Data Processing**:
    - Downloading and loading the dataset.
    - Creating pairs of questions and answers from the dataset.
    - Cleaning and tokenizing the data.
    - Filtering out sentences that are too long or too short.

2. **Model Training**:
    - Implementing a Transformer model for training.
    - Training the model using standard training and gradient accumulation techniques.
    - Evaluating the model's performance.

3. **Evaluation**:
    - Implementing greedy decoding and top-k sampling for generating responses.

## Python Libraries Used

- **torch**: For building and training the neural network.
- **regex**: For advanced regular expression operations.
- **os**: For file and directory operations.
- **pickle**: For saving and loading processed data.
- **rich**: For enhanced console output.
- **art**: For generating ASCII art.
- **matplotlib**: For plotting graphs.
- **numpy**: For numerical operations.


- **data/**: Contains the dataset files.
- **harkeerat_sawhney.py**: Main script for data processing, model training, and evaluation.
- **report/**: Contains LaTeX files and logs for generating the project report.

## How to Run the Project

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install the required libraries**:
    ```sh
    pip install torch regex rich art matplotlib numpy
    ```

3. **Run the main script**:
    ```sh
    python harkeerat_sawhney.py
    ```

## Detailed Description of Each Directory

- **data/**:
    - [`movie_conversations.txt`](command:_github.copilot.openSymbolFromReferences?%5B%22movie_conversations.txt%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Fharkeerat_sawhney.py%22%2C%22external%22%3A%22file%3A%2F%2F%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Fharkeerat_sawhney.py%22%2C%22path%22%3A%22%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Fharkeerat_sawhney.py%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A291%2C%22character%22%3A9%7D%7D%5D%5D "Go to definition"): Contains conversations between characters from the Cornell Movie Dialogues Corpus.

- **harkeerat_sawhney.py**:
    - Main script that includes functions for data processing, model training, and evaluation.

- **report/**:
    - [`harkeerat_sawhney.aux`](command:_github.copilot.openSymbolFromReferences?%5B%22harkeerat_sawhney.aux%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Freport%2Fharkeerat_sawhney.log%22%2C%22external%22%3A%22file%3A%2F%2F%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Freport%2Fharkeerat_sawhney.log%22%2C%22path%22%3A%22%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Freport%2Fharkeerat_sawhney.log%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A292%2C%22character%22%3A5%7D%7D%5D%5D "Go to definition"), [`harkeerat_sawhney.log`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Freport%2Fharkeerat_sawhney.log%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "/Users/hsawhney/Developer/GitRepositories/GitHub/conversational-model-with-transformers/report/harkeerat_sawhney.log"), [`harkeerat_sawhney.out`](command:_github.copilot.openSymbolFromReferences?%5B%22harkeerat_sawhney.out%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Freport%2Fharkeerat_sawhney.log%22%2C%22external%22%3A%22file%3A%2F%2F%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Freport%2Fharkeerat_sawhney.log%22%2C%22path%22%3A%22%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Freport%2Fharkeerat_sawhney.log%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A318%2C%22character%22%3A4%7D%7D%5D%5D "Go to definition"), [`harkeerat_sawhney.tex`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FUsers%2Fhsawhney%2FDeveloper%2FGitRepositories%2FGitHub%2Fconversational-model-with-transformers%2Freport%2Fharkeerat_sawhney.tex%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "/Users/hsawhney/Developer/GitRepositories/GitHub/conversational-model-with-transformers/report/harkeerat_sawhney.tex"): LaTeX files and logs for generating the project report.

## Conclusion

This project demonstrates the implementation of a conversational model using Transformers. It covers data processing, model training, and evaluation, providing a comprehensive approach to building a dialogue system.