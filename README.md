# Production-Grade Retrieval-Augmented Generation (RAG) Platform

A production-oriented Retrieval-Augmented Generation (RAG) application built step by step as part of my YouTube tutorial series.

This project goes beyond a basic “upload a PDF and ask questions” demo. The goal is to show how a more realistic AI application can be structured when we also need authentication, organizations, user roles, document management, vector search, rate limiting, security, testing, health checks, and a usable frontend.

The backend is built with **FastAPI and Python**, while the frontend uses **Next.js and TypeScript**. MySQL stores relational application data, Chroma handles vector search, Redis is used for rate limiting and protection, Hugging Face models generate embeddings, and Gemini is used as the Large Language Model (LLM).

