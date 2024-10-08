# Language Translator

This project demonstrates the use of the `langchain` framework along with `langchain_groq` to interact with the Groq language model API. The application translates text from English to French using the `ChatGroq` model.

## Prerequisites

- Python 3.x
- Access to Groq API with an API key
- Required libraries:
  - `langchain`
  - `langchain_groq`
  - `langchain_core`
  - `python-dotenv` (for managing environment variables)

## Installation

1. Install required Python packages:

   ```bash
   pip install langchain langchain_groq langchain_core python-dotenv

## Set up the Groq API key:
1. Create a `.env` file in the root of your project directory.
2. Add the following line to the `.env` file:
   ```bash
   GROQ_API_KEY=your_groq_api_key_here

## Environment Variables
GROQ_API_KEY: Your API key for accessing the Groq model services. Make sure to keep this key confidential.

## License
This project is open-source. You can modify and distribute it according to the terms of your chosen license.
