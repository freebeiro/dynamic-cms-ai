# Dynamic CMS System - MVP Documentation

## Project Overview
A dynamic Content Management System that generates interfaces and queries through natural language processing. The system uses Nyxb UI for components and SQLCoder for query generation, allowing users to interact with databases using plain English.

## Core Features (MVP)

### 1. Natural Language Interface
- Users can request data views using plain English
- System generates appropriate SQL queries
- Handles basic filtering and pagination

### 2. Dynamic UI Generation
- Generates tables, forms, and basic dashboards
- Responsive layouts
- Basic CRUD operations

### 3. Admin Features
- Database connection setup
- Table/column descriptions
- Basic role management

## Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL
- OpenAI API key (for SQLCoder)

### Installation
```bash
# Clone repository
git clone https://github.com/freebeiro/dynamic-cms-ai.git

# Install dependencies
npm install

# Setup environment
cp .env.example .env

# Initialize database
npm run db:init

# Start development server
npm run dev
```

## Technical Stack

### Frontend
- **Nyxb UI**: React component library
- Next.js: React framework
- Tailwind CSS: Styling
- TypeScript: Type safety

### Backend
- **SQLCoder**: Query generation
- PostgreSQL: Database
- NextAuth: Authentication
- tRPC: Type-safe API

## Contributing
- Fork repository
- Create feature branch
- Submit pull request
- Follow coding standards

## License
MIT License