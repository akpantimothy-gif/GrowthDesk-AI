# GrowthDesk AI

**AI-powered web platform for Nigerian marketing agencies**

GrowthDesk AI is an internal capstone project designed to transform how Nigerian marketing agencies work. It uses generative AI to turn hours of manual research and writing into minutes of AI-assisted output.

## Core Value Proposition

"Turn hours of manual research and writing into minutes of AI-assisted output — tailored for the Nigerian market context."

## Features

### 6 Core Modules

1. **Prospect Finder** - Generate qualified prospect lists with business problems and outreach angles
2. **Outreach Generator** - Create multi-channel outreach materials (email, LinkedIn, WhatsApp, call scripts)
3. **Market Intelligence** - Generate comprehensive market reports with trends, competitors, and opportunities
4. **Proposal Generator** - Build structured proposals with executive summaries, timelines, and KPIs
5. **Brief Interpreter** - Analyze client briefs and extract actionable insights
6. **Concept Note Generator** - Create creative concept notes with visual directions and copy lines

## Target Users

- **Business Development Managers** - Prospect research and outreach
- **Strategy Leads** - Market intelligence and analysis
- **Project Managers** - Proposal generation and brief interpretation
- **Creative Directors** - Concept development and creative direction

## Tech Stack

- **Frontend:** React 18 + TypeScript, Tailwind CSS, shadcn/ui, Zustand
- **Backend:** Node.js + Express, PostgreSQL, Prisma ORM
- **AI:** OpenAI GPT-4o API
- **Auth:** NextAuth.js (email + Google SSO)
- **Deployment:** Vercel (frontend), Railway (backend + DB)

## Project Structure

```
growthdesk-ai/
├── apps/
│   ├── frontend/          # React + Next.js
│   └── backend/           # Express + PostgreSQL
├── packages/
│   └── shared/            # Shared types and utilities
├── docs/
│   └── database/          # Schema and migrations
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL 14+
- OpenAI API key

### Installation

```bash
# Clone repository
git clone https://github.com/akpantimothy-gif/GrowthDesk-AI.git
cd GrowthDesk-AI

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env.local
# Edit .env.local with your credentials

# Run migrations
cd apps/backend
npm run db:migrate

# Start development servers
npm run dev
```

Frontend will run on `http://localhost:3000`
Backend will run on `http://localhost:4000`

## Database Schema

See `/docs/database/schema.sql` for complete schema.

## API Documentation

See `/docs/api.md` for endpoint documentation.

## Contributing

This is an internal capstone project. Team members should follow the contribution guidelines in the project wiki.

## License

Internal use only.
