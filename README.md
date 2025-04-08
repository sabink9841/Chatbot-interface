# Chat Bot Interface

A clean, responsive chat bot user interface with a modern design built with React, Express, and TypeScript.

## Features

- Professional blue theme with modern UI components
- Real-time message display with typing indicators
- Responsive design that works on desktop and mobile
- Expandable text input area
- Simple bot responses based on user message keywords
- Session-based conversations that persist between page refreshes

## Tech Stack

- **Frontend**: React with TypeScript
- **Backend**: Node.js with Express
- **Styling**: Tailwind CSS with shadcn/ui components
- **State Management**: TanStack React Query

## Setup & Installation

1. Clone this repository
   ```
   git clone https://github.com/your-username/chatbot-interface.git
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Start the development server
   ```
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5000`

## How It Works

The application has a simple architecture:

- Frontend React components handle the UI and user interactions
- Messages are sent to the Express backend via API calls
- The backend stores messages in memory and generates simple bot responses
- React Query is used to fetch and update messages in real-time

## Extending the Bot

The bot currently uses keyword matching to generate responses. To make it smarter, you could:

1. Modify the `generateBotResponse` function in `server/routes.ts`
2. Connect it to a more sophisticated NLP service or AI API
3. Add additional response categories and conversation flows

## License

MIT
