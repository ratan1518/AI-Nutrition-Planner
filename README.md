# AI Travel Planner

A Streamlit app that generates personalised day-wise travel itineraries from a user's preferences, budget and trip duration.

## Features
- LLM-generated itineraries using structured prompts (OpenRouter API)
- Hotel recommendations
- Maps and destination images (Pexels API)
- Downloadable PDF itinerary

## Tech stack
Python, Streamlit, OpenRouter API, Pexels API

## Run locally
```bash
git clone https://github.com/ratan1518/AI-Travel-Planner.git
cd AI-Travel-Planner
pip install -r requirements.txt
export OPENROUTER_API_KEY=your_key_here
export PEXELS_API_KEY=your_key_here
streamlit run app.py
```
(verify file and variable names)

## How it works
1. The user enters destination, budget, trip length and preferences
2. The app builds a structured prompt and calls the LLM
3. The itinerary, hotels, maps and images are displayed
4. The user can export the plan as a PDF
