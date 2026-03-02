# copilot-cli-demo-repo

this is a demo repo for testing the copilot cli skillset

## Quick Start

### Prerequisites
- Python 3.12+ (backend)
- Node.js 20+ (frontend)
- Azure CLI + active subscription
- GitHub Copilot CLI

### 1. Clone and configure
\\\ash
git clone https://github.com/cmccann123/copilot-cli-demo-repo
cd copilot-cli-demo-repo
cp .env.example .env
# Fill in your values in .env
\\\

### 2. Run the backend
\\\ash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
\\\

### 3. Run the frontend
\\\ash
cd frontend
npm install
npm run dev
\\\

Open http://localhost:5173

## Deploy to Azure
\\\ash
azd up
\\\

## Architecture
> TODO: add architecture diagram

## Environment Variables
See \.env.example\ for all required variables.
