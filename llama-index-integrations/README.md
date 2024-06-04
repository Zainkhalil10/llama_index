# LlamaIndex Integrations
**Installations:**

-Olama 

-GitHub

-Visual Studio/Notebook

-LlamIndex

**Process:**

-Install the library:  pip install llama-index

-First offers data connectors to ingest your existing data sources and data formats (APIs, PDFs, docs, SQL, etc.). This explains the usage of elastic search as a database.

-can easily connect the GitHub and LangChain.

-Then you can use the Visual Studio/notebook for the programming.

**What does our project do?**

As our primary objective is to create a chatbot model that can read and interpret the data from all the PDF, excel(still in progress) and word documents that would be provided to it from the manufacturing department. The primary objective of this project is to allow the chatbot to respond to highly specific questions related to the company's products without getting puzzled quickly and effecienty.

Why have we developed this?

By this far the OpenAi is still falling a little behind on this and have not been upto the mark like ChatGPT can’t handle more than 4000 tokens, which is by far not enough for the vast amount of data stored by our business partner. Our model needs to be able to handle hundreds of pages of PDF data.


**ELASTIC SEARCH:**

It isn't sort of traditional database like you can't store all sort of data into it. It's basically used to store strings etc at the very beginning and we are using it to store vector embeddings (a vector embedding, often just called an embedding, is a numerical representation of the semantics, or meaning of your text. Two pieces of text with similar meanings will have mathematically similar embeddings, even if the actual text is quite different). So in this database it will store the PDF files that will contain the detailed information about a product and while responding to a customer's query, our system will go through all the PDF files and will compare the results and will respond to the user's query for the better understanding.

**LlamaIndex:**

LlamaIndex is a data framework specifically designed to work with large language models, including Ollama. It makes the data structured. In our project it will work in a way that we will index the data first and then we will pass and scan the PDF files and then it will go through the files and locate text that is related to the meaning of the query terms rather than simple keyword matching this will give increase the ratio of getting the correct answer.

**Links:**

Olama:
https://www.ollama.com/

LlamaIndex:
https://www.llamaindex.ai/

Building LLM applications with LlamaIndex involves building with LlamaIndex

[core](https://github.com/run-llama/llama_index/tree/main/llama-index-core) as well as with the LlamaIndex Integrations required for your application.Integrations are categorized by type and each are their own Python package.
