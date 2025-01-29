# Welcome!

Welcome to my portfolio! Below is a collection of my publications and contributions, showcasing my expertise and work in data science, machine learning, history, and critical analysis.

## Publications

- [Biased PromptORE: Enhancing Relation Extraction in Gendered Languages and Complex Texts – The Case of Spanish Documents from the XVI Century](https://arxiv.org/abs/2406.00027)  
  *Hèctor López Hidalgo, Michel Boeglin, David Kahn, Josiane Mothe, Diego Ortiz, David Panzoli*  
  Semantic relations among entities are a widely accepted method for relation extraction. PromptORE (Prompt-based Open Relation Extraction) was designed to improve relation extraction with Large Language Models on generalistic documents. This study introduces an adaptation of PromptORE to extract relations from specialized documents, particularly digital transcripts of trials from the Spanish Inquisition.
  Published in [ECIR 2025](https://ecir2025.eu/accepted-papers/)

- [Análisis del discurso y pensamiento crítico](https://egregius.es/catalogo/analisis-del-discurso-y-pensamiento-critico/)  
  Coauthor of the book.  
  This article examines the sense of “being young” in two youth discussion groups from different time periods in Córdoba city (Spain). The analysis highlights how leisure activities, such as role-playing games, have evolved over 20 years and their impact on youth identity and communication through media interfaces.

- [Uso del teléfono móvil, juventud y familia](https://egregius.es/catalogo/uso-del-telefono-movil-juventud-y-familia/)  
  Coauthor. I wrote a chapter titled *"Circuitos de ocio juveniles mediados: un caso de prácticas lúdicas y ecología mediática en Córdoba capital (2008-2017)"*.  
  This chapter explores mediated youth leisure circuits, focusing on playful practices and media ecology in Córdoba from 2008 to 2017.

- [Periodismo narrativo y nuevos escenarios de comunicación](https://egregius.es/catalogo/periodismo-narrativo-y-nuevos-escenarios-de-comunicacion/)  
  Coauthor. I wrote a chapter titled *"Historia, narrativa y discurso: el extraño viaje como imagen del franquismo en la vida cotidiana."*  
  This chapter examines the intersection of history, narrative, and discourse, analyzing how the concept of "the strange journey" reflects life under Francoism in Spain.

---

## Github Repositiories

- [pdf-extractor-agent](https://github.com/HlhDataScience/pdf-extractor-agent)
  pdf-extractor agent is an approach on how we can leverage LLM engines like `OpenAI` and generative IA app development
 frameworks to create Information Retrieval Systems. In this case we focused on pdf extraction of research documents.
 **Our app extract meaningful insights from the pdf documents and format then into a json friendly format for display to
 the user**. **It preserves the raw text extracted with its original estructure**. Finally, **it uploads the data extracted 
 to a `BigQuery` table**, once the json google credentials are given.The table is created, if it is not already present.
 Therefore, **the app is completely compatible either you use it locally, deployed on `Streamlit` or pushed as a `Docker Image` to 
 `Google Run`.**

- [mobile-use-detection](https://github.com/HlhDataScience/mobile-use-detection)
  This repository demonstrates the implementation of efficient MLOps workflows using accessible tools to achieve effective results.
  We utilize GitHub and DVC for version control of both code and data, ensuring consistency and traceability. Pydantic is employed to enforce data
   input serialization during Exploratory Data Analysis (EDA)   and training phases, while FastAPI serves as the backend framework.
   The project features a Gradio-powered application and a Docker image for seamless deployment in cloud environments.
   To enhance code reusability, we implement interfaces and abstract classes using Python's `protocol` and `abc` modules,
   promoting portability and  adaptability.

---
