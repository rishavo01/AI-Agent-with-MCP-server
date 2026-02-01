AI-Agent-with-MCP-server/
├── client/
├── server/
├── .gitignore
└── README.md


Tech Stack
Server

Node.js

Express

@modelcontextprotocol/sdk

Zod (schema validation)

dotenv

Twitter API (optional tool)

Client

Node.js

@google/genai

@modelcontextprotocol/sdk

dotenv

🚀 Features

MCP-compliant server setup

AI client that connects to MCP server

Tool-based architecture (Twitter tool optional)

Clean separation of client and server

Environment-variable based configuration

⚙️ Prerequisites

Node.js v18 or higher

npm

Git

Google GenAI API key (for client)

(Optional) Twitter API keys

🔧 Setup Instructions
1️⃣ Clone the repository
git clone https://github.com/rishavo01/AI-Agent-with-MCP-server.git
cd AI-Agent-with-MCP-server

2️⃣ Server Setup
cd server
npm install


Create a .env file in server/:

PORT=3000

# Optional (only if using Twitter tool)
TWITTER_API_KEY=
TWITTER_API_SECRET=
TWITTER_ACCESS_TOKEN=
TWITTER_ACCESS_SECRET=


Start the server:

node index.js

3️⃣ Client Setup
cd ../client
npm install


Create a .env file in client/:

GOOGLE_API_KEY=your_google_genai_api_key


Run the client:

node index.js
