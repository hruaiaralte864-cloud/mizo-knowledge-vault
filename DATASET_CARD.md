# 🗂️ Mizo Knowledge Vault Dataset Card

## 📌 Dataset Overview
The **Mizo Knowledge Vault** is a high-resolution, structured bilingual dataset focused on the history, culture, geography, and language of the Mizo people. It is designed for both human consumption via the Obsidian PKM system and machine ingestion for LLM training (RAG, Fine-tuning).

- **Total Knowledge Nodes**: 1,599
- **Dictionary Entries**: 14,884
- **Languages**: Mizo, English, Mixed
- **Format**: Markdown (UTF-8) with YAML Frontmatter
- **Structure**: Hierarchical taxonomy (24 categories)

## 🎯 Use Cases
1. **RAG (Retrieval-Augmented Generation)**: High-density indexing for domain-specific local AI agents.
2. **NMT (Neural Machine Translation)**: Building English-Mizo translation models using the `bilingual_dictionary.json`.
3. **Cultural Fine-tuning**: Improving LLM performance on low-resource tribal languages and histories.

## 🛠️ Data Structure
Every knowledge node contains standardized YAML frontmatter:
```yaml
title: "Node Title"
category: "History/Culture/etc"
tags: ["tag1", "tag2"]
language: "mizo/english/mixed"
tokens: 1234
ai_ready: true
completeness: "high/medium/low"
```

## 📜 Licensing
- **Code & Repository Structure**: MIT License
- **Text Content**: Creative Commons Attribution 4.0 International (CC-BY 4.0)

## 🤝 Attribution
Produced by the Mizo Knowledge Vault Project.
