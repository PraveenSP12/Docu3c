# Docu3c
AI Prompt Engineer Internship  

Decoding Covid-19 with Genome Analysis using knowledge graph 

Overview
Given problem statement
You are one of the researchers responding to the White House Office of Science and Technology Policy center’s call to conduct advanced research on Covid-19. You are working with CDC, which has led a coordinated effort to set up a machine readable dataset. A dataset that represents the most extensive machine-readable coronavirus literature collection available for data and text mining to date, with over 29,000 articles, more than 13,000 of which have full
text. Using the CORD-NER dataset and Knowledge Graph, determine and map out the details of the SARS-CoV-2 genome to assist understanding of the emergence, evolution and diagnosis of this deadly virus.


knowledge graphs in machine learning
A knowledge graph, also known as a semantic network, represents a network of real-world entities—i.e. objects, events, situations, or concepts—and illustrates the relationship between them. This information is usually stored in a graph database and visualized as a graph structure, prompting the term knowledge “graph.”



Dataset Link 
https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge



Simple procedure
1. Import the necessary libraries such as (Example: Panda, Numpy, Spacy, tqdm, networkx, matplotlib, etc)
2. Import the Dataset specific file named Metadata.csv (1.65 GB) , The whole Dataset contains 87 GB of Data which makes the model hard to execute.
3. Then using the imported libraries such as Spacy,NLP. we need to extract the Entities & Relationships
4. tqum library is used to pair the Entities & Relations.
5. Create a new CSV file using the collected Entities & Relationship as (Source & Destination)
6. By using matplotlib, spacy, networkx libraries draw the knowledge graphs for the Source & Destination with Relationships
7. plot the output of Knowledge Graph.



Sample Outputs:
![final](https://github.com/PraveenSP12/Docu3c/assets/95535247/482af48d-a095-4711-aa3d-51811e563466)
![download](https://github.com/PraveenSP12/Docu3c/assets/95535247/b1efba57-aeb8-4eca-9550-65378e63a654)
![download (2)](https://github.com/PraveenSP12/Docu3c/assets/95535247/e8d99452-9c4c-4ded-a538-8379dd3111b3)


