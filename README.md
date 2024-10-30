Events Management Application

A full-stack React application for managing and discovering events. Users can create, edit, search, and delete events with real-time updates using React Query.
Features

📅 Create and manage events
🔍 Search functionality
🖼️ Image selection for events
⚡ Real-time updates
📱 Responsive design

Tech Stack

Frontend: React + Vite
State Management: TanStack Query (React Query)
Backend: Express.js
Routing: React Router
Styling: CSS3

Quick Start
Running Locally

Clone the repository
Install dependencies:
bashCopynpm install
cd backend && npm install

Start the backend server:
bashCopycd backend
npm start

Start the frontend development server:
bashCopynpm run dev


Using CodeSandbox

Frontend: Open in CodeSandbox
Backend: Open in CodeSandbox

Environment Variables
Create a .env file in the root directory:
CopyVITE_API_URL=your-backend-url
API Endpoints

GET /events - List all events
GET /events/:id - Get single event
POST /events - Create new event
PUT /events/:id - Update event
DELETE /events/:id - Delete event
GET /events/images - Get available images

License
MIT