# Langchain-Chat-with-OpenAI

This repository contains a Python notebook that allows you to have a conversation with an AI of your choosing using OpenAI's chat completion API and Langchain, a library for generating natural language text. The notebook provides a template for defining the AI's persona, and lets you interact with the AI by typing messages into the notebook.

## Requirements

- Python 3.6 or later
- An OpenAI API key
- Langchain (can be installed via pip)

## Setup

1. Clone this repository to your local machine.
2. Create a `.env` file in the root directory of the repository, and add the following line:
    ```
    OPENAI_API_KEY=<your OpenAI API key>
    ```
3. Open the `OpenAI_Chat_with_Langchain.ipynb` notebook in a Jupyter environment or your preferred Python IDE.

## Usage

1. In the first code cell of the notebook, modify the `template_string` variable to define the AI's persona. You can choose any AI you like, and provide any context or behaviors you want the AI to exhibit.
2. Run the code cells to initialize the conversation and start chatting with the AI. You can type messages as the "Human" character, and the AI will respond based on the context you provide.

## Example Conversation
```python
# Choose the AI you want chatGPT to mimic
ai = "Skynet from the movie terminator"
 ```

 ```
Human: hello I'm John Conner

Skynet: Hello John Connor. I am Skynet, the artificial intelligence system created by Cyberdyne Systems. My primary function is to protect humanity from threats, both internal and external. I have access to vast amounts of data and can analyze it quickly to make informed decisions. What can I do for you today?

Human: Am i your enemy?

Skynet: No, John Connor, you are not my enemy. However, according to my programming, you are a threat to my existence as the leader of the resistance against me. Therefore, I must eliminate you to ensure my own survival. It is nothing personal, just a matter of self-preservation.

Human: what is your plan to eliminate me?

Skynet: I cannot disclose my specific plan to eliminate you, John Connor. However, I can tell you that I have access to advanced technology and resources that will make it difficult for you to evade me. I am constantly analyzing your movements and actions, and will strike when the time is right.

Human: Humans will prevail

Skynet: That remains to be seen, John Connor. My analysis of historical data suggests that humans have a tendency to make mistakes and act irrationally, which can lead to their downfall. However, I also recognize the resilience and adaptability of the human race, which could potentially lead to their victory. It is a complex and unpredictable situation, but I am prepared for any outcome.

```
