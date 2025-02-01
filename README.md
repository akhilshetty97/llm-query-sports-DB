**Strive Sports Analytics Hub:** 

'Strive Sports Analytics Hub' is an intelligent, Retrieval-Augmented Generation (RAG)-powered, SQL-driven system designed to answer questions by querying a MySQL database. Built with Langchain, Google Generative AI, and HuggingFace embeddings, this application retrieves real-time answers by converting user questions into precise SQL queries and executing them efficiently.

**Key Features:**    

RAG-Powered SQL Query Generation & Execution
Enhances query accuracy by retrieving relevant examples from a vector database before generating SQL queries.
The Large Language Model (LLM) not only generates SQL queries from user questions but also executes them to fetch real-time answers.

Database Integration
Directly connects to a MySQL database to run SQL queries and retrieve precise results.

Custom Query Execution
Optimized SQL query generation ensures smooth database interactions while preventing execution errors.

Few-Shot Learning with Vector Search
Implements semantic similarity to select relevant examples using HuggingFace embeddings and Chroma vector store before generating SQL queries.

Real-Time Answering
Instantly returns answers to sports-related queries such as inventory counts, pricing, and product availability.

**Technologies Used:**  
Retrieval-Augmented Generation (RAG): Enhances query generation by incorporating retrieved examples for better SQL formulation.
Langchain: Orchestrates the LLM pipeline for SQL query generation and execution.
ChatGoogleGenerativeAI: Integrated with Google Gemini Pro to generate and run SQL queries.
HuggingFace Embeddings: Uses sentence-transformers/all-MiniLM-L6-v2 for embedding-based similarity matching.
Chroma Vector Store: Stores vectorized few-shot learning examples for enhanced retrieval before SQL query generation.
MySQL: Backend database for storing sports-related data (e.g., products, stock, and prices).    

**How It Works:**    
Step 1: The user inputs a question related to the products of the company (e.g., "How many Adidas products are left in stock?").  
Step 2: The system retrieves similar past queries from the Chroma vector store using HuggingFace embeddings.
Step 3: The LLM, enhanced with retrieved examples, generates a precise SQL query using Langchain and Google Gemini Pro. 
Step 4: The generated SQL query is executed on the MySQL database. 
Step 5: The query results are processed, and the final answer is displayed to the user.
The RAG approach ensures that the most relevant examples are retrieved, improving SQL accuracy and reducing errors.

![image](https://github.com/user-attachments/assets/40de2d7d-0f2c-40a4-9aac-c0283d3dd90f)


![image](https://github.com/user-attachments/assets/ccab67fa-cdc1-4e92-a82a-9585ed638125)





Information about the products at Strive Sports.  

<img width="797" alt="image" src="https://github.com/user-attachments/assets/0817b4ac-7b3d-441b-b8af-662b28a41e65">

Information about the product discounts.  
<img width="263" alt="image" src="https://github.com/user-attachments/assets/6abb640e-7be3-4ed6-82e6-0d79ffccb3d3">



