# SENTINEL — Indian Market Intelligence

Premium real-time financial news intelligence for Indian markets.
AI-curated news mapped to specific stocks with sentiment scoring.

## Architecture
- **Backend**: FastAPI (Python 3.11+)
- **Frontend**: Next.js 14 (TypeScript)
- **Database**: PostgreSQL + Redis
- **ML**: FinBERT + spaCy NER
- **Real-time**: WebSocket push alerts

## Quick Start
```bash
# Clone
git clone https://github.com/yourusername/sentinel-finance.git
cd sentinel-finance

# Start everything
docker-compose up --build

# Access
# API: http://localhost:8000/docs
# Web: http://localhost:3000
