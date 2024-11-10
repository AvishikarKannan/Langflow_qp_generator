Question Paper Generator - No Code Langflow Project<br>
This repository contains a no-code Langflow project designed to generate question papers using a Retrieval-Augmented Generation (RAG) model. This project utilizes the Gemini Large Language Model (LLM) along with Mistral embeddings and vector database storage via DataStax AstraDB.<br>

Project Overview<br>
The Question Paper Generator is an entry-level implementation of a RAG model for generating question papers. The model takes previously generated question papers as input, enabling it to generate customized and coherent question papers for educational purposes.<br>

Key Components<br>
Gemini LLM: The core language model responsible for understanding input and generating meaningful questions.<br>
Mistral Embeddings: Embeddings used to capture semantic information, enhancing the relevance of generated questions.<br>
DataStax AstraDB: Vector database for efficient storage and retrieval, enabling fast and scalable data processing.<br><br>
Features<br>
No-Code Interface: Built on Langflow for a fully no-code setup, ideal for non-developers and educators.<br>
Reusable Input: Accepts previously generated question papers as input, ensuring contextual relevance in each generated question.<br>
Efficient Question Generation: Powered by RAG, this tool combines retrieval and generative capabilities for accurate question paper generation.<br>

Getting Started<br>

Set up dependencies:<br>

Ensure access to Langflow, Gemini, Mistral, and DataStax AstraDB (sign up if necessary).<br>
Run the project using Langflow:<br>

Use the provided Langflow configurations to set up and run the no-code interface.<br><br>
Usage<br>
Input a previously generated question paper into the system.<br>
Initiate the question paper generation process.<br>
The model retrieves relevant content and generates new questions based on the input.<br>
