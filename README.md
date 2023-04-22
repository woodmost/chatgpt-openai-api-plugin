# ChatGPT Plugin for OpenAI API

## Introduction

The ChatGPT Plugin for OpenAI API is a powerful tool that seamlessly integrates ChatGPT with the OpenAI API, enabling users to leverage the capabilities of OpenAI's language models in creative and interactive ways. This plugin acts as an intelligent API caller, allowing ChatGPT to generate text completions, engage in dynamic conversations, fine-tune language models, and explore various output settings, all through natural language interactions.

The plugin is designed to enhance ChatGPT's functionality by providing access to the OpenAI API, making it a valuable asset for developers, content creators, and businesses seeking to harness the power of language models for a wide range of use-cases inside the ChatGPT interface.
## Use-Cases

- **Text Generation:** Generate creative and coherent text based on user-defined prompts using OpenAI's GPT-3.5 Turbo and other models.
- **Conversational AI:** Build interactive chatbots and virtual assistants that can engage in natural language conversations with users.
- **Language Translation:** Translate text from one language to another with high accuracy.
- **Model Fine-Tuning:** Fine-tune language models to specialize in specific domains or industries, such as legal, medical, or finance.
- **Recursive Workflow:** Generate multiple completions recursively to explore different narrative paths or conversation branches.
- **Customization:** Experiment with different settings, such as temperature and top_p, to influence the diversity and creativity of generated text.

## Benefits

- **Versatility:** The plugin supports multiple modes of interaction, including text generation and conversational AI, through the OpenAI API.
- **Intelligent API Caller:** ChatGPT acts as an intelligent API caller, proactively calling the OpenAI API to perform actions based on user input.
- **Domain Specialization:** Fine-tune language models to meet specific requirements and improve performance in specialized domains.
- **Ease of Use:** The plugin provides a simple and intuitive interface for interacting with the OpenAI API through natural language commands.
- **Scalability:** The plugin is designed to handle a wide range of tasks and use-cases, making it suitable for both small and large-scale projects.

## Plugin Flow

1. **Activate the Plugin:** Users must manually activate the ChatGPT Plugin for OpenAI API within the ChatGPT UI.
2. **Begin a Conversation:** Users can start a conversation with ChatGPT and provide prompts or commands related to the OpenAI API functionality.
3. **API Invocation:** ChatGPT intelligently invokes the OpenAI API based on user input, performing actions such as text generation, model fine-tuning, or recursive completions.
4. **API Results:** ChatGPT incorporates the API results into its response to the user, providing coherent and relevant answers based on the API data.

## How to Use

To use the ChatGPT Plugin for OpenAI API, follow these steps:

1. Install and activate the ChatGPT Plugin for OpenAI API within the ChatGPT UI.
2. Start a conversation with ChatGPT and provide natural language prompts or commands related to the OpenAI API functionality.
3. ChatGPT will intelligently call the OpenAI API based on your input and provide responses that incorporate the API data.

## Examples of commands you can use:

- "Using the OpenAI API, generate a short poem about the moon with a temperature of 0.7."
- "Using the OpenAI API, translate the following English text to French: 'Hello, how are you?'" 
- "Using the OpenAI API, fine-tune a language model using the training data I provided to improve its creative writing ability."
- "Using the OpenAI API, generate multiple completions (n=3) for the prompt 'Once upon a time' with different temperature settings (0.5, 0.7, and 0.9)."
- "Using the OpenAI API, generate a Python code snippet that calculates the factorial of a given number, with a maximum token limit of 50."
- "Using the OpenAI API, create a short story about a robot who discovers its own consciousness, with a temperature of 0.8."
- "Using the OpenAI API, write a haiku about the changing seasons with a temperature of 0.6."
- "Using the OpenAI API, generate multiple versions (n=2) of a motivational quote with different levels of assertiveness (temperature 0.3 and 0.9)."
- "Using the OpenAI API, fine-tune a language model to generate creative recipes based on a list of ingredients, and provide me with a recipe using the fine-tuned model."
- "Using the OpenAI API, generate a dialogue between two characters discussing the meaning of life, with different levels of formality (top_p 0.7 and 0.95)."
- "Using the OpenAI API, create a code snippet that finds the longest palindrome in a given string, with a maximum token limit of 80."
- "Using the OpenAI API, generate a limerick about a mischievous cat with a temperature of 0.75."
- "Using the OpenAI API, write a short description of an imaginary planet with different levels of detail (n=2, temperature 0.5 and 0.9)."
- "Using the OpenAI API, generate multiple endings (n=3) for the story 'The princess was trapped in the tower by an evil witch' with different levels of optimism (temperature 0.4, 0.7, and 1.0)."

## Installation

To install and use the open-source `main.py` code for the ChatGPT Plugin for OpenAI API, follow the steps below:

1. Clone the GitHub repository:
```bash
git clone https://github.com/ruvnet/chatgpt-openai-api-plugin.git
```
2. Change to the cloned directory:
```
cd chatgpt-openai-api-plugin
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```
4. Set the OPENAI_API_KEY environment variable with your OpenAI API key:
```
export OPENAI_API_KEY=YOUR_API_KEY
```
5. Run the FastAPI application using the Uvicorn ASGI server:
```
uvicorn main:app --host 0.0.0.0 --port 8080
```
6. Update ai-plugin.json
```
./plugins/ai-plugin.json
```
7. Manifest is located http://localhost:8080/.well-known/ai-json.json and API Specification is located http://localhost:8080/openapi.json 

The ChatGPT Plugin for OpenAI API is now running and accessible at http://localhost:8080.

## Conclusion

The ChatGPT Plugin for OpenAI API is a valuable tool for users seeking to explore the capabilities of OpenAI's language models in creative and interactive

# Preview
![ChatGPT OpenAI API Plugin](https://github.com/ruvnet/chatgpt-openai-api-plugin/blob/main/chatgpt-openai-api-plugin.png?raw=true)

