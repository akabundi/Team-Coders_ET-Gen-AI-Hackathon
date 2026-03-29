# 🌍 AI-Powered Global Mobility Assistant — Our Hackathon Story

## ✨ What Inspires Us
Global mobility today sounds borderless, but in reality it is **confusing, fragmented, and intimidating**.  
Students, remote workers, and professionals often rely on scattered Google searches, agents with conflicting advice, or outdated forums just to answer a simple question:

This gap inspired us to build an **AI-powered Global Mobility Assistant** — a system that doesn’t just display rules, but **understands a user’s profile** and provides **actionable guidance**. Our goal was to reduce uncertainty and make international opportunities more accessible.

## 🚀 Solution

- **Al visa requirement summarizer
- **Country mobility Q&A chatbot
- **Relocation checklist generator
- **Document verification tracker
- **Al confidence score
## Architecture
- **Frontend**: Streamlit
      - **Interactive mobility form UI
      - **Collects country, purpose, job & visa inputs
      - **Sends structured JSON request
- **Backend**: FastAPI
      - **Summary REST endpoint
      - **Visa rule & eligibility engine
      - **Checklist + document mapper
- **AI Layer**
       - **Visa requirement summarizer
      - **Context-based reasoning
      - **Confidence score generator
- **Persistence**: PostgreSQL + Prisma ORM.
- **Safety**: End-to-end type safety with tRPC and Zod.

## ⚖️ Workflow
- User submits mobility details
- Streamlit sends API request
- FastAPI processes rules
- Al generates visa summary
- Confidence score computed
- Results displayed in UI

## 🚀 Impact
- Cuts visa & relocation research time drastically
- Reduces documentation & compliance errors
- Delivers personalized, Al-based mobility guidance
- Scales across countries and visa categories

# 🎯 TARGET USERS
DESIGNED FOR INDIVIDUALS & ORGANIZATIONS NAVIGATING GLOBAL MOBILITY
- **🌍 International Students**
      - **Applying for study visas across multiple countries
      - **Need eligibility validation and document clarity
      - **Require structured checklist generation
      - **Often rely on fragmented embassy or consultant information
- *💼Skilled Professionals & Job Seekers**
      - **Relocating for work or long-term employment
      - **Need country comparison for visa types
      - **Require compliance verification before submission
      - **Seek faster and more reliable decision support
- **🏢HR & Global Mobility Teams**
       - **Managing cross-border employee relocation
      - **Need centralized visa documentation tracking
      - **Require compliance risk reduction
      - **Aim to reduce rejection and processing delays
- **👨‍👩‍👧Families & Dependent Applicants**
       - **Require dependent visa documentation guidance
      - **Need structured relocation planning (healthcare, housing, schooling)
      - **Seek clarity in multi-applicant processes
- **🌐Digital Nomads & Entrepreneurs**
     - **Exploring remote work visa ecosystems
      - **Comparing flexible mobility programs
      - **Need quick AI-powered summaries and eligibility insights

## Setup Instructions
 - 1.Clone the repository using git clone https://github.com/akabundi/Team-Coders_ET-Gen-AI-Hackathon.git then cd Team-Coders_ET-Gen-AI-Hackathon
 - 2. Install required dependencies using pip install -r requirements.txt
 - 3. Setup environment variable for which create .env file in root includes AZURE_OPENAI_KEY=your_api_key and AZURE_OPENAI_ENDPOINT=your_endpoint
 - 4 Run backend server using uvicorn backend.main:app --reload --port 8007
 - 5.Run frontend server using streamlit run frontend/app.py

     
