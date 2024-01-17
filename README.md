# Complete Langchain GEN AI Pack
This is a complete Langchain GEN AI pack with 6 end To end LLM projects with OPENAI, LLAMA2, Gemini Pro, Gemini Pro Vision.
This pack contains a series of projects developed as part of the LangChain initiative, demonstrating various applications and use cases leveraging language models and generative AI. Each project is designed to showcase the capabilities of different technologies and platforms.                        
        
Requirements:
Python 3.8 or higher(python 3.10 for LLM5 and LLM6 files)
Streamlit
langchain library
OpenAI API key
Hugging Face API token
LLaMA 2 model file
Pinecone API key
Google's GenerativeAI API Key
Pillow (Python Imaging Library)


Projects Overview:

1. LLM1-Basics of LLM

    1.1. LLM1-Basics of LLM 
This project introduces the LangChain library and demonstrates how to use it to interact with OpenAI and Hugging Face models. The examples cover querying information, chaining models for sequential tasks, and using prompt templates.
     
      Pre-requisites:
      Set your OpenAI API key and Hugging Face API token as environment variables:
      OPEN_API_KEY='your_openai_api_key'
      HUGGINGFACEHUB_API_TOKEN='your_huggingface_api_token'

   1.2. LangChaiChatmodels with ChatOpenAI
Project LangChain 02 showcases the integration of ChatOpenAI for interactive conversations. It involves setting up ChatOpenAI, providing system and human messages, and obtaining AI-generated responses.
   
      Pre-requisites: 
      Set up your OpenAI API key as an environment variable:
      OPEN_API_KEY='your-api-key-here'     

2. LLM2-Querying PDF with AstraDB
This project demonstrates a question-answering demo using Astra DB and LangChain, powered by Vector Search. It involves setting up a Serverless Cassandra with Vector Search on Astra DB and querying PDF documents.
      
      Pre-requisites: 
      You need a Serverless Cassandra with Vector Search database on ASTRA DB to run this demo.You should get a DB Token with role Database Administrator 
      and copy your Database ID.You also need an OpenAI API Key.  

3. LLM3-Blog Generation using LLAMA 2
A Streamlit app to generate blog content using the LLama 2 model. It has a user-friendly Streamlit interface for blog generation and supports customizable inputs for blog topic, word count, and style.
   
      Pre-requisites: 
      Download and place the LLaMA 2 model file in the appropriate directory. Ensure the path to the model file is correctly set in the script.

   ### Image
   <img width="789" alt="Screenshot 2024-01-17 220306" src="https://github.com/VarsaGupta/Complete-Langchain-Series/assets/125072517/51a30008-ef9f-414c-965d-d676eeddeaf0"> 
  

4. LLM4-LLM Generic App using Pinecone VectorDB
This project is a Python-based application designed for processing and querying PDF documents. It leverages OpenAI's GPT models and Pinecone's vector search database to efficiently handle and search text within large PDF files. The application chunks and vectorizes text, allowing for advanced text searches using natural language queries, enhancing the accessibility and utility of information within PDF documents.

      Pre-requisites: 
      Set up your environment variables:
      Create a .env file in the project root. 
      Add your OpenAI and Pinecone API keys:
      OPENAI_API_KEY=your_openai_api_key
      PINECONE_API_KEY=your_pinecone_api_key
     

5. LLM5-Gemini Pro LLM Application
This Streamlit application serves as a Q&A interface, integrating with Google's GenerativeAI Gemini Pro model. It configures the environment, establishes a Streamlit interface, and facilitates communication with the Gemini Pro model through user inputs. Users can input questions, and the app displays responses from the AI model. It maintains a session-based chat history, showing an ongoing conversation between the user and the AI.

      Pre-requisites:     
      Set up your environment variables:
      Create a .env file in the project root.
      Add your Google GenerativeAI API key:
      GOOGLE_API_KEY=your_google_generativeai_api_key

   ### Image
   <img width="837" alt="Screenshot 2024-01-17 215403" src="https://github.com/VarsaGupta/Complete-Langchain-Series/assets/125072517/d2d08d3f-6a6d-423c-8ec9-4325643c37d6">


7. LLM6-Invoice Extractor using Gemini Pro Vision
A Streamlit web application titled "MultiLanguage Invoice Extractor" leveraging Google's Generative AI Gemini Pro Vision model to analyze and extract data from uploaded invoice images. Users can upload invoice images, input prompts, and get AI-generated insights.
   
      Pre-requisites: 
      Set up your environment variables:
      Create a .env file in the project root.
      Add your Google GenerativeAI API key:
      GOOGLE_API_KEY=your_google_generativeai_api_key

   ### Image
   <img width="368" alt="Screenshot 2024-01-17 215837" src="https://github.com/VarsaGupta/Complete-Langchain-Series/assets/125072517/993b3911-5b03-4625-851d-877271f58acf">
 
   
Note:
To run the LLM5 and LLM6 file (i.e. '---.py' python files),follow the following steps:
1. Create a conda environment with python version 3.10.
   conda create --name myvenv python=3.10 
2. Activate the conda environment.
   conda activate myvenv
3. Install all the dependencies.
   pip install -r requirements.txt
4. Run the file.
   streamlit run 'file_name.py' 

    





