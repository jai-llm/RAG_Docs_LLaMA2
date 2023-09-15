# Retrieval Augmented Generation
Code implementing Retrieval Augmented Generation using the LLaMA2 Open Source LLM model. Details related to RAG can be found in RAG_ForDocs_Details.pdf.

The IPYNB Notebook can be run in Google Colab using the free T4 GPU (be sure to select GPU option in Notebook Settings in Colab). 

Notebook does the following:
1. Downloads documents from the web and stores these PDFs in a folder.
2. Processes these PDF files and stores them in a vector store (Chroma DB).
3. Creates RAG Chain consisting of LLM + Retriever + Prompt.
4. Shows the benefits of RAG in terms of white-boxing LLMs and reducing "hallucinations"
