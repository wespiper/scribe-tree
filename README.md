# Scribe Tree

A writing education platform that uses version control concepts to teach and improve writing skills.

## 📚 **Documentation**

Comprehensive documentation is available in the [`docs/`](./docs/) directory:
- **Implementation Roadmaps**: Development phases and current priorities
- **Educational Philosophy**: Bounded Enhancement for Learning principles  
- **Testing Guides**: Setup procedures and workflow testing

**Current Priority**: [Phase 5 - AI Enhancement Implementation](./docs/roadmaps/PHASE_5_AI_ENHANCEMENT_PLAN.md)

## Project Structure

```
scribe-tree/
├── frontend/          # React + TypeScript + Vite frontend
├── backend/           # Node.js + Express + TypeScript backend
└── README.md          # Project documentation
```

## Tech Stack

### Frontend
- **React 18** - User interface framework
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Styling
- **ShadCN UI** - Component library

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **TypeScript** - Type safety
- **MongoDB** - Database
- **Mongoose** - ODM for MongoDB

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- Git

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd scribe-tree
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install backend dependencies:
```bash
cd ../backend
npm install
```

4. Set up MongoDB and environment:
```bash
# MongoDB is included in the project - no separate installation needed!
# Environment is already configured in backend/.env
```

### Development

1. Start MongoDB (Terminal 1):
```bash
./start-mongodb.sh
```

2. Start the backend server (Terminal 2):
```bash
cd backend
npm run dev
```

3. Start the frontend development server (Terminal 3):
```bash
cd frontend
npm run dev
```

The frontend will be available at `http://localhost:5173` and the backend at `http://localhost:5001`.

### MongoDB Management

```bash
# Start MongoDB
./start-mongodb.sh

# Stop MongoDB  
./stop-mongodb.sh

# Check if MongoDB is running
ps aux | grep mongod
```

## Features (Planned)

- **Writing Projects** - Create and manage writing projects like Git repositories
- **Version Control** - Track changes and revisions in writing
- **Branching** - Work on different versions or drafts
- **Collaboration** - Multiple writers can work on the same project
- **Merge Conflicts** - Learn to resolve conflicting edits
- **Commit Messages** - Practice describing changes effectively
- **Pull Requests** - Peer review for writing improvements

## API Endpoints

### Health Check
- `GET /api/health` - Check if the API is running

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test your changes
5. Submit a pull request

## License

This project is licensed under the MIT License.