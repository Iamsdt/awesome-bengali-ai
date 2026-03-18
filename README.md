# Awesome Bengali AI

<p align="center">
  <img src="https://img.shields.io/badge/Bengali-AI-brightgreen?style=for-the-badge" alt="Bengali AI">
  <img src="https://img.shields.io/badge/LLM-Genie-ff69b4?style=for-the-badge" alt="LLM">
  <img src="https://img.shields.io/badge/Generative-AI-blue?style=for-the-badge" alt="Generative AI">
  <img src="https://img.shields.io/badge/NLP-Language-yellow?style=for-the-badge" alt="NLP">
</p>

A curated collection of resources, tools, datasets, models, and projects for Bengali (Bangla) Artificial Intelligence, Large Language Models, Generative AI, and Natural Language Processing. This repository aims to be the most comprehensive resource for researchers, developers, and enthusiasts working on Bengali language AI.

---

## Contents

- [Large Language Models (LLMs)](#large-language-models-llms)
  - [Open Source Bengali LLMs](#open-source-bengali-llms)
  - [Code Generation LLMs](#code-generation-llms)
  - [Multilingual LLMs with Bengali Support](#multilingual-llms-with-bengali-support)
  - [Fine-tuned & Specialized LLMs](#fine-tuned--specialized-llms)
  - [Embedding Models](#embedding-models)
- [Generative AI](#generative-ai)
  - [Text-to-Image Generation](#text-to-image-generation)
  - [Text-to-Speech / Speech Recognition](#text-to-speech--speech-recognition)
  - [Handwriting & OCR](#handwriting--ocr)
- [Retrieval-Augmented Generation (RAG) & Chatbots](#retrieval-augmented-generation-rag--chatbots)
- [Machine Translation](#machine-translation)
- [Datasets for LLMs & Fine-tuning](#datasets-for-llms--fine-tuning)
- [NLP Tasks & Models](#nlp-tasks--models)
  - [Named Entity Recognition (NER)](#named-entity-recognition-ner)
  - [Sentiment & Emotion Analysis](#sentiment--emotion-analysis)
  - [Text Classification](#text-classification)
  - [Text Summarization](#text-summarization)
  - [Question Answering](#question-answering)
  - [Part-of-Speech Tagging](#part-of-speech-tagging)
  - [Hate Speech & Toxic Detection](#hate-speech--toxic-detection)
  - [Text Augmentation & Paraphrasing](#text-augmentation--paraphrasing)
- [Research & Benchmarks](#research--benchmarks)
- [Tools & Libraries](#tools--libraries)
- [Datasets Collections](#datasets-collections)
- [Research Groups & Organizations](#research-groups--organizations)
- [Communities](#communities)
- [Contributing](#contributing)

---

## Large Language Models (LLMs)

### Open Source Bengali LLMs

| Model | Size | Description | Link |
|-------|------|-------------|------|
| **TigerLLM** | 1B-9B | Family of Bangla LLMs - SOTA open-source performance (ACL 2025) | [GitHub](https://github.com/mraihan-gmu/TigerLLM) \| [HuggingFace](https://huggingface.co/md-nishat-008/TigerLLM-1B-it) |
| **BanglaLLaMA** | 7B, 13B | Instruction-tuned Bangla LLaMA models (Base + Instruct) | [HuggingFace](https://huggingface.co/BanglaLLM) |
| **TiTULM** | 1B, 2B | Hishab's Bangla LLM trained on 4.5B+ tokens | [HF](https://huggingface.co/hishab/titulm-llama-3.2-1b-v1.0) \| [Gemma](https://huggingface.co/hishab/titulm-gemma-2-2b-v1.1) |
| **TigerCoder** | 1B, 9B | Code LLMs for Bangla - 11-18% better than alternatives | [arXiv](https://arxiv.org/abs/2509.09101) |
| **LilTii** | 0.6B | Bengali language model trained from scratch | [HuggingFace](https://huggingface.co/Polygl0t/LilTii) |
| **Bangla-AI** | 1.7B | Open Bangla instruction-tuned model | [HuggingFace](https://huggingface.co/swapnillo/Bangla-AI-1.7B) |
| **BongLLaMA** | - | LLaMA adapted for Bangla language | [arXiv](https://arxiv.org/abs/2410.21200) |
| **BengaliLlama** | - | Instruction-following LLaMA for Bengali (252K instructions) | [OpenReview](https://openreview.net/pdf/9b0cf00f3f78c4ee8e571ec923391b9a57dbc705.pdf) |
| **Bangla LLaMA (Context QA)** | 3B-8B | Fine-tuned Llama 3 for context-based QA and RAG | [GitHub](https://github.com/asiff00/Bangla-Llama) |

#### BanglaLLM Collection (HuggingFace)

- [BanglaLlama (Llama-2)](https://huggingface.co/collections/BanglaLLM/llama-2) - 7B/13B Base & Instruct
- [BanglaLlama (Llama-3)](https://huggingface.co/collections/BanglaLLM/llama-3) - Llama 3 variants
- [BanglaLlama (Llama-3.1)](https://huggingface.co/collections/BanglaLLM/llama-3-1) - Llama 3.1 variants
- [BanglaLlama (Llama-3.2)](https://huggingface.co/collections/BanglaLLM/llama-3-2) - Llama 3.2 variants
- [Bangla-s1](https://huggingface.co/collections/BanglaLLM/bangla-s1) - Reasoning models

### Code Generation LLMs

| Project | Description | Link |
|---------|-------------|------|
| **TigerCoder** | First dedicated Code LLMs for Bangla with MBPP-Bangla benchmark | [arXiv](https://arxiv.org/abs/2509.09101) |
| **BanglaForge** | LLM collaboration with self-refinement for Bangla code generation using RAG | [arXiv](https://arxiv.org/html/2512.19122v1) |

### Multilingual LLMs with Bengali Support

| Model | Description |
|-------|-------------|
| **BharatGen Param-1-7B-MoE** | Multilingual LLM supporting Bengali + 14 Indian languages |
| **Sarvam-105B** | Open-source LLM focused on Indian languages with strong Bengali support |
| **NLLB-200** | Meta's 200-language model (1.3B, 3.3B variants) with excellent Bengali translation |
| **Qwen3 Series** | Strong multilingual performance on Bengali (100+ languages) |
| **Gemma + LoRA** | Fine-tuned Gemma 2B for Bengali using Low-Rank Adaptation | [Medium](https://medium.com/@abhishek20dgp/building-a-bangla-llm-by-finetuning-gemma-2b-llm-using-low-rank-adaptation-lora-73bad579f0a4) |
| **Shiksha-MT** | NLLB-3.3B fine-tuned for educational translation in Bengali | [HuggingFace](https://huggingface.co/SPRINGLab/shiksha-MT-nllb-3.3B) |

### Fine-tuned & Specialized LLMs

| Model | Task | Description |
|-------|------|-------------|
| **BanglishSentiment-Llama3-8B** | Sentiment Analysis | Fine-tuned Llama3 for Banglish sentiment classification |
| **Hercule Bengali LoRA** | Evaluation | Cross-lingual evaluation model for Bengali LLMs (AI4Bharat) |
| **Parameter-Efficient Fine-tuning** | Hate Speech | PEFT comparison study for Bengali hate speech detection | [arXiv](https://arxiv.org/html/2510.16985v1) |

### Embedding Models

| Model | Description | Link |
|-------|-------------|------|
| **bangla2vec** | Bengali sentence embeddings | [GitHub](https://github.com/sagorbrur/bangla2vec) |
| **BanglaBERT** | ELECTRA-based embeddings for semantic search | [HuggingFace](https://huggingface.co/csebuetnlp/banglabert) |
| **Bangla-BERT-base** | Pretrained BERT for Bangla | [HuggingFace](https://huggingface.co/sagorsarker/bangla-bert-base) |

---

## Generative AI

### Text-to-Image Generation

| Project | Description | Link |
|---------|-------------|------|
| **Mukh-Oboyob** | Stable Diffusion + BanglaBERT for Bangla Text-to-Face synthesis | [Paper](https://thesai.org/Downloads/Volume14No11/Paper_142-Mukh_Oboyob_Stable_Diffusion_and_BanglaBERT.pdf) |
| **Bangla Text-to-Image** | Attentional GAN for Bengali text-to-image synthesis | [GitHub](https://github.com/pioneerAlpha/BanglaText2ImageGeneration) |
| **Bengali Flux LoRA** | Fine-tuned Flux.1 Dev for Bengali character generation | [Civitai](https://civitai.com/models/816997/bengali-model) |
| **Culturally-Aware Bangla TTI** | Fine-tuned Stable Diffusion Turbo for Bengali | [IEEE](https://www.researchgate.net/publication/395176563) |

### Text-to-Speech / Speech Recognition

| Project | Description | Link |
|---------|-------------|------|
| **SPRING LAB BENGALI-STREAMING** | Bengali ASR with Zipformer (750+ hours, supports Banglish) | [Model](https://huggingface.co/SPRING-BHASHINI/bengali-streaming) |
| **Bhashini Bengali ASR** | India AI's Bengali speech recognition model | [AI4Bharat](https://aihpc.gov.in/bhashini) |
| **Bangla-TTS-Datasets** | Collection of Bangla TTS datasets for fine-tuning | [HuggingFace](https://huggingface.co/collections/Mahadih534/bangla-tts-datasets) |
| **Bangla.ai Chatbot** | Bengali AI chatbot app for Android | [Google Play](https://play.google.com/store/apps/details?id=com.jokercodes.banglaai) |
| **Bengali Voice Bot** | AI voice agent with natural Bengali pronunciation | [Edesy](https://edesy.in/multilingual-voice-bot/languages/bengali) |
| **Soniox Bengali STT** | Speech-to-text API for Bengali AI voice agents | [Soniox](https://soniox.com/use-cases/voice-agents/bengali) |

### Handwriting & OCR

| Dataset/Model | Description | Link |
|---------------|-------------|------|
| **Bengali.AI Handwritten Graphemes** | Kaggle competition dataset for grapheme classification | [Kaggle](https://www.kaggle.com/c/bengaliai-cv19) |
| **BanglaLekha-Isolated** | Comprehensive Bangla handwritten character dataset | [Paper](https://www.academia.edu/82459466/BanglaLekha_Isolated_A_Comprehensive_Bangla_Handwritten_Character_Dataset) |
| **NumtaDB** | Bengali handwritten digits dataset | [Kaggle](https://www.kaggle.com/datasets/BengaliAI/numta) |
| **Bayanno** | Multi-purpose handwritten dataset for Bengali | [Mendeley](https://data.mendeley.com/datasets/jtpfd6j55n) |
| **CBD2023** | Hypercomplex Bangla handwriting data | [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC10789996/) |
| **Bongabdo** | Offline handwritten text recognition dataset | [UCI](https://archive.ics.uci.edu/dataset/894/bongabdo) |
| **GraDeT-HTR** | Resource-efficient Bengali HTR with grapheme tokenizer | [arXiv](https://arxiv.org/html/2509.18081v1) |
| **AKHCRNet** | Deep neural architecture for Bengali handwritten characters | [GitHub](https://github.com/theroyakash/AKHCRNet) |
| **Okkhor-Diffusion** | DDPM for Bangla handwritten character generation | [GitHub](https://github.com/MubtasimFuad10/Okkhor-Diffusion) |
| **BeHGAN** | Bengali handwritten word generation from text using GANs | [arXiv](https://arxiv.org/pdf/2512.21694) |
| **Bangla OCR Enhancement** | Specialized Bengali OCR for diverse document types | [WACV](https://openaccess.thecvf.com/content/WACV2024W/WVLL/papers/Rabby_Enhancement_of_Bengali_OCR_by_Specialized_Models_and_Advanced_Techniques_WACVW_2024_paper.pdf) |

---

## Retrieval-Augmented Generation (RAG) & Chatbots

### Open Source Projects

| Project | Description | Tech Stack |
|---------|-------------|------------|
| **Bangla-RAG-Pipeline** | Multilingual RAG for Bangla PDFs with OCR, Bangla-BERT, FAISS | LangChain, Gradio |
| **ProshnoAI** | Multilingual chatbot for Bangla PDF Question Answering | RAG, HuggingFace |
| **Bangla Legal Assistant** | RAG-powered legal assistant using Gemini for Bangladesh | FastAPI, RAG |
| **BanglAssist** | Bengali-English chatbot for customer service (code-switching) | Research Paper |
| **Bangla History Chatbot** | RAG-based chatbot for Bangla history preservation | FastAPI |
| **KFG HR Bot** | RAG chatbot for policy documents (Bangla + English) | LangChain, ChromaDB |
| **Bengali RAG Tutor** | Agentic RAG with memory for Bengali AI tutoring | LangGraph, Pinecone |
| **Bangla FAQ Chatbot** | RAG chatbot for Bengali Q&A with FAISS, SBERT | FAISS, SBERT |
| **Document QA RAG** | FastAPI-based RAG for document Q&A | FAISS, Groq |
| **Bengali & English QA Chatbot** | RAG pipeline for Bengali & English PDF documents | OCR, LLM |
| **Bangla.ai** | Bengali AI Chatbot mobile app | Android |

---

## Machine Translation

| Model | Description | Link |
|-------|-------------|------|
| **csebuetnlp/banglanmt** | Bengali-English NMT (EMNLP 2020) - aligner ensembling, batch filtering | [GitHub](https://github.com/csebuetnlp/banglanmt) |
| **csebuetnlp/banglat5_nmt_bn_en** | BanglaT5 for Bengali-English translation | [HuggingFace](https://huggingface.co/csebuetnlp/banglat5_nmt_bn_en) |
| **facebook/nllb-200** | Meta's 200-language model (1.3B, 3.3B variants) | [HuggingFace](https://huggingface.co/facebook/nllb-200-3.3B) |
| **NLLB Translator** | Next.js web app using NLLB-200 | [GitHub](https://github.com/somenath203/next-nllb200-language-translator) |
| **Shiksha-MT-nllb-3.3B** | Fine-tuned NLLB for educational translation (8 Indian languages) | [HuggingFace](https://huggingface.co/SPRINGLab/shiksha-MT-nllb-3.3B) |

---

## Datasets for LLMs & Fine-tuning

### Instruction & Fine-tuning Datasets

| Dataset | Description | Link |
|---------|-------------|------|
| **Bangla Instruction Dataset** | Collection for instruction tuning | [HuggingFace](https://huggingface.co/collections/Mahadih534/bangla-instruction-dataset-for-instruction-tuning) |
| **Bangla COT Datasets** | Chain-of-thought datasets for reasoning | [HuggingFace](https://huggingface.co/collections/Mahadih534/bangla-chain-of-thought-cot-datasets) |
| **Bangla Visual Reasoning** | VQA datasets for vision-language models | [HuggingFace](https://huggingface.co/collections/Mahadih534/bangla-visual-reasoning-datasets) |
| **Multilingual COT** | Multilingual CoT datasets for fine-tuning | [HuggingFace](https://huggingface.co/collections/Mahadih534/multilingual-chain-of-thought-cot-datasets-for-fine-tuning) |
| **Medical Datasets** | Bangla medical reasoning datasets | [HuggingFace](https://huggingface.co/collections/Mahadih534/medical-dataset-for-llm) |
| **TigerLLM Dataset** | Training data for TigerLLM family | [Paper](https://arxiv.org/html/2503.10995v1) |
| **BengaliParaphrase** | High-quality Bangla paraphrase dataset | [GitHub](https://github.com/csebuetnlp/banglaparaphrase) |
| **BanglaHealth Paraphrase** | Bengali paraphrase dataset on health domain | [Mendeley](https://pmc.ncbi.nlm.nih.gov/articles/PMC12167436/) |
| **BDA Framework** | Bangla Text Data Augmentation Framework | [arXiv](https://arxiv.org/pdf/2412.08753) |

### Benchmarks & Evaluation

| Benchmark | Description | Link |
|-----------|-------------|------|
| **BanglaMATH** | Bangla math word problems (grades 6-8, 1.7K samples) | [ACL](https://aclanthology.org/2025.mathnlp-main.10/) |
| **MBPP-Bangla** | Evaluation benchmark for Bangla code generation | [arXiv](https://arxiv.org/abs/2509.09101) |
| **BanglaNLG** | NLG benchmark (translation, summarization, QA, etc.) | [csebuetnlp](https://github.com/csebuetnlp/BanglaNLG) |
| **BEnQA** | Bengali-English QA benchmark for exam questions (ACL 2024) | [GitHub](https://github.com/sheikhshafayat/BEnQA) |
| **Hercules Bengali Eval** | Cross-lingual evaluation model for Bengali LLMs | [AI4Bharat](https://aikosh.indiaai.gov.in/home/models/details/ai4bharat_hercules_bengali_lora_evaluation_model.html) |

---

## NLP Tasks & Models

### Named Entity Recognition (NER)

| Dataset/Model | Description | Link |
|---------------|-------------|------|
| **BanNERD** | Largest human-annotated Bangla NER dataset (85K+ sentences, 29 domains) | [ACL](https://aclanthology.org/2025.findings-naacl.380/) |
| **ANCHOLIK-NER** | Benchmark for Bangla regional dialect NER (Barishal, Chittagong, etc.) | [PLOS ONE](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0342786) |
| **B-NER** | Novel Bangla NER dataset with largest entities | [IEEE](https://ieeexplore.ieee.org/document/10103464) |
| **Bangla NER (BanglaNLP)** | NER datasets for Bangla | [bnlp-resources](https://github.com/banglanlp/bnlp-resources) |
| **Banner** | Bengali NER using bootstrapping | [Paper](https://www.academia.edu/4228351/Banner_A_Word_SteamingMethod_for_Bengali_Named_Entity_Extraction) |

### Sentiment & Emotion Analysis

| Dataset/Model | Description | Link |
|---------------|-------------|------|
| **BnSentMix** | Bengali-English code-mixed sentiment dataset | [arXiv](https://arxiv.org/html/2408.08964) |
| **Bengali & Banglish Emotion** | Monolingual dataset for emotion detection | [Mendeley](https://data.mendeley.com/datasets/4dnrwbxt8n/2) |
| **Bangla Emotion Detection (Extended)** | Emotion detection dataset with extended taxonomy | [IEEE](https://arxiv.org/abs/2409.01736) |
| **SentNoB** | Sentiment on Noisy Bangla Texts | [Papers with Code](https://paperswithcode.com/dataset/sentnob) |
| **EmoMix-3L** | Code-mixed Bangla-English-Hindi emotion detection | [GitHub](https://github.com/GoswamiDhiman/EmoMix-3L) |
| **Bangla BERT Sentiment** | Fine-tuned BanglaBERT for sentiment analysis | [HuggingFace](https://huggingface.co/DipsankarSinha/bangla-sentiment-analysis) |
| **Hybrid Bangla Sentiment** | Lexicon + BanglaBERT approach | [arXiv](https://arxiv.org/pdf/2411.19584) |
| **Bangla Emotion ML+LIME** | Emotion analysis using ML and LIME explainability | [arXiv](https://arxiv.org/html/2506.10154v1) |

### Text Classification

| Dataset/Model | Description | Link |
|---------------|-------------|------|
| **Bangla News Dataset** | Multi-category Bangla news classification | [Kaggle](https://www.kaggle.com/datasets/furcifer/bangla-newspaper-dataset) |
| **Bangla NLP Dataset** | Sentiment, topic classification, hate speech | [Mendeley](https://data.mendeley.com/datasets/pv3mr44472) |
| **BanglaNewsClassifier** | Hybrid stacking classifiers for news classification | [PLOS ONE](https://www.researchgate.net/publication/392525742) |
| **Bangla News Categorization (Deep Learning)** | Deep learning approaches with fine-tuned BERT | [IJCA](https://www.ijcaonline.org/archives/volume187/number9/) |
| **Conv-LSTM Bangla** | Bangla document categorization using Conv-LSTM | [GitHub](https://github.com/eftekhar-hossain/Bengali-Document-Categorization) |
| **Bangla News Headlines** | GRU-based headlines categorization | [GitHub](https://github.com/eftekhar-hossain/Bangla-News-Headlines-Categorization) |
| **LLM for Bengali Text Classification** | Evaluation of LLM approaches | [arXiv](https://arxiv.org/html/2601.12132v1) |

### Text Summarization

| Dataset/Model | Description | Link |
|---------------|-------------|------|
| **XL-Sum** | Large-scale multilingual abstractive summarization (includes Bengali) | [GitHub](https://github.com/csebuetnlp/xl-sum) |
| **Bengali Summarization** | Unsupervised abstractive summarization (EACL 2021) | [GitHub](https://github.com/tafseer-nayeem/BengaliSummarization) |
| **Bangla Abstractive Summarization** | Transformer-based Bengali summarization | [IEEE](https://arxiv.org/html/2501.15051v1) |
| **Rank Your Summaries** | Ranking-based approach for Bengali summarization | [GitHub](https://github.com/TonmoyTalukder/Rank-Your-Summaries-Enhancing-Bengali-Text-Summarization-via-Ranking-based-Approach) |
| **Bangla Text Summarizer** | Abstractive + extractive summarization | [GitHub](https://github.com/Risvy/Bangla-Text-and-Document-Summarizer) |
| **Bengali News Summarization** | Bengali news summarization dataset | [Kaggle](https://www.kaggle.com/datasets/prithwirajsust/bengali-news-summarization-dataset) |
| **State-of-Art Transformers Review** | Review of transformers for Bengali text summarization | [MDPI](https://www.mdpi.com/2504-2289/9/5/117) |

### Question Answering

| Dataset | Description | Link |
|---------|-------------|------|
| **NCTB-QA** | Large-scale Bangla educational QA (87K+ pairs from 50 textbooks) | [arXiv](https://arxiv.org/html/2603.05462v1) |
| **BanglaQuAD** | Bengali open-domain QA dataset (native Bengali, not translated) | [arXiv](https://arxiv.org/html/2410.10229v1) |
| **BanglaRQA** | Reading comprehension QA with diverse question types (EMNLP 2022) | [ACL](https://aclanthology.org/2022.findings-emnlp.186/) |
| **BEnQA** | Bengali-English exam QA benchmark (ACL 2024 Findings) | [GitHub](https://github.com/sheikhshafayat/BEnQA) |
| **UDDIPOK** | Reading comprehension QA in Bangla from various sources | [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC9929199/) |
| **Bengali QA Dataset** | Bengali question answering dataset | [Kaggle](https://www.kaggle.com/datasets/mayeesha/bengali-question-answering-dataset) |
| **TiDy QA** | Bengali question answering dataset | [bangla-corpus](https://github.com/sagorbrur/bangla-corpus) |

### Part-of-Speech Tagging

| Resource | Description | Link |
|----------|-------------|------|
| **brnltk** | POS tagger and dialect processing for Bengali (LSTM-based) | [PyPI](https://pypi.org/project/brnltk/) |
| **Bangla POS Tagger (HMM)** | Hidden Markov Model based POS tagger | [GitHub](https://github.com/shaoncsecu/Bangla_POS_Tagger) |
| **Universal Dependencies Bengali** | Bengali treebank (UD format) | [UD](https://universaldependencies.org/bn/index.html) |
| **BDNC Treebank** | Bangla Syntactic Treebank Corpus (2M+ gold, 10M+ silver) | [BanglaGov](https://corpus.bangla.gov.bd/) |
| **Bangla POS (BNLP)** | POS tagging using BNLP toolkit | [GitHub](https://github.com/Rajspeaks/Machine-Learning-approach-to-Bengali-POS-Tagging-using-BNLP) |
| **Viterbi vs BiLSTM** | Performance comparison for Bangla POS tagging | [IEEE](https://ieeexplore.ieee.org/document/9829581) |

### Hate Speech & Toxic Detection

| Dataset | Description | Link |
|---------|-------------|------|
| **BengaliSent140** | Large-scale Bengali binary sentiment for hate/non-hate | [arXiv](https://arxiv.org/html/2601.20129v1) |
| **BD-SHS** | Benchmark dataset for Bangla hate speech (different social contexts) | [GitHub](https://github.com/naurosromim/hate-speech-dataset-for-Bengali-social-media) |
| **Bengali Hate Speech (UCI)** | Hate speech detection dataset (4.5K instances) | [UCI](https://archive.ics.uci.edu/dataset/719/bengali+hate+speech+detection+dataset) |
| **BIDWESH** | Bangla regional based hate speech detection | [arXiv](https://arxiv.org/html/2507.16183v1) |
| **ToxLex_bn** | Bangla toxic language from Facebook comments | [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC9256543/) |
| **Context-Aware Bengali Toxic** | Bengali toxic comments with context (Prothom Alo, News24) | [Mendeley](https://data.mendeley.com/datasets/gphbs7vsbz/1) |
| **Multi-Label Toxic** | Interpretable multi-label Bengali toxic comments | [GitHub](https://github.com/deepu099cse/Multi-Labeled-Bengali-Toxic-Comments-Classification) |
| **Cyberbully/Spam Detection** | Bangla multilabel cyberbully, harassment, threat, spam | [Mendeley](https://data.mendeley.com/datasets/sz5558wrd4/3) |
| **Abusive Code-Mixed** | Bangla-English code-mixed abusive comment detection | [IEEE](https://arxiv.org/abs/1912.12626) |
| **HateBertBN** | Hybrid transformer for Bangla hate speech detection | [Springer](https://link.springer.com/article/10.1007/s10791-025-09804-x) |
| **PEFT for Hate Speech** | Parameter-efficient fine-tuning comparison for Bengali | [arXiv](https://arxiv.org/html/2510.16985v1) |

### Text Augmentation & Paraphrasing

| Resource | Description | Link |
|----------|-------------|------|
| **BanglaParaphrase** | High-quality Bangla paraphrase dataset (BUET CSE NLP) | [GitHub](https://github.com/csebuetnlp/banglaparaphrase) \| [HuggingFace](https://huggingface.co/datasets/csebuetnlp/BanglaParaphrase) |
| **BnPC** | Gold standard Bangla paraphrase corpus | [Kaggle](https://www.kaggle.com/datasets/souravsaha0152/bnpc-a-gold-standard-bangla-paraphrase-corpus) |
| **Large-scale Bangla Paraphrase** | Comprehensive paraphrase generation dataset | [IEEE](https://ieeexplore.ieee.org/document/11022379/) |
| **BanglaHealth Paraphrase** | Health domain paraphrase dataset | [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC12167436/) |
| **BDA Framework** | Bangla Text Data Augmentation using pre-trained + rule-based | [arXiv](https://arxiv.org/pdf/2412.08753) |

---

## Research & Benchmarks

### Key Papers (2022-2026)

| Year | Paper | Venue | Description |
|------|-------|-------|-------------|
| 2025 | TigerLLM | ACL | Family of Bangla LLMs |
| 2025 | TigerCoder | arXiv | Code LLMs for Bangla |
| 2025 | BanglaForge | arXiv | Self-refinement for Bangla code generation |
| 2025 | BanglaMATH | ACL MathNLP | Bangla math reasoning benchmark |
| 2025 | BanNERD | NAACL Findings | Largest Bangla NER dataset (85K sentences) |
| 2025 | GraDeT-HTR | arXiv | Bengali handwritten text recognition |
| 2025 | Bangla Abstractive Summarization | IEEE | Transformer-based summarization |
| 2025 | BanglaNewsClassifier | PLOS ONE | Hybrid stacking for news classification |
| 2025 | Bengali Text Classification | arXiv | LLM evaluation approaches |
| 2024 | NCTB-QA | arXiv | Large-scale Bangla educational QA |
| 2024 | BanglaQuAD | arXiv | Native Bengali open-domain QA |
| 2024 | BnSentMix | arXiv | Bengali-English code-mixed sentiment |
| 2024 | Bengali & Banglish Emotion | PMC | Emotion detection dataset |
| 2024 | BanglaParaphrase | arXiv | High-quality paraphrase dataset |
| 2023 | BanglaNLG | EACL | BanglaT5 and NLG benchmarks |
| 2023 | BanglaRQA | EMNLP Findings | Reading comprehension QA |
| 2023 | BEnQA | ACL Findings | Bengali-English QA benchmark |
| 2022 | BanglaBERT | NAACL | BERT for Bangla NLU |
| 2021 | Bengali Summarization | EACL | Unsupervised abstractive summarization |
| 2020 | BanglaNMT | EMNLP | Bengali-English machine translation |

### Tracking Progress

- [Bengali-NLP-Progress](https://github.com/sagorbrur/Bengali-NLP-Progress) - SOTA tracking for Bengali NLP
- [NLP Progress - Bengali](https://github.com/sebastianruder/NLP-progress/blob/master/bengali) - Sebastian Ruder's NLP progress tracker

---

## Tools & Libraries

### NLP Libraries

| Library | Description | Link |
|---------|-------------|------|
| **BNLP** | Bengali Natural Language Processing toolkit | [GitHub](https://github.com/banglakit/bnlp) |
| **brnltk** | POS tagging and dialect processing (LSTM-based) | [PyPI](https://pypi.org/project/brnltk/) |
| **csebuetnlp/normalizer** | Text normalization for Bangla | [GitHub](https://github.com/csebuetnlp/normalizer) |
| **BanglaNLP Resources** | Comprehensive Bangla NLP datasets | [GitHub](https://github.com/banglanlp/bnlp-resources) |

### Input Tools

| Tool | Description | Link |
|------|-------------|------|
| **Avro Keyboard** | Popular Bangla keyboard (Windows, Mac, Linux) | [GitHub](https://github.com/nicornk/avro-keyboard) |
| **Ridmik Keyboard** | Android Bangla keyboard app | [Google Play](https://play.google.com/store/apps/details?id=com.ridmik.keyboard) |
| **jGanana (Indic input)** | Input method for Bangla | [GitHub](https://github.com/sunctux/jganana) |

---

## Datasets Collections

| Collection | Description | Link |
|------------|-------------|------|
| **Bengali.AI Datasets** | Open source datasets for Bengali NLP/CV research | [bengali.ai](https://bengali.ai/datasets) |
| **banglanlp/bnlp-resources** | NER, POS, sentiment, emotion, lemma datasets | [GitHub](https://github.com/banglanlp/bnlp-resources) |
| **sagorbrur/bangla-corpus** | Translation, NER, POS, QA corpus | [GitHub](https://github.com/sagorbrur/bangla-corpus) |
| **banglakit/awesome-bangla** | Comprehensive Bangla computing resources (564 stars) | [GitHub](https://github.com/banglakit/awesome-bangla) |
| **Foysal87/Bangla-NLP-Dataset** | NER, POS, summarization, sentiment, QA | [GitHub](https://github.com/Foysal87/Bangla-NLP-Dataset) |
| **BanglaCorpus** | Multiple Bangla corpus resources | [BanglaGov](https://corpus.bangla.gov.bd/) |
| **Universal Dependencies Bengali** | UD treebank for Bengali | [UD](https://universaldependencies.org/bn/index.html) |

---

## Research Groups & Organizations

| Organization | Focus | Link |
|-------------|-------|------|
| **BUET CSE NLP Group** | Leading Bangla NLP research (BanglaBERT, BanglaT5, XL-Sum) | [Website](https://csebuetnlp.github.io/) |
| **Bengali.AI** | Non-profit for open-source Bengali datasets and research | [bengali.ai](https://bengali.ai/) |
| **AI4Bharat** | Indian language AI, translation, models | [AI4Bharat](https://ai4bharat.org/) |
| **India AI** | India's AI mission with Bengali models | [indiaai.gov.in](https://indiaai.gov.in/) |
| **Bangladesh Computer Council** | Bangla language technology | [BCC](https://bcc.gov.bd/) |

---

## Communities

| Community | Description | Link |
|-----------|-------------|------|
| **Machine Learning Bangladesh** | Active ML community in Bangladesh | [Facebook](https://www.facebook.com/groups/mlban) |
| **Bengali.AI Community** | Bengali AI practitioners | [Facebook](https://www.facebook.com/groups/bengaliAI) |
| **banglakit/awesome-bangla** | Long-standing resource collection (564 stars) | [GitHub](https://github.com/banglakit/awesome-bangla) |
| **Bangla NLP Researchers** | Academic research community | Various |

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request to add:
- New models, datasets, or tools
- Missing resources or corrections
- Updated links or descriptions

---

## License

[![CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

This work is licensed under a Creative Commons CC0 1.0 Universal License.

---

<p align="center">
  <strong>Star this repo if you find it useful!</strong>
  <br>
  <a href="https://github.com/your-username/awesome-bengali-ai/stargazers"><img src="https://img.shields.io/github/stars/your-username/awesome-bengali-ai?style=social" alt="Stars"></a>
</p>
