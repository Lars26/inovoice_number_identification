# Invoice Number Extraction with Longformer and RAG
This project explores two approaches to automatically extract invoice numbers from semi-structured documents:

Longformer-based Sequence Labeling:
A transformer model fine-tuned to identify invoice numbers using token classification on long text spans. Suitable for OCR-extracted, layout-flattened documents.

Retrieval-Augmented Generation (RAG):
Combines a vector-based retrieval system with a generative language model. Relevant document chunks are retrieved based on query similarity, and the model generates or selects the correct invoice number.
Both models aim to improve information extraction in real-world invoice workflows, especially in cases where traditional pattern matching fails due to layout noise or document diversity.
