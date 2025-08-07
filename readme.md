<img src="./img/gif v1.gif" min-width="400px" max-width="400px" width="400px" align="right" alt="Computer iuriCode">
<p>
<div align="right">
<a href="./readme.md"> <img src="./img/LogoUK.png" alt="Logo UK" width="30"/></a><a href="./leiame.md"> <img src="./img/logoBrazil.png" alt="Logo Brasil" width="30"/> </a>
</div>
 <H1><b> Victor Sérgio Silva Barros </b> </H1>
</p>

<div align="top" style="display: flex; justify-content: space-between;">
  <img src="./img/artificial-intelligence.png" alt="Logo Inteligência Artificial" width="80"/>
  <img src="./img/pineconeLog.png" alt="Logo pinecone" width="80"/>
  <img src="./img/logoN8N.png" alt="Logo N8N" width="80"/>
</div>

Generate accurate and contextualized answers to technical questions.
Automate repetitive tasks of searching and analyzing information.

## Introduction

This project aims to integrate artificial intelligence and automation to access complex information and transform it into useful knowledge. In this project, I used the RAG (Retrieval Augmented Generation) technique. An Agent was created in N8N that acts as a true personalized technical expert in any area!

## Project Structure

1. **Knowledge Base Creation**:
   - Efficiently consult and extract data from various sources.
   - Every minute, the agent checks if a new file has been added to a specific Google Drive folder.
   - Google Gemini embeddings are numerical representations of text, image, or video data that capture the meaning and semantic relationships between them. These numerical vectors allow machine learning models, especially generative AI, to process and produce language more effectively, identifying complex patterns and semantic relationships specific to a given content.
   - Pinecone is a managed vector database in the cloud, designed to optimize similarity search for data in artificial intelligence applications. It allows developers to easily integrate vector search into their applications, such as semantic search, recommendation systems, and AI-driven data analysis.
   ![N8N Flow](./img/RAG-Vicssb.png)
   [Download N8N Flow](rag_vicssb.json)

2. **RAG AI Agent**:
   - The RAG agent does the following: Retrieval: the user's request is used to query an external knowledge database, such as a vector repository, keyword search, or SQL database. The goal is to obtain the supporting data needed for the LLM's response.
   - Hyperparameter tuning.
   ![N8N Flow](./img/Vic_Agent.png)
   [Download N8N Flow](Vic_Agent.json)

## Requirements

- Python 3.7 or higher.
- TensorFlow or PyTorch framework for AI model development and training.
- Image annotation tool (example: LabelImg) to prepare input data.
- Google Drive account for storage and automatic updating of knowledge files.
- Pinecone for managing and searching embedding vectors.
- Gemini API for generating text, image, or video embeddings.
- N8N for workflow automation and agent integration.

## Usage in N8N Chat
![N8N Chat](./img/chat1.png)

## Usage in Web Chat
![Web Chat](./img/chat2.png)


## License

This project is licensed under the MIT License.

## Version control

1.0.0


## Author

**Victor Sérgio Silva Barros**:


<p align="left">
 <a href="mailto:vicssb@gmail.com" alt="Gmail" target = "_blank">
 <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=mailto:vicssb@gmail.com" /></a>

 <a href="https://www.linkedin.com/in/victor-sergio-silva-barros/" alt="Linkedin" target = "_blank">
 <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/victor-sergio-silva-barros/" /></a>

 <a href="https://wa.me/+5512981328278" alt="WhatsApp" target = "_blank">
 <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white&link=https://wa.me/+5512987085327"/></a>

 </p>

<p>Please follow github and join us!
Thanks for visiting and happy coding!</p>