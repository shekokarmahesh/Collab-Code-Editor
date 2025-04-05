# Collaborative Code Editor

A real-time collaborative code editor built with React, TypeScript, and Yjs for seamless multi-user editing experience.

## Features

- Real-time collaborative editing
- Monaco Editor integration for rich code editing experience
- WebSocket-based synchronization
- TypeScript support
- Modern React-based frontend
- Express.js backend

## Tech Stack

### Frontend
- React 18
- TypeScript
- Vite
- Monaco Editor
- Yjs & Y-WebSocket
- ESLint for code quality

### Backend
- Node.js
- Express.js
- WebSocket
- Y-WebSocket
- CORS support

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd collab-coe-editor
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

### Running the Application

1. Start the backend server:
```bash
cd backend
npm start
```

2. Start the frontend development server:
```bash
cd frontend
npm run dev
```

The application will be available at `http://localhost:5173` (frontend) and the backend will run on the configured port.

## Project Structure

```
collab-coe-editor/
├── backend/              # Backend server
│   ├── src/             # Source code
│   ├── package.json     # Backend dependencies
│   └── .gitignore
├── frontend/            # Frontend application
│   ├── src/            # Source code
│   ├── public/         # Static assets
│   ├── package.json    # Frontend dependencies
│   └── vite.config.ts  # Vite configuration
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.

## Acknowledgments

- [Yjs](https://github.com/yjs/yjs) for the collaborative editing framework
- [Monaco Editor](https://microsoft.github.io/monaco-editor/) for the code editor
- [React](https://reactjs.org/) for the frontend framework
