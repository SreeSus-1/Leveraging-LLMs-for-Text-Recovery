# Leveraging-LLMs-for-Text-Recovery

🔄 Notebook: Leveraging LLMs for Text Recovery.ipynb
This notebook is a research-focused experiment that explores how large language models (LLMs) can be used to reconstruct or recover text from shuffled, fragmented, or noisy document data.

🧪 Purpose
EXPERIMENT-1: Assess LLM effectiveness in reconstructing disrupted text inputs for document recovery and semantic alignment.

🔧 Libraries Used
OpenAI, scikit-learn, matplotlib, seaborn

pandas, numpy, re, random, cosine_similarity

Google Colab integrations: drive, userdata

🧠 Key Functions
read_document_and_split(): Loads and segments input text

prepare_shuffled_sentences_and_words(): Introduces random noise/shuffling

get_completion(): Calls OpenAI’s API to generate completions

llm_reconstruction(): Rebuilds logical order using LLM outputs

create_summary_table(): Measures and displays performance/accuracy

This notebook highlights LLMs' potential in document cleanup, text recovery, and AI-based summarization under imperfect input conditions.
