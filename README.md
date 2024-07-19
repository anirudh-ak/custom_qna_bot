# custom_qna_bot
RAG based custom chatbot that answers questions related to the T20 Cricket World Cup 2024

# ICC T20 Cricket World Cup 2024 Chatbot

## Project Overview
This project aims to build a chatbot that can answer questions about the ICC T20 Cricket World Cup 2024 using the GPT-3.5 Turbo model. Since this event is very recent, the model's training data does not cover it, making this project ideal for showcasing the capabilities of Retrieval Augmented Generation (RAG).

## Dataset
We use the Wikipedia page about the ICC T20 Cricket World Cup 2024. This dataset provides comprehensive and up-to-date information, ensuring that the chatbot can deliver accurate and relevant responses.

## Methodology
To enhance the chatbot's question-answering capability, we employ the Retrieval Augmented Generation (RAG) technique. This approach involves supplementing the model's prompt with contextual information from the dataset, which enables the model to generate more precise answers.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/anirudh-ak/custom_qna_bot.git
    cd custom_qna_bot
    ```

2. Create a virtual environment and install dependencies:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3. Set up your OpenAI API key:
    ```sh
    export OPENAI_API_KEY='your_openai_api_key'
    ```


You can enter questions related to the ICC T20 Cricket World Cup 2024, and the chatbot will provide accurate answers using the information from the dataset.

File Structure

custom_chatbot.ipynb: Notebook containing all steps to extract, save, embed data and run this bot
requirements.txt: List of dependencies required for the project.

Acknowledgements
OpenAI for providing the GPT-3.5 Turbo model.
Wikipedia for the dataset.


