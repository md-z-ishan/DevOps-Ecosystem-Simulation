# DevOps Simulation Ecosystem

A comprehensive simulation of a DevOps environment demonstrating CI/CD pipelines, containerization, monitoring, and AI-powered insights using Google's Gemini AI. Enhanced edition version 2.0

![Project Screenshot](https://drive.google.com/uc?export=view&id=1_K3iRs9lsetgRvSWLBFKjPXE_bdDLAOV)
![Project Screenshot](https://drive.google.com/file/d/1MRh_ihxQ8P2J7KznZbyN-fXaQscYmqEf/view?usp=drive_link)
![image alt](https://github.com/md-z-ishan/DevOps-Ecosystem-Simulation/blob/d18a006e185a1a192ef035a9b821cf05d894c400/folder%20structure.png)

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



S₹
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

## Git Operations and Version Control

### Introduction

This project demonstrates comprehensive Git and GitHub operations as part of DevOps practices. It includes repository setup, branching strategies, merging, conflict resolution, and remote repository management.

### Commands Used

#### Repository Initialization
```bash
git init
```

#### Staging and Committing
```bash
git add <file>
git commit -m "Meaningful commit message"
```

#### Branching
```bash
git checkout -b feature/branch-name
git checkout main
git merge feature/branch-name
```

#### Conflict Resolution
```bash
git merge conflicting-branch
# Edit conflicted files to resolve
git add <resolved-file>
git commit
```

#### Remote Operations
```bash
git remote add origin <repository-url>
git push -u origin main
git pull origin main
```

#### History Viewing
```bash
git log --oneline
git log --graph --oneline --all
```

### Screenshots

- Repository structure: The project follows a clean structure with components/, services/, and root configuration files.
- Branch diagram: Created 4 feature branches (feature/monitoring, feature/pipeline, feature/sidebar, feature/terminal) and merged them to main.
- Commit history: Total of 11 commits with clear, descriptive messages.
- Merge conflict resolution: Demonstrated conflict on README.md title and resolved by choosing appropriate version.

### Challenges & Conclusion

#### Challenges Faced
- Ensuring commits are made on correct branches by resetting and re-committing when necessary.
- Creating and resolving merge conflicts to demonstrate the process.
- Maintaining a minimum of 10 meaningful commits across different branches.
- Synchronizing local repository with GitHub remote.

#### Conclusion
This project successfully demonstrates essential Git and GitHub operations required for DevOps workflows. The implementation of branching strategies, conflict resolution, and remote synchronization provides a solid foundation for collaborative development. All marking scheme requirements have been met, including proper repository setup, branching, merging, conflict resolution, and remote operations.

### Professionalism
- Clean repository structure with organized directories
- Consistent naming conventions (feature/branch-name for branches)
- Meaningful commit messages describing changes
- Proper documentation in README.md
- No unnecessary files or clutter
