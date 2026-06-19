# PROCESS PIPELINE (IN PROGRESS)   
may june 2026.    

Depending on the problem or challenges in a particular project, not all steps are needed. This is an iterative process, which means that sometimes, from one step to the next, it is necessary to go back and repeat some steps until the goal is reached. 
It is possibLe to generate questions for each stage of the process. Each stage can also have its own goals, methods, tools, associated technologies, and input-output. 

**General Tools:** Spacy, Scipy-ScikitLearn, Numpy, NLTK, Docker, Neo4J-Cypher, Annoy, GIT, PyTorch, Jupyter, Google Colab, D3, Apache Echarts, Apache Superset,
other. 

### A: From Document to Data Structure
This part related to Data is well documented, mainly from the engineering field; some other experiences related to DH challenges are also being documented. It is possible to incorporate visualisations for some stages to explore potential outputs. 

**Phase A1: Problem Definition, Goals, Scope:** 
–Team and roles definition.   
–Describing data's current state (time frame, type, context, etc.).  
–Defining scope, and constraints (Workflow, Stefaner, 2014).  
–Evaluating initial possible media outcomes.   
–Defining initial need and goals for the archive and Visualization.    
–Consider ethical, legal and proprietary concerns.   
–Initial preview of the methodological process.   
–Technical preview (methods [colab], libraries[transformers, vision transformers], softwares, models, etc)   
–Autoethnography tools.   
–Research Workshop & Interviews.   

**Phase A2: Docs_Preparation:**   
–Initial data exploration (usually from metadata from archives).  
–Identify data boundaries (period, authors, types, etc).  
–Define scope and gather sources (which ones, where).   
–Collect documents from archives and repositories.   
–Locating relevant documents.   
–Assess data quality and digitisation needs.   
–Standardise file formats (TXT, XML, JPG, PDF).  
–for classification resize, and/or rescale, 3 channels.    
–Clasificación (redes convolucionales, visión transformer?).  
–Defining methods to OCR/Metadata process (LLM & prompting techniques).  
–OCR application.  
–OCR correction & cleaning noise.  
–Document metadata schema for the corpus.  

**Phase A3: Data Preprocessing for computational analysis:**. 
–Defining tools for preprocessing (LLM & prompting techniques).  
–Tokenise and segment sentences/paragraphs.  
–Normalise text (lowercasing, lemmatisation).  
–Removing noise (stopwords, punctuation).   
–Annotate text with linguistic tags (POS, syntax).   
–Converting documents into machine‑readable structures (JSON, CSV).   
–Validate preprocessing with sample checks.   

**Phase A4: Information Extraction:**. Text2KG  (spaCy).  
–Text chunking with overlap.  
–Defining elements to recognise and to extract. ONtologies.   
–Defining method for information extraction (LLM & prompting techniques).  
–Defining LLM to extraction process (LLM & prompting techniques).  
–Named Entity Recognition (people, places, tools, concepts, events, dates).   
–Detecting topics (topic modelling, BeRTtopic).  
–Designing semantic relations (Subject ➔ Predicate ➔ Object).   
–Extracting relations & link identificación (who did what, where). 
–Evaluate extraction accuracy (manual samples).  
–Correference resolution (entity-entity; entity-popularity; entity-content).  

**Phase A5: Data Structure & Modeling for visualization:**   
–Defining LLM for data structuring (method & prompting techniques).  
–Design data model, Ontology definition (entities, attributes, relations) (Protegé, Chimaera).  
–Graph structure for entity linking myKG de medium?   
–Entity Linking connecting using external vocabulary (Wikidata, Geonames).   
–Competency Questions for Ontology Engineering, Manual & LLM (Pan et al.,2025). 
–Build a Knowledge Graph or relational tables.  
–Defining LLM/model to embedding creation (Gensim, Other).  
–Vector database (Annoy, other).  
–Query design (LLM to query).  
–Query to cypher (LLM to cypher).  
–Integrate metadata + extracted data.  
–DB normalisation for visualisation (network, map, timeline, other).  
–RAG, eventual incorporation of complementary documents.  


### OPTIONAL A2?: Developing Cultural Analitytics.   
–Data Analysis.   
–Cultural Analytics.  

### Pipeline B: From Data Structure to Visualisation.  
**Phase B5: Visualization requirements:**.  
–Defining conceptual requirements.   
–Defining technical requirements.   
–Definition of structural narratives for visualisations.  
–Defining user requirements (general, experts, flaneurs, etc).   
 
**Phase B6: Queries to DDBB:**.  
–Chat prototyping for DDBB queries.   
–Building a system for queries to the DDBB.   
–Testing Chat development.   

**Phase B7: Interface Definition:**.  
–Defining main Visual encoding.   
–Initial exploratory visualisations (graphs, maps, timelines, etc)
–Exploring DDBB visual representations.   
–Defining UX-UI requirements.   

**Phase B8: Funcional Prototype Implementación**.  
–Visualisation web Integration.   
–Model tovos.   
–Chat to vis.   

**Phase B9: Documentaiotn and maintain**.  
–Document.   
–Maintain.   

**Phase B10: Spread Sharing**.  
–Spread to the world.   
–Media integration.   
–Sharing project and sub parts.  

**Phase B11: User Testing:**.  
–Document methodology and limitations.   

### Otras consideraciones.
–Iteraciones: Serie de testeos de usuario y análisis de resultados del prototipo.
B4– Resultados: –Análisis del proceso: Comparativa con modelos de visualización, análisis de las etapas.
–Propuesta de modelo: Desarrollo de modelo conceptual propuesto que integra tanto
tecnologías recientes y conocimiento de dominio sobre documentos del caso de estudio.
–Salida: Desarrollo de Conclusiones generales sobre el prototipo y los modelos estudiados y
desarrollados. Empaquetamiento de entregables como el prototipo, bbdd, análisis, etc.

