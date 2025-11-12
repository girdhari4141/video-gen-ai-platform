# AI Video Generator SaaS

A full-stack SaaS application that leverages multiple AI services to generate custom videos. Built with Next.js, TypeScript, and TailwindCSS.

## Features

- **AI-Powered Video Generation**: Create unique videos using multiple AI services including GeminiAI, AssemblyAI, and ReplicateAI
- **Credit System**: Built-in credit system for user transactions and service usage
- **Dashboard**: User-friendly dashboard for managing video projects
- **Multiple Video Styles**: Various predefined styles including artistic, realistic, comic, fantasy, and more
- **Real-time Preview**: Live video preview using Remotion
- **Cloud Integration**: Google Cloud and Cloudinary for storage and processing
- **Responsive Design**: Fully responsive UI using TailwindCSS and shadcn/ui components

## Tech Stack

- **Frontend**:
  - Next.js 13+
  - TypeScript
  - TailwindCSS
  - Shadcn UI Components
  - Remotion for video rendering

- **Backend**:
  - MongoDB for data storage
  - Various AI APIs integration
  - Cloudinary for media management

- **AI Services**:
  - GeminiAI
  - AssemblyAI
  - ReplicateAI
  - Google Cloud AI

## Project Structure

```
├── actions/          # Server actions for API integrations
├── app/              # Next.js app directory
├── components/       # React components
│   ├── landing-page/ # Landing page sections
│   ├── modal/       # Modal components
│   ├── nav/         # Navigation components
│   ├── ui/          # Reusable UI components
│   └── video/       # Video-related components
├── context/         # React context providers
├── lib/             # Utility libraries
├── models/          # MongoDB models
├── public/          # Static assets
│   ├── icons/       # Icon assets
│   └── images/      # Image assets
├── remotion/        # Remotion video templates
└── utils/           # Utility functions
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - MongoDB connection string
   - AI service API keys
   - Cloudinary credentials
   - Payment system credentials

4. Run the development server:
   ```bash
   npm run dev
   ```

## Key Features Implementation

- **Video Generation Flow**:
  1. User inputs requirements
  2. AI processes and generates content
  3. Remotion renders the video
  4. Final output is stored in cloud storage

- **Credit System**:
  - Pay-as-you-go model
  - Credit purchase options
  - Usage tracking and management

- **Dashboard**:
  - Project management
  - Video creation interface
  - Usage statistics and credit balance

## Roadmap

- [ ] Additional video styles
- [ ] Batch processing
- [ ] Custom video templates
- [ ] Enhanced editing capabilities
- [ ] Team collaboration features