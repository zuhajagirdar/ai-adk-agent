# 🚀 Planetary AI Agent using Google ADK

## Overview
This project is an AI-powered planetary information agent built using Google ADK and Gemini.

It processes user queries about planets, moons, and space missions, and generates structured, informative responses.

## How it Works
1. User provides a query (planet or space topic)
2. Agent stores query using tool
3. Research agent gathers data using:
   - Wikipedia API
4. Formatter agent converts data into a mission-style response

## Architecture
- Root Agent (Greeter)
- Sequential Agent Workflow:
  - Research Agent
  - Response Formatter

## Features
- Multi-agent workflow using ADK
- Integration with external knowledge (Wikipedia)
- Structured response generation
- Clean separation of logic

## Tech Stack
- Python
- Google ADK
- Google Gemini
- LangChain
- Wikipedia API
- Cloud Run

## Project Presentation

You can view the full project submission here:

[Download PPT/PDF](zuha_jagirdar_apac.pdf)

## Author
Zuha Jagirdar
