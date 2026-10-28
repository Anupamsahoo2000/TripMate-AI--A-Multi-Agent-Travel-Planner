# 🌍 TripMate AI — A Multi-Agent Travel Planner

TripMate AI is an intelligent, multi-agent travel planning system built with LangGraph, LangChain, and FastAPI. It orchestrates specialized AI agents to generate customized travel itineraries, recommendations, and logistics for travelers.

---

## ✨ Features

- **Multi-Agent Orchestration**: Powered by LangGraph to coordinate dedicated agents for flights, stays, activities, and budget planning.
- **Real-Time Web Intelligence**: Uses Tavily search to fetch the latest travel alerts, weather forecasts, and destination insights.
- **Airport & Destination Intelligence**: Integrates `airportsdata` and `pycountry` for airport code lookup and location data.
- **Persistent State & Checkpointing**: Built-in state management using PostgreSQL checkpointing for conversation tracking and workflow resumption.
- **FastAPI Backend**: High-performance RESTful API powering travel planning endpoints.
