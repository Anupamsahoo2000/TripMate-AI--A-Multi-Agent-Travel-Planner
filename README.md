# 🌍 TripMate AI — A Multi-Agent Travel Planner

TripMate AI is an intelligent, multi-agent travel planning system built with LangGraph, LangChain, and FastAPI. It orchestrates specialized AI agents to generate customized travel itineraries, recommendations, and logistics for travelers.

---

## ✨ Features

- **Multi-Agent Orchestration**: Powered by LangGraph to coordinate dedicated agents for flights, stays, activities, and budget planning.
- **Real-Time Web Intelligence**: Uses Tavily search to fetch the latest travel alerts, weather forecasts, and destination insights.
- **Airport & Destination Intelligence**: Integrates `airportsdata` and `pycountry` for airport code lookup and location data.
- **Persistent State & Checkpointing**: Built-in state management using PostgreSQL checkpointing for conversation tracking and workflow resumption.
- **FastAPI Backend**: High-performance RESTful API powering travel planning endpoints.

---

## 🛠️ Tech Stack

- **Language & Package Manager**: Python 3.12+, [uv](https://github.com/astral-sh/uv)
- **Agent Framework**: LangChain, LangGraph, LangChain-Groq
- **API Framework**: FastAPI, Uvicorn
- **Search & Tools**: Tavily Search, AirportsData, PyCountry
- **Database & Persistence**: PostgreSQL (`psycopg`, `langgraph-checkpoint-postgres`)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.12 or higher installed
- [uv](https://docs.astral.sh/uv/) package manager installed
- PostgreSQL instance running (optional for local checkpointing)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Anupamsahoo2000/TripMate-AI--A-Multi-Agent-Travel-Planner.git
   cd "TripMate AI-A Multi Agent Travel Planner"
   ```

2. **Install dependencies:**
   ```bash
   uv sync
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the root directory:
   ```env
   GROQ_API_KEY=your_groq_api_key
   TAVILY_API_KEY=your_tavily_api_key
   DATABASE_URL=postgresql://user:password@localhost:5432/tripmate
   ```
