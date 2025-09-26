Chat AI App
A modern AI-powered chat application built with Stream Chat, OpenAI, and web search capabilities. This full-stack application provides an intelligent writing assistant that can help with content creation, research, and real-time collaboration.

🚀 Features
Real-time Chat: Powered by GetStream.io for seamless messaging
AI Writing Assistant: OpenAI GPT-4 integration for intelligent content generation
Web Search: Live web search capabilities using Tavily API for current information
Modern UI: Beautiful React interface with dark/light theme support
Writing Prompts: Categorized writing prompts for business, content, communication, and creative tasks
Agent Management: Dynamic AI agent lifecycle management
Secure Authentication: JWT-based token authentication
Responsive Design: Mobile-first design with Tailwind CSS
🏗️ Architecture
Backend (nodejs-ai-assistant/)
Node.js/Express server
Stream Chat server-side integration
OpenAI API for AI responses
Tavily API for web search functionality
Agent management system with automatic cleanup
Frontend (react-stream-ai-assistant/)
React with TypeScript
Stream Chat React components
Tailwind CSS + shadcn/ui for modern styling
Vite for fast development and building
📋 Prerequisites
Node.js 20 or higher
npm or yarn package manager
GetStream.io account (free tier available)
OpenAI API account
Tavily API account (for web search)
**Key Systems:**
AI Agent Management
Dynamic Agent Creation: AI agents are created per chat channel on-demand.

Agent Caching: In-memory cache prevents duplicate agents for the same channel.

Automatic Cleanup: 8-hour inactivity threshold with periodic cleanup.

Race Condition Prevention: Pending agent tracking to prevent duplicate creation.

Web Search Integration
Tavily API: Advanced web search with multiple result sources.

Automatic Search: Triggers web search for current information requests.

Result Synthesis: Combines multiple sources for comprehensive answers.


### Integration Flow

```mermaid
graph TD
    A[Frontend React App] --> B[Stream Chat React Components]
    B --> C[Stream Chat API]
    C --> D[Backend Node.js Server]
    D --> E[OpenAI API]
    D --> F[Tavily Web Search]
    D --> G[AI Agent Management]
```




## 📚 Technologies Used

### Backend

- **Node.js** - Runtime environment
- **Express** - Web framework
- **Stream Chat** - Real-time messaging
- **OpenAI** - AI language model
- **Axios** - HTTP client
- **CORS** - Cross-origin resource sharing
- **TypeScript** - Type safety

### Frontend

- **React** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool
- **Stream Chat React** - Chat UI components
- **Tailwind CSS** - Styling
- **Radix UI** - Accessible components
- **React Hook Form** - Form handling
- **React Router** - Navigation

  <img width="1348" height="441" alt="Screenshot 2025-09-26 132511" src="https://github.com/user-attachments/assets/90d24425-b192-42cf-bd92-bb9b363b682f" />
  <img width="1449" height="803" alt="Screenshot 2025-09-26 132746" src="https://github.com/user-attachments/assets/1ed4d6e1-d670-46d3-90eb-32952bd948d0" />
  <img width="1079" height="239" alt="Screenshot 2025-09-26 133320" src="https://github.com/user-attachments/assets/111b3420-ff57-4acb-86aa-bbe821d1556b" />
  <img width="1042" height="577" alt="Screenshot 2025-09-26 133703" src="https://github.com/user-attachments/assets/392ad5c2-2759-4f4a-9fc2-2020fa4dc68c" />


  


