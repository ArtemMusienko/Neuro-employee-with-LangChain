![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)![LangChain](https://img.shields.io/badge/langchain-%231C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white)

![enter image description here](https://cdn.prod.website-files.com/64009032676f24f376f002fc/668ec547def06a3e6bcf37ee_langchain_logo.webp)

## Neuro-employee with LangChain

[![ru](https://img.shields.io/badge/README_на_русском-2A2C39?style=for-the-badge&logo=github&logoColor=white)](README.ru.md)

> First of all, I recommend reading the comment about
> creating documents and organizing their structure.

The main technology in this repository is **LangChain**, an open-source framework and library of software tools for creating applications based on large language models (LLM). It helps to integrate LLM with external services and data sources, allowing you to create complex multi-step workflows.

 To use this neural assistant, you will need to have your **OpenAI API Key** . Since I use the key through the **VseGPT** service, I add the following variable in the code:

`base_url = "https://api.vsegpt.ru/v1"`, 

but if you have the key in a different way, you should remove this variable. 

The Neuroemployee is based on the **RAG (Retrieval Augmented Generation) technology**, which allows you to search for information in external knowledge bases, such as documents, reference books, and corporate instructions. As a knowledge base, I use a Google document that I created.  

I also use **Gradio** to describe the interface of the neuro-employee.  This is a convenient and quick way to deploy your code into a basic interface and share it with your friends using a temporary link :)

> I recommend using a **T4** or more powerful graphics accelerator to run the code.