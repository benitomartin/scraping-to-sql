# Web Scraping to PDF

Justicio is a Question/Answering Assistant that generates answers from user questions about the official state gazette of Spain: Boletín Oficial del Estado (BOE).

At this moment we are running a user-free service: [Justicio](https://justicio.es/)

All BOE articles are embedded in vectors and stored in a vector database. When a question is asked, the question is embedded in the same latent space and the most relevant text is retrieved from the vector database by performing a query using the embedded question. The retrieved pieces of text are then sent to the LLM to construct an answer.

## Tech Stack

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## Contributions

Web scraping of the municipal regulations of La Coruña and Oviedo and saving the file in an SQL dump for further usage in the vector database.
