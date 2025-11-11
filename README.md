![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)

![enter image description here](https://cdn.prod.website-files.com/64009032676f24f376f002fc/668ec547def06a3e6bcf37ee_langchain_logo.webp)

## Neuro-employee with LangChain

> В первую очередь рекомендую ознакомиться с комментарием по поводу
> создания документов и организации их структуры.

Для использования этого нейро-сотрудника вам потребуется иметь свой **OpenAI API Key**. Так как я использую ключ через сервис **VseGPT**, то я добавляю в коде такую переменную:

`base_url = "https://api.vsegpt.ru/v1"`, 

но если вы владеете ключом иным способом, то тогда стоит убрать эту переменную. 

Нейросотрудник реализован по принципу работы технологии **RAG (Retrieval Augmented Generation)**. В качестве базы знаний используется созданные мной Google документ. 

Также я использую **Gradio** для описание интерфейса нейро-сотрудника. Это удобный и быстрый способ развернуть свой код в базовый интерфейс и поделиться им с друзьями с помощью временной ссылки :)

> Для запуска кода рекомендую использовать графический ускоритель T4 в Google Colab.
