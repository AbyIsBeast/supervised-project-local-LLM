# 🤖 Local LLM with RAG - Proof of Concept

**Supervised Project - Open Source AI Assistant**

## 📋 Project Overview

This project explores deploying a **secure, private Generative AI assistant** using company data, without reliance on external cloud APIs. Built entirely with open-source/open-weight models.

**Key Objectives:**
- Deploy local LLM on commodity hardware
- Implement Retrieval-Augmented Generation (RAG) with internal documents
- Create web interface for Q&A
- Measure accuracy, speed, and cost-effectiveness

## 🎯 Business Case

Mitigate data privacy risks and control long-term costs by running AI entirely on-premises using open-source technology.

## 🛠️ Technology Stack

| Component | Technology | Purpose |
|-----------|------------|---------|
| **LLM Runtime** | Ollama | Model inference engine |
| **Models** | Llama 3 / Mistral / Deepseek | Language generation |
| **Framework** | LangChain | RAG orchestration |
| **Vector DB** | ChromaDB | Document embeddings storage |
| **Embeddings** | all-MiniLM-L6-v2 | Text → vector conversion |
| **UI** | Gradio | Web interface |
| **OS** | Ubuntu 22.04 LTS | Base system |

## ⚙️ Hardware Requirements

**Minimum:**
- GPU: RTX 3060 12GB VRAM
- RAM: 32GB
- Storage: 1TB SSD

**Recommended:**
- GPU: RTX 4060 Ti 16GB VRAM
- RAM: 64GB
- Storage: 2TB NVMe SSD

**Budget:** $2,500 - $3,500

## 📅 Timeline (13 Weeks)

| Milestone | Week | Deliverable |
|-----------|------|-------------|
| M1 | 2 | Hardware setup complete |
| M1 | 4 | First LLM operational + benchmarked |
| M2 | 6 | RAG pipeline functional |
| M2 | 9 | Web interface integrated |
| M3 | 11 | Pilot user testing |
| M3 | 13 | Final presentation & report |

## 📊 Current Progress

**Phase 0: Planning & Foundation** - 2% Complete ✅

- [x] GitHub repository created
- [x] Folder structure established
- [x] Project documentation initialized
- [ ] Requirements document (PL1)
- [ ] Effort estimation (PL1)
- [ ] Hardware research

## 🎓 Academic Deliverables

### Software Engineering
- **PL1:** Requirements Document
- **PL2:** GitHub project with code & documentation

### Project Management
- **PL1:** Effort & cost estimation
- **PL2:** Progress tracking & actual vs. estimated comparison

### Advanced Databases
- Vector database implementation (ChromaDB)

## 👤 Team

**Student:** Alex (AbyIsBeast)  
**Period:** February - May 2025

## 🔗 Links

- GitHub Repository: https://github.com/AbyIsBeast/supervised-project-local-LLM
- Project Journal: docs/journal.md

---

**Last Updated:** February 10, 2025  
**Status:** 🟡 In Progress - Phase 0 (Planning)
