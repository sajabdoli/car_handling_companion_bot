# Car manual assistant, Work in progress!

This repo contains a notebook, a simple use case of [Llama assistant model](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct) for answering questions related to car handling. 
This is a simple [Retrieval-Augmented Generation](https://blogs.nvidia.com/blog/what-is-retrieval-augmented-generation/), aka RAG model, that extracts related parts from the manual according to the user's query for a clear, validated answer by the assistant.

In this use case, we use the manual document of the Toyota Venza car available in this file:
- [Car manual original PDF](https://assets.sia.toyota.com/publications/en/omnav-s/OM48K20U/pdf/OM48K20U.pdf)
- This document is created by converting the .pdf to a text file to be used in the RAG model: [Car manual text version](https://github.com/sajabdoli/car_handling_companion_bot/blob/main/cleaned_car_manual.md) 

ToDo:
- [ ] More document cleaning is needed as there is some irrelevant information in the file eg. removing the indexes, and image captions and making it more structured.
- [ ] Improve the system instructions
- [ ] Create a set of test questions to assess the performance of the answers and detect the hallucination 
