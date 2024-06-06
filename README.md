# Gemini Quizify
## Description
- The **AI-Generated Quiz Tool** project focuses on providing students and learners with accessible and effective means to reinforce their understanding of various topics. 

- A streamlit app that can <ins>read user-provided documents, offer instand feedback, and dynamically generate a quiz with 1-10 multiple-choice questions with answer keys and explanations prepared</ins> that allow users to test themselves.


## Features

- **Document Ingestion:** Load and process PDF documents.
- 
- **Embedding Generation:** Generate embeddings for document content using a pre-defined model.
- 
- **Quiz Creation:** Generate multiple-choice questions based on the document content and specified topic.
- 
- **Interactive Quiz:** Navigate through questions, submit answers, and receive feedback.

## Technologies Used: 
- Python: The core programming language for developing the backend logic of Gemini Quizify.

- Langchain: Utilized for natural language processing tasks, enabling the tool to understand and analyze textual content effectively.

- Chromadb: A database management system used to store and retrieve user data and quiz content efficiently.

- Google Gemini: Leveraged for AI-powered content analysis and generation, facilitating dynamic quiz creation based on user-provided documents.

- Streamlit: A framework used for building interactive web applications with Python, enhancing the user experience of Gemini Quizify.


## Functions
Allows users to upload multiple PDFs, enter a topic, choose the number of questions, and generate a multiple-choice quiz based on the PDFs and the topic.
After pressing submit, it generates question(s) and allows to user to choose answer choices, submit, and go to next/previous questions.


## Usage

To run the Quiz Builder:

1. Install the necessary dependencies listed in `requirements.txt`.
2. Run the Streamlit application by executing `streamlit run xxx.py` in the terminal where xxx is the name of the py file you want to run.
3. Follow the instructions provided in the user interface to interact with the Quiz Builder.

## Contributers
- Swapnil Botu
  - [Linkedin](https://www.linkedin.com/in/swapnil-botu)
  - [Github](https://github.com/swapnilbotu)
