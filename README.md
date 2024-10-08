# Car manual assistant, Work in progress!

This repo contains a notebook, a simple use case of [Llama assistant model](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct) for answering questions related to car handling. 
This is a simple [Retrieval-Augmented Generation](https://blogs.nvidia.com/blog/what-is-retrieval-augmented-generation/), aka RAG model, that extracts related parts from the manual according to the user's query for a clear, validated answer by the assistant.

In this use case, we use the manual document of the Toyota Verena car available in this file: The document is created by converting the .pdf to a text file. 

ToDo:
- [ ] More document cleaning is needed as there is some irrelevant and repeated information in the file.
- [ ] Improve the system instructions
- [ ] Create a set of test questions to assess the performance of the answers and detect the hallucination 
