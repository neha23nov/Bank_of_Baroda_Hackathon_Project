# Bank of Baroda Chatbot Project

## Project Overview

This project is developed by the team **Ctrl Freaks** for the Bank of Baroda Hackathon. Our goal is to create an intelligent chatbot that can assist customers with common queries and provide useful financial information.

## Features

- **Greeting and Farewell Responses**: The chatbot can handle greetings and farewells, providing a friendly interaction experience.
- **Query Responses**: The chatbot can answer questions about the existence of God, current inflation rates, income levels, and more.
- **Financial Assistance**: The chatbot offers responses to various financial-related questions, including savings management, financial goals, risk attitudes, and more.

## Technologies Used

- **Python**: The core programming language used for the chatbot development.
- **TensorFlow**: For building and training the neural network model.
- **Natural Language Toolkit (nltk)**: For text processing and tokenization.
- **Keras**: For building and saving the model.
- **JSON**: For handling the intents and responses.
- **Pickle**: For saving and loading processed data.

## Project Structure

- **intents.json**: Contains the intents, patterns, responses, and context of the chatbot.
- **chatbot_model.h5**: The trained model file.
- **words.pkl**: Pickle file for storing the processed words.
- **classes.pkl**: Pickle file for storing the processed classes.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/bob-chatbot.git
    cd bob-chatbot
    ```

2. Install the required dependencies:
    ```bash
    pip install numpy nltk tensorflow keras
    ```

3. Download NLTK data:
    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('wordnet')
    ```

4. Run the chatbot:
    ```bash
    python chatbot.py
    ```

## What We Have Done So Far

- **Data Preparation**: Collected and processed the data, tokenized the patterns, and created training datasets.
- **Model Training**: Developed and trained a neural network model using TensorFlow and Keras.
- **Response Handling**: Implemented functions to predict the class of the input sentence and retrieve appropriate responses.

## Next Steps

- **Improve Model Accuracy**: Enhance the model by fine-tuning hyperparameters and expanding the dataset.
- **Add More Intents**: Include more intents to cover a broader range of customer queries.
- **Integrate with Bank Systems**: Connect the chatbot to Bank of Baroda's systems for real-time data retrieval and transactions.
- **Deploy the Chatbot**: Host the chatbot on a server and create a user-friendly interface for customers.

## Team

 <table>
  <p align="center">
  <tr>
    <td align="center"><a href="https://github.com/ananyag309"><img src="https://avatars.githubusercontent.com/u/145869907?v=4" width="120px;" alt=""/><br/><sub><b>Ananya Gupta</b></sub></a></td>
    <td align="center"><a href="https://github.com/neha23nov"><img src="https://avatars.githubusercontent.com/u/145911161?v=4" width="120px;" alt=""/><br/><sub><b>Neha Saini</b></sub></a></td>
    <td align="center"><a href="https://github.com/Peehu1308"><img src="https://avatars.githubusercontent.com/u/145141126?v=4" width="120px;" alt=""/><br/><sub><b>Peehu Mishra</b></sub></a></td>
    <td align="center"><a href="https://github.com/Aditijainnn"><img src="https://avatars.githubusercontent.com/u/144632601?v=4" width="120px;" alt=""/><br/><sub><b>Aditi Jain</b></sub></a></td>
 </tr>

   </p>
 </table>
## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
