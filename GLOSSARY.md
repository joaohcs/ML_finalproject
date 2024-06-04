# Glossary

#### Machine Learning
Machine Learning is a subset of artificial intelligence (AI) focused on building systems that learn from and make decisions based on data. These systems improve their performance over time without being explicitly programmed for every task, relying instead on patterns and inference.

#### Generative AI
Generative AI refers to a class of algorithms that can generate new data or content similar to the input data they were trained on. This includes creating text, images, music, and more, by learning from a large dataset and producing original outputs that mimic the characteristics of the training data.

#### Large Language Models (LLMs)
Large Language Models (LLMs) are a type of artificial intelligence model designed to understand and generate human language. They are trained on vast amounts of text data and can perform a variety of language-related tasks, such as translation, summarization, and conversation, by predicting the likelihood of word sequences.

#### Query
In the context of querying an LLM chatbot, a query is a request for information or a specific task made by the user through natural language input. The chatbot processes the query using its language model to generate a relevant and coherent response based on its training data.

#### Hallucinations
In AI, hallucinations refer to instances where the model generates information or content that is not based on the training data or real-world facts. These outputs can be misleading or entirely fictitious, reflecting the model's limitations in understanding and accuracy.

#### Embeddings
Embeddings are numerical, low-dimensional representations of data items typically used in machine learning to capture the features or relationships of objects like words, sentences, or images. These representations are engineered to place similar items closer together in the embedding space, facilitating tasks such as classification, clustering, and recommendation. This transformation not only reduces the computational load but also enhances model performance by capturing subtle semantic relationships in the data.

#### Vector Database
A vector database is a specialized database designed to efficiently store and retrieve vector embeddings used in ML applications. These databases are optimized for operations such as similarity search, where the goal is to quickly find vectors closest to a given query vector in high-dimensional space. They utilize indexing strategies and distance metrics (Euclidean, Cosine,Dot Product) to enable fast and scalable retrieval across large datasets. Vector databases are crucial in supporting real-time machine learning tasks like recommendation systems, image retrieval, and natural language processing, where the rapid comparison of feature vectors directly impacts performance and user experience.

#### Semantic Search
Semantic search involves the process where the system employs understanding of contextual and conceptual meanings to retrieve information that aligns with the intent behind the query. Unlike traditional keyword-based search, semantic search in RAG utilizes advanced natural language processing techniques to analyze the query semantically and fetch documents that are contextually relevant, not just textually similar. This capability enhances the model's ability to generate responses that are more accurate and contextually appropriate by ensuring that the underlying information from which it learns is directly relevant to the user's inquiry.

#### System Message
A system message is a specific instruction or information communicated to the AI model that helps guide its behavior or processing. For example, a system message might instruct the AI, "You are a helpful AI which helps the user answer questions about their business data. We will provide the source material as context." This message clarifies the AI's role and the nature of the data it will process, setting parameters for how the model retrieves relevant documents and generates responses based on the provided context. System messages are essential for directing the model's focus and ensuring that its outputs are aligned with user expectations and the specific tasks at hand

#### Chunking
In the context of RAG, chunking refers to the process of dividing the documents you want the LLM to access into smaller, contextually coherent segments or "chunks" before they are processed and transformed in embeddings, and finally can be used for generating responses. This technique enhances the RAG model's efficiency by enabling more focused and relevant interactions between the retrieval and generation components. Each chunk, representing a segment of the retrieved content, is separately fed into the generative model, ensuring that the nuances and specific details of the text are preserved and utilized effectively in generating accurate and contextually rich responses. 

#### Context Window and Tokens
The context window in machine learning, particularly in language models, refers to the span of text the model considers when generating a response. Tokens are the individual pieces of text (such as words or subwords) that the model processes. The context window size, often measured in tokens, determines how much information the model uses at a time to make predictions.
