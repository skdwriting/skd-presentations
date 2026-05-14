# Project: IoTShow Agenda Copilot

## Project Overview

IoTShow Agenda Copilot is an AI-powered conversational assistant designed for the India Electronics Week 2026 event.

The copilot enables attendees, speakers, exhibitors, organizers, and visitors to interact with the event agenda using natural language queries.

The solution uses an AI-driven retrieval and conversational interface to answer questions related to:

- Session schedules
- Speaker details
- Tracks and topics
- Session timings
- Session locations
- Day-wise agenda
- Event navigation
- Recommended sessions

The copilot retrieves agenda information from:

https://www.indiaelectronicsweek.com/agenda-2026/

The agenda contains multiple tabs:
- Day 1
- Day 2
- Day 3

The system should understand and answer queries across all agenda days.

---

# Business Objective

Create an AI-native event assistant that improves attendee engagement and simplifies agenda navigation using conversational AI.

The solution should demonstrate:
- AI-Augmented SDLC (A2-SDLC)
- Agentic AI orchestration
- Knowledge-grounded conversational AI
- Retrieval-Augmented Generation (RAG)
- AI role realization within SDLC
- Enterprise AI engineering workflow

This project will be used as a live demonstration for the conference session:

"A2-SDLC: Uncoding the Legacy to Elevate Product Development with AI"

---

# Key Goals

## Functional Goals

1. Answer attendee questions about event sessions
2. Support conversational natural language interactions
3. Search agenda across all event days
4. Retrieve accurate session details
5. Provide contextual responses
6. Support follow-up conversational queries
7. Handle ambiguous user queries intelligently

---

# Example User Queries

## Basic Queries

- What are the AI sessions on Day 1?
- Who is speaking about IoT security?
- What sessions are available after lunch on Day 2?
- Show me cloud computing sessions.
- Which sessions discuss embedded systems?
- What is the first keynote on Day 3?
- Are there any GenAI sessions?
- Which speaker is presenting on industrial IoT?

---

# Expected AI Capabilities

The copilot should:

- Understand conversational queries
- Perform semantic search
- Retrieve relevant agenda items
- Summarize session information
- Maintain conversational context
- Recommend related sessions
- Handle incomplete queries
- Handle spelling variations and abbreviations

---

# Scope

## In Scope

- Agenda ingestion
- Multi-day agenda understanding
- Conversational chatbot
- RAG-based retrieval
- AI answer generation
- Semantic search
- Session recommendation
- Responsive UI
- Context-aware responses

## Out of Scope

- Ticket booking
- Authentication
- Personalized schedules
- Speaker management
- Calendar sync
- Payment processing

---

# Target Users

- Event attendees
- Conference speakers
- Organizers
- Media participants
- Exhibitors
- Technology professionals

---

# Architecture Overview

## High-Level Components

### 1. Agenda Ingestion Layer
Responsible for:
- Extracting agenda data from website
- Parsing Day 1 / Day 2 / Day 3 tabs
- Structuring agenda information

### 2. Knowledge Processing Layer
Responsible for:
- Data normalization
- Chunking
- Embedding generation
- Vector indexing

### 3. Retrieval Layer
Responsible for:
- Semantic search
- Context retrieval
- Similarity matching

### 4. LLM Orchestration Layer
Responsible for:
- Prompt orchestration
- Context injection
- Response generation
- Conversation management

### 5. Chat Interface
Responsible for:
- User interaction
- Query handling
- Conversation continuity

---

# Proposed Technology Stack

## Frontend
- React
- Tailwind CSS
- Chat UI Components

## Backend
- Python / FastAPI OR Node.js
- REST APIs

## AI/LLM
- Gemini
- OpenAI
- Claude

## RAG Components
- LangChain / LangGraph
- Vector Database

## Vector Database Options
- ChromaDB
- Pinecone
- Weaviate

## Embedding Models
- Gemini Embeddings
- OpenAI Embeddings

---

# Agentic AI Roles in A2-SDLC

## Product Analyst Agent
Responsibilities:
- Analyze business requirements
- Generate user stories
- Define acceptance criteria

---

## Knowledge Engineer Agent
Responsibilities:
- Extract agenda data
- Normalize agenda structure
- Create embeddings
- Build vector indexes

---

## Frontend Developer Agent
Responsibilities:
- Generate chatbot UI
- Create responsive layouts
- Implement chat interactions

---

## Backend Developer Agent
Responsibilities:
- Create APIs
- Implement orchestration logic
- Build retrieval pipeline

---

## RAG Engineer Agent
Responsibilities:
- Build retrieval workflows
- Optimize semantic search
- Improve answer grounding

---

## QA Agent
Responsibilities:
- Generate test cases
- Validate response quality
- Detect hallucinations

---

## Security Agent
Responsibilities:
- Validate API security
- Review prompt injection risks
- Review data access controls

---

## DevOps Agent
Responsibilities:
- Deployment automation
- Monitoring setup
- Infrastructure optimization

---

# AI-Augmented SDLC Demonstration Mapping

This project will demonstrate how AI agents participate throughout the SDLC lifecycle.

| SDLC Phase | AI Role |
|---|---|
| Requirement Analysis | Product Analyst Agent |
| Design | Architecture Agent |
| Development | Frontend & Backend Agents |
| Knowledge Engineering | RAG Engineer Agent |
| Testing | QA Agent |
| Security | Security Agent |
| Deployment | DevOps Agent |
| Monitoring | Observability Agent |

---

# Functional Requirements

## FR-1
System shall answer agenda-related questions.

## FR-2
System shall support all three agenda days.

## FR-3
System shall provide session timing information.

## FR-4
System shall identify speakers and topics.

## FR-5
System shall support semantic search.

## FR-6
System shall maintain conversational context.

## FR-7
System shall provide accurate grounded responses.

---

# Non-Functional Requirements

## Performance
- Response time under 5 seconds

## Scalability
- Support concurrent users

## Reliability
- Minimize hallucinations

## Security
- Prevent prompt injection attacks

## Usability
- Simple conversational interface

---

# Success Criteria

The project is considered successful if:

- Users can retrieve agenda information conversationally
- Responses are contextually accurate
- Multi-day agenda understanding works correctly
- AI responses remain grounded to source data
- Demonstration clearly shows AI-Augmented SDLC workflow

---

# Future Enhancements

- Voice interaction
- Personalized recommendations
- Speaker networking suggestions
- Calendar integration
- Mobile app
- Live session updates
- Multi-language support
- Autonomous event concierge agent

---

# Demonstration Narrative for Conference

This project demonstrates:

1. AI-native product development
2. Agentic SDLC orchestration
3. AI role realization
4. Human + AI collaborative engineering
5. Practical enterprise AI workflow
6. Future-ready AI engineering models

The demo showcases how organizations can evolve from:
- AI-assisted coding
to
- AI-orchestrated product engineering

---

# Key Message

"The future of engineering is not humans replacing AI or AI replacing humans.

It is collaborative intelligence across the entire SDLC lifecycle."
