# User Stories
## Local LLM with RAG - Proof of Concept

**Project:** Supervised Project - Local LLM PoC  
**Student:** Alex (AbyIsBeast)  
**Date:** February 17, 2026

---

## US-01: Ask a Question

**Story:** *"As a company employee, I want to ask questions about internal documents and get instant answers, so that I don't have to manually search through hundreds of pages."*

**Acceptance Criteria:**
- I can type a question in plain English
- I receive an answer within 30 seconds
- The answer is relevant to my question
- I can see which document the answer came from

**Priority:** HIGH  

---

## US-02: Upload Company Documents

**Story:** *"As an administrator, I want to add our company's PDF documents to the system, so that employees can query our specific internal knowledge."*

**Acceptance Criteria:
**
- I can place PDF files in the data/sample-documents/ folder
- Running the ingestion script processes all documents
- Documents are searchable within 5 minutes of ingestion
- I receive confirmation when ingestion is complete

**Priority:** HIGH

---

## US-03: Get Honest "I Don't Know" Responses

**Story:** *"As a user, I want the AI to tell me when it doesn't have information, so that I can trust its answers and know when to look elsewhere."*

**Acceptance Criteria:**
- When I ask about something not in the documents, system responds "I don't have information about that in the provided documents"
- System does NOT make up answers or use general knowledge
- System suggests I check other sources when it can't answer

**Priority:** HIGH  

---

## US-04: Use System Without Technical Knowledge

**Story:** *"As a non-technical business user, I want to use the AI assistant through a simple web interface, so that I don't need to use the command line or know how AI works."*

**Acceptance Criteria:**
- I can access the system by opening a web browser
- The interface has clear labels and instructions
- I can start asking questions within 2 minutes of opening the browser
- No technical knowledge required

**Priority:** MEDIUM  

---

## US-05: Trust That Data Stays Private

**Story:** *"As a company security officer, I want to verify that no data is sent to external servers, so that our confidential documents remain secure."*

**Acceptance Criteria:**
- System works with internet completely disconnected
- Network monitoring shows zero outbound connections during queries
- All models and data are stored on local hardware
- No cloud API keys are required

**Priority:** HIGH  
**Target:** Week 4

---

## US-06: Evaluate System Performance

**Story:** *"As a project supervisor, I want to see performance metrics (speed, accuracy), so that I can decide whether to scale, pivot, or halt the project."*

**Acceptance Criteria:**
- I can see average response time for queries
- I can see accuracy rate from manual testing
- Results are presented in a clear report
- Metrics are compared against success criteria

**Priority:** MEDIUM  
**Target:** Week 13





