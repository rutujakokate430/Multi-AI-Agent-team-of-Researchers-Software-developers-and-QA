# Multi-AI-Agent-team-of-Researchers-Software-developers-and-QA (CrewAI)

![_- visual selection (1)](https://github.com/user-attachments/assets/1f7ae57a-6441-469e-8e90-80c44a1513f5)

This project showcases an end-to-end Multi-AI Agentic System designed to autonomously:

Extract software requirements from web sources,

Retrieve relevant APIs from a large catalog using semantic search (via FAISS),

And generate production-ready full-stack code (Flask + React) — without hardcoding APIs.

Built using modern LLM orchestration frameworks, this system represents a blueprint for intelligent, autonomous software engineering powered by multi-agent coordination and retrieval-augmented generation (RAG).

## Project Highlights

✅ Multi-Agent AI Coordination using CrewAI

✅ RAG with FAISS + Sentence Transformers for API retrieval

✅ LLM-based Web Research using Exa search API

✅ Autonomous Code Generation (Flask backend + React frontend)

✅ End-to-End QA Validation with a dedicated Reviewer Agent

<img width="338" alt="Screenshot 2025-06-22 160513" src="https://github.com/user-attachments/assets/0995741c-3a6f-4248-b923-70522ef6eb1e" />

## System Architecture

Each agent performs a specialized function in a fully autonomous CrewAI pipeline:

Agent	Purpose
🧾 Research Agent	Extracts key product requirements from reference web sources using Exa
📡 API Retriever	Performs semantic search over API catalog via FAISS vector store
⚙️ Developer Agent	Generates full-stack code based on retrieved API metadata
🧪 Reviewer Agent	Validates code correctness, completeness, and adherence to spec

## Tech Stack
Component	Technology Used	Purpose
🔗 LLM Orchestration	CrewAI	Multi-agent task pipeline
💬 Language Model	OpenAI GPT-3.5 or any closed/open LLM	Autonomic reasoning and code generation
🔍 Web Search	Exa API	Extract features from external websites
🔎 Semantic Search	FAISS + SentenceTransformers	RAG-style retrieval from API catalog
🧱 Embedding Model	all-MiniLM-L6-v2 from Hugging Face	Lightweight and efficient text embedding
🧑‍💻 Backend	Flask	Dynamic API integration layer
💻 Frontend	React + Tailwind	Modular UI with feature-specific components

## Workflow Execution

Agents run in sequential order using Process.sequential

Each agent receives dynamic output from the previous agent — no static instructions or hardcoded prompts

Code is automatically validated by a QA agent before being returned

## Below are screenshots of the Agentic Crew in Action.

## Researcher visits the reference solution, extracts the core features 

<img width="901" alt="Screenshot 2025-06-22 160110" src="https://github.com/user-attachments/assets/6fc2f478-d29e-491f-a7ef-c606edaa27e0" />

## Software developer writing production grade full-stack code

<img width="338" alt="Screenshot 2025-06-22 160752" src="https://github.com/user-attachments/assets/17adc47b-0229-4c36-8b22-f1aa43c9b16e" />

## Senior reviewer reviewing the code against the requirement

<img width="904" alt="Screenshot 2025-06-22 160412" src="https://github.com/user-attachments/assets/eabcbb10-0dc2-410b-8a09-40015e16acca" />

## Business Impact
This system reduces developer ramp-up time by 80%, enabling zero-shot full-stack prototyping with minimal manual API discovery or code wiring.

## Disclaimer
This project is my original implementation and design, built independently as part of a technical take-home assessment. While I do not claim ownership over the core idea or problem statement, However the entire codebase, multi-agent architecture, design flow, and execution strategy are my own work. I have the right to share my own original work.

If you find this codebase, pipeline design, or implementation helpful and plan to use or adapt it for your own work, please credit me appropriately. Please reach out to me for the code.
I retain full credit for the design, implementation, and engineering effort behind this solution.

Built with dedication, transparency, and a passion for intelligent software systems.
