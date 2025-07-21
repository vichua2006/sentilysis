# Sentilysis @ SpurHacks 2025
## 🚀 Inspiration
We wanted to make real-time stock sentiment and global event analysis accessible and visually engaging for everyone. With so much financial news and data, it’s hard to see the big picture so we built Sentilysis to combine AI, live data, and interactive visuals in a single dashboard.

## How we built it
Frontend: Next.js (React), Tailwind CSS, Chart.js for charts, and Three.js for the animated globe. Backend: FastAPI for news aggregation, sentiment analysis, and AI-powered summaries. AI: Integrated with OpenAI for natural language sentiment summaries. Deployment: Vercel for frontend, backend hosted separately (e.g., Render/Railway). Features: Custom skeleton loaders for smooth UX, scrollable chat, and responsive design.

## Challenges
API integration: Handling CORS and environment variables for backend/frontend communication, especially in production. UI/UX: Making the dashboard visually appealing and responsive, with smooth loading states. Data consistency: Ensuring real-time updates and accurate sentiment aggregation from multiple sources. Globe rendering: Integrating Three.js with React and keeping performance smooth.

