# Tutorials

**Feedback Dataset**

```{include} /_common/feedback_dataset.md
```

Here you can find end-to-end examples to help you get started with curanting datasets and collecting feedback to fine-tune LLMs and other language models.

````{grid}  1 1 3 3
:class-container: tuto-section-2
```{grid-item-card} Ⓜ️ Fine-tuning LLMs as chat assistants: Supervised Finetuning on Mistral 7B
:link: feedback/training-llm-mistral-sft.html

Learn how to fine-tune Mistral 7B into a chat assistant using supervised finetuning with the ArgillaTrainer and TRL.
```
```{grid-item-card} 🪄 Fine-tuning and evaluating GPT-3.5 with human feedback for RAG
:link: feedback/fine-tuning-openai-rag-feedback.html

Learn how to fine-tune and evaluate gpt3.5-turbo models with human feedback for RAG applications with LlamaIndex.
```
```{grid-item-card} 🎛️ Fine-tune a SetFit model using the ArgillaTrainer
:link: feedback/trainer-feedback-setfit.html

Learn how to use the ArgillaTrainer to fine-tune your Feedback Dataset using Setfit.
```
```{grid-item-card} 🏆 Train a reward model for RLHF
:link: feedback/train-reward-model-rlhf.html

Learn how to collect comparison or human preference data and train a reward model with the trl library.

```
```{grid-item-card} ❓ Train a QnA model with transformers and Argilla
:link: feedback/training-qa-transformers.html

Learn how to fine-tune a QnA model with transformers and annotated data using ArgillaTrainer
```
```{grid-item-card} 🌠 Fine-tune RAG pipelines by training retrieval and reranking models
:link: feedback/fine-tuning-sentencesimilarity-rag.html

Learn how to boost RAG performance through optimized retrieval and reranking models for better AI accuracy.
```
```{grid-item-card} ✨ Add zero-shot text classification suggestions using SetFit
:link: feedback/labelling-feedback-setfit.html

Learn how to add suggestions to your Feedback Dataset using SetFit.
```
```{grid-item-card} 🧸 Using LLMs for text classification and summarization with spacy-llm
:link: feedback/labelling-spacy-llm.html

Learn how to add suggestions for text classification and summarization to your Feedback Dataset using spacy-llm.
```
```{grid-item-card} 🎡 Create synthetic data and annotations with LLMs
:link: feedback/labelling-feedback-langchain-syntethic.html

Learn how to create synthetic data and annotations with OpenAI, LangChain, Transformers and Outlines.
```
```{grid-item-card} 🖼️ Curate an instruction dataset for supervised fine-tuning
:link: feedback/curating-feedback-instructiondataset.html

Learn how to set up a project to curate a public dataset that can be used to fine-tune an instruction-following model.
```

````

**Other datasets**

```{include} /_common/other_datasets.md
```

Looking for more tutorials? Check out our [notebooks folder](/reference/notebooks)!

````{grid}  1 1 3 3
:class-container: tuto-section-2
```{grid-item-card} 🤯 Few-shot classification with SetFit
:link: other_datasets/few_shot_learning_with_setfit.html

Learn how to use the `setfit` library to perform few-shot classification.

```

```{grid-item-card} 👂 Few shot text classification with active learning using small-text and SetFit
:link: other_datasets/few_shot_text_classification_with_active_learning.html

Learn how to use the `setfit` and `small-text` libraries to perform few-shot text classification with active learning.

```
```{grid-item-card} 💨 Label data with semantic search and Sentence Transformers
:link: other_datasets/label_data_with_semantic_search.html

Learn how to use the `sentence-transformers` library to label data with semantic search.

```
```{grid-item-card} 🧹 Find and clean label errors with cleanlab
:link: other_datasets/label_errors_cleanlab.html

Learn how to use the `cleanlab` library to find and clean label errors.

```
```{grid-item-card} 🐭 Train a NER model with weak supervision rules using skweak
:link: other_datasets/weak_supervision_ner.html

Learn how to use the `snorkel` library to perform weak supervision for NER.
```
```{grid-item-card} 👮 Weak supervision for text classification with semantic search
:link: other_datasets/weak_supervision_text_classification_semantic_search.html

Learn how to use the `sentence-transformers` and `snorkel` to do weak supervision for text classification with semantic search.
```
```{grid-item-card} 🔗 Using LLMs for Few-Shot Token Classification Suggestions with spacy-llm
:link: other_datasets/labelling-tokenclassification-using-spacy-llm.html

Learn how to use the `spacy-llm` library to do few-shot token classification.
```
````
<!--
```{toctree}
:hidden:

feedback/fine-tuning-openai-rag-feedback
feedback/training-llm-mistral-sft
feedback/curating-feedback-instructiondataset
feedback/train-reward-model-rlhf
feedback/labelling-feedback-setfit
feedback/trainer-feedback-setfit
feedback/labelling-feedback-langchain-syntethic
feedback/fine-tuning-sentencesimilarity-rag

other_datasets/few_shot_learning_with_setfit
other_datasets/few_shot_text_classification_with_active_learning
other_datasets/label_data_with_semantic_search
other_datasets/label_errors_cleanlab
other_datasets/weak_supervision_ner
other_datasets/weak_supervision_text_classification_semantic_search
other_datasets/labelling-tokenclassification-using-spacy-llm
``` -->