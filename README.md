# DevOps SimOps Ecosystem

A comprehensive simulation of a DevOps environment demonstrating CI/CD pipelines, containerization, monitoring, and AI-powered insights using Google's Gemini AI.

![Project Screenshot](https://drive.google.com/uc?export=view&id=1_K3iRs9lsetgRvSWLBFKjPXE_bdDLAOV)


## Features

- **CI/CD Pipeline Visualization**: Interactive pipeline diagrams showing build, test, and deployment stages
- **Real-time Monitoring**: Charts and metrics for system performance and health
- **AI-Powered Assistance**: Chat with an AI DevOps engineer for guidance on DevOps concepts, troubleshooting, and best practices
- **Log Analysis**: Upload and analyze build logs with AI recommendations
- **Containerization Insights**: Docker and Kubernetes workflow simulations

## Tech Stack

- **Frontend**: React 19 with TypeScript
- **Build Tool**: Vite
- **AI Integration**: Google Gemini AI
- **Charts**: Recharts for data visualization
- **Icons**: Lucide React

## Prerequisites

- Node.js (v16 or higher)
- A Google Gemini API key

## Setup and Installation

1. **Clone the repository** (if applicable):
   ```bash
   git clone <repository-url>
   cd devops-simops-ecosystem
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   - Copy `.env.local` and add your Gemini API key:
   ```
   VITE_GEMINI_API_KEY=your_api_key_here
   ```

4. **Run the development server**:
   ```bash
   npm run dev
   ```

   The app will be available at `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally

## Project Structure

```
src/
├── components/          # React components
│   ├── MonitoringCharts.tsx
│   ├── PipelineVisualizer.tsx
│   ├── Sidebar.tsx
│   └── TerminalWindow.tsx
├── services/            # API and utility services
│   └── geminiService.ts
├── App.tsx             # Main application component
├── index.tsx           # React entry point
└── types.ts            # TypeScript type definitions
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is for educational and demonstration purposes.
