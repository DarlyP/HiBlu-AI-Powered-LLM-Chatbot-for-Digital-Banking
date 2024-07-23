<img src="https://imgtr.ee/images/2024/07/17/7739fbd7d605b0d8b31194cdbd85fade.png" alt="7739fbd7d605b0d8b31194cdbd85fade.png" border="0" />

# HiBlu: LLM Chatbot for Blu (Digital Banking)

---

## Tools
[<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />](https://pandas.pydata.org/)
[<img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib" />](https://matplotlib.org/)
[<img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="Numpy" />](https://numpy.org/)
[<img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium" />](https://www.selenium.dev/)
[<img src="https://img.shields.io/badge/BeautifulSoup-430098?style=for-the-badge&logo=beautifulsoup&logoColor=white" alt="BeautifulSoup" />](https://www.crummy.com/software/BeautifulSoup/)
[<img src="https://img.shields.io/badge/LangChain-1A1A1A?style=for-the-badge" alt="LangChain" />](https://langchain.org/)
[<img src="https://img.shields.io/badge/OpenAI-FF6600?style=for-the-badge" alt="OpenAI" />](https://www.openai.com/)
[<img src="https://img.shields.io/badge/LLM-1A1A1A?style=for-the-badge" alt="LLM" />](https://en.wikipedia.org/wiki/Large_language_modeling)
[<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />](https://streamlit.io/)
[<img src="https://img.shields.io/badge/NoSQL-4DB33D?style=for-the-badge" alt="NoSQL" />](https://en.wikipedia.org/wiki/NoSQL)
[<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />](https://www.mongodb.com/)
[<img src="https://img.shields.io/badge/RAG-1A1A1A?style=for-the-badge" alt="RAG" />](https://en.wikipedia.org/wiki/Retrieval-augmented_generation)
[<img src="https://img.shields.io/badge/LLM%20fine--tuning-1A1A1A?style=for-the-badge" alt="LLM fine-tuning" />](https://huggingface.co/transformers/model_sharing.html#fine-tuning)

---


## Background

In today's competitive digital era, user satisfaction is crucial, especially in the banking sector. Prompt and accurate responses to user inquiries are essential for retaining customers. Generative AI technology, particularly Large Language Models (LLMs), has revolutionized user interactions through intelligent chatbots capable of providing information quickly and accurately. This not only enhances operational efficiency but also reduces costs.

---

## Introduction

HiBlu is a custom LLM chatbot model developed specifically for Blu, a digital banking service. Its primary objective is to deliver prompt and precise responses to inquiries from current and potential customers regarding Blu's services, enhancing response efficiency and user satisfaction. This initial prototype of the LLM chatbot aims to pave the way for broader implementation across all Blu services in the future. The documentation for this prototype will include a comparative analysis of modeling outcomes from the LLM RAG model, fine-tuned LLM model, and RAFT LLM model.

---

## Team Members

   - [Dito Wicaksana Prasetya](https://github.com/ditoowp) as a Data Engineer.
   - [Ahmad Naufal Budianto](https://naufalbudianto.framer.website/) as a Data Analyst + Visual Designer.
   - [Gieorgie Kharismatik Kosasih](https://github.com/GieorgieK) as a Data Scientist.
   - [Darly Guntur Darris Purba](https://github.com/DarlyP) as a Data Scientist.

---

## Data Source

The reference data for frequently asked questions and answers is based on data scraped from the [FAQ Blu](https://blubybcadigital.id/info/faq).

---

## RAG LLM Workflow

<center><img src="https://imgtr.ee/images/2024/07/11/ced345b5d0bf4ca7b4bfec39aa11cae9.png" alt="ced345b5d0bf4ca7b4bfec39aa11cae9.png" border="0" /></center>

---

## Fine Tuning LLM Workflow

<center><img src="https://imgtr.ee/images/2024/07/23/1b7d061e76097cd48201d7ce5e096e95.png" alt="1b7d061e76097cd48201d7ce5e096e95.png" border="0" /></center>


---

## RAFT LLM Workflow

<center><img src="https://imgtr.ee/images/2024/07/23/2c952693f912f7802d8ea9e49a02ea49.png" alt="2c952693f912f7802d8ea9e49a02ea49.png" border="0" /></center>

---

## File Explanation

| File | Explanation |
| --- | --- |
| `scraping.ipynb` | FAQ Web Scrapping Documentation |
| `hiblu_DAG.py` | DAG Documentation |
| `eda.ipynb` | EDA Documentation |
| `FAQ_GX.ipynb` | Great Expectation Validation Documentation |
| `rag_maverick_vecdb.ipynb` | Vector To MongoDB Documentation |
| `rag_maverick_query.ipynb` | RAG Model Documentation |
| `fine_tuning_maverick_query.ipynb` | Fine Tuning Model Documentation |
| `ragft_maverick_query.ipynb` | RAFT Model Documentation |
| `rag.py` | RAG Deployment Documentation |
| `finetuning.py` | Fine Tuning Documentation |
| `ragft.py` | RAFT Documentation |

---
## Link

* [Recording Video](https://drive.google.com/file/d/1AUtG-WBEMWUht799C6bXHG-T645zUv1c/view?usp=sharing)
* [Sample of Model Comparison](https://docs.google.com/spreadsheets/d/1C6bjPlXn09hHPvgiO1LU5f2JuIc1eKDk/edit?usp=sharing&ouid=108097674241546601906&rtpof=true&sd=true)
* [Presentation Deck](https://drive.google.com/file/d/1f4l9zLxRy-XMTeoh-R_E-1vX2rvMJmST/view?usp=sharing)

---

**Disclaimer**: 
- This notebook is created solely for learning and exploration purposes. There is no intention to offend or harm any party. All content and analysis presented are based on publicly available data online. I undertake this process to enhance my understanding of data analysis techniques and methodologies and hone my skills in implementing relevant algorithms and models within the context of data science learning. In conducting this analysis, I strive to maintain objectivity and professionalism in interpreting the existing data. Any conclusions or recommendations provided result from personal analysis and are not intended as professional advice in any specific capacity. I hope the information obtained from this notebook can be useful to anyone reading it to learn and develop data analysis skills.
- This notebook is written in Indonesian.

