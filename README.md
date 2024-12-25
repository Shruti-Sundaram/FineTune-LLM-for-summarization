**Efficient Summarization of Research Papers Using Fine-Tuned Small Context Language Models**


Model used: BART-large-CNN

Token Size: 1024


The Challenge: 

Summarizing complex research papers poses a unique challenge due to their length and intricate context. Traditional large language models (LLMs) are optimized for shorter texts and often struggle with the extensive context required for academic content due to their limited context-window. While newer models like Longformer can handle longer contexts, they are resource-intensive, difficult to fine-tune, and costly.


💡 Highlights of the cost-effective approach presented in my dissertation:

• Fine-tuned a small-context LLM (specifically the BART-large-CNN model) to understand research papers better. This is more efficient and less computationally demanding than training long-context models, making it an ideal solution for time and resource-constrained environments.

• Created a novel adaptive recursive chunking strategy that splits long documents into smaller pieces that fit within the model’s 1024-token limit. A recursive function then iteratively refines the summaries, preserving context across chunks and ensuring the final summary is coherent and meets length constraints. This approach dynamically adjusts based on the input text length, maintaining coherence across the chunks.

• Compare its performance to long-context models like Longformer using ROUGE metrics.

The goal? To prove that small-context LLMs, with the right strategies, can rival (or beat!) their long-context counterparts. 
