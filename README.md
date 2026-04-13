# ✈️ AI Trip Planner

> **Vignan University · B.Tech CSE · Final Year Project**

A hybrid AI-powered travel planner that combines **real-world tourism datasets** (1M+ records) with **Google Gemini AI** to generate personalized trip itineraries.

## 🗂️ Project Structure

```
Ai-Based Trip Planning/
├── Aitrip/                    # Main application
│   ├── src/               # React frontend
│   ├── backend/           # Express + Flask APIs
│   └── PROJECT_OVERVIEW.html  # Visual overview (open in browser)
├── Trip_Planner.ipynb       # ML model notebook (reference)
└── walkthrough.md        # Full documentation
```

## 🚀 Quick Start

```bash
# Frontend
cd Aitrip && npm install && npm run dev

# Backend (Terminal 2)
cd Aitrip && npm run backend

# ML API (Terminal 3)  
cd Aitrip && npm run ml-api
```

## 📊 Data Sources

| Dataset | Records | Purpose |
|--------|---------|---------|
| TBO Hotels | 1M+ | Hotel recommendations |
| Zomato | 123K | Restaurant data |
| Tourist Places | 325 | Attractions |

## ✨ Features

- AI itinerary generation (Gemini 2.5 Flash Lite)
- Real hotel/restaurant/attraction recommendations
- PDF export, weather widget, cost estimator
- Google OAuth + email authentication
- Trip history & favorites
- User ratings (1-5 stars)

## 📄 License

MIT