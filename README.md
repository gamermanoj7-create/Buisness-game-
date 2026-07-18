Business Game — MVP (React + Node/TypeScript)

Structure:
- /server - Node/Express API + simulation engine
- /client - React + TypeScript frontend

Requirements:
- Node 18+ and npm

Run locally:
1. In project root open two terminals.
2. Server:
   cd server
   npm install
   npm run dev
   (server runs at http://localhost:4000)
3. Client:
   cd client
   npm install
   npm run dev
   (client runs at http://localhost:5173)

Gameplay:
- Frontend shows current KPIs and decision inputs each turn.
- Press "Resolve Turn" to send decisions to server; server returns updated game state.
- Play for multiple turns.