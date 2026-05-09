# Network Expert System - AI-Powered Network Analysis

## Project Overview
An intelligent expert system for analyzing multi-branch VPN networks using Large Language Models (LLMs) and network automation. The system provides:
- Log analysis and anomaly detection
- Automated troubleshooting recommendations
- Natural language interface for network engineers

## Architecture
- Network Simulation: GNS3 (3 branches connected via VPN)
- AI Core: Llama 3 / Qwen2.5 (local deployment with Ollama)
- RAG Pipeline: ChromaDB + LangChain for log retrieval
- Automation: Netmiko for SSH command execution
- Interface: Streamlit dashboard

## Project Structure
