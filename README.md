# Retrieval-Augmented-Generation-RAG-Implementation-in-Healthcare
This project showcases the implementation of Retrieval-Augmented Generation (RAG) in the healthcare domain to build an intelligent question-answering system capable of delivering accurate, relevant, and up-to-date information. Designed as part of a graduate-level course at the University of Texas at Austin, the system is built on top of a small subset of the MIMIC-III Clinical Database—specifically the 100HeadacheNLP dataset, which contains discharge summaries for patients presenting with headaches and related conditions.

The MIMIC-III (Medical Information Mart for Intensive Care III) is a widely used, publicly available dataset that contains de-identified health data associated with over 40,000 patients who stayed in intensive care units of the Beth Israel Deaconess Medical Center. It includes demographics, vital signs, laboratory tests, medications, caregiver notes, imaging reports, and more—making it a valuable resource for healthcare AI research.

Our project used this dataset to simulate real-world clinical information retrieval. By integrating LangChain, OpenAI GPT-3.5 Turbo, and Pinecone Vector Database, we created a RAG pipeline that can interpret natural language questions, retrieve relevant sections from medical notes, and generate well-informed responses.

Advanced features include:

1. Recursive text chunking, cosine similarity, and vector embeddings to optimize document retrieval
2. Prompt templating and output parsing to produce human-readable answers
3. A feedback loop mechanism to collect user ratings for continuous system improvement



This application demonstrates how RAG can enhance clinical decision-making, streamline healthcare workflows, and support patient-centered care in a secure and scalable way.
