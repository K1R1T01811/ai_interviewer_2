# Prepwise — AI-Powered Mock Interview Platform

Prepwise is an AI-powered mock interview platform designed to help candidates prepare for job interviews through interactive, voice-based interview sessions. The platform allows users to generate personalized interviews, interact with an AI interviewer in real time, and receive structured feedback to evaluate and improve their performance.

The application combines conversational AI, voice interaction, authentication, and interview analytics to create a more realistic and accessible interview preparation experience.

## Features

- **AI-Generated Interviews:** Generate interview questions tailored to specific job roles, technical domains, and experience levels.
- **Real-Time Voice Interviews:** Interact with an AI interviewer through voice-based conversations.
- **Personalized Feedback:** Receive AI-generated evaluations based on interview responses and conversation context.
- **Interview Transcripts:** Review interview conversations and responses after completing a session.
- **Interview Dashboard:** Create, access, and manage previous interview sessions in one place.
- **Authentication:** Secure user sign-up and sign-in functionality.
- **Responsive Interface:** A clean, responsive interface designed for desktop and mobile devices.

## Tech Stack

| Technology | Purpose |
|---|---|
| Next.js | Frontend and server-side application logic |
| React | Component-based UI development |
| TypeScript | Type-safe application development |
| Tailwind CSS | Styling and responsive UI |
| Firebase | Authentication and data storage |
| Vapi AI | Real-time voice interaction and AI interviewer |
| Google Gemini | AI-powered question generation and feedback |
| shadcn/ui | Reusable UI components |
| Zod | Schema validation |

## Application Workflow

1. **Authentication:** Users sign up or sign in to access their interview dashboard.
2. **Interview Creation:** Users configure an interview based on relevant parameters such as job role, technical focus, or interview type.
3. **Question Generation:** AI generates relevant interview questions based on the selected configuration.
4. **Voice Interview:** Users participate in an interactive interview session with a voice-enabled AI interviewer.
5. **Evaluation:** Interview responses and conversation context are processed to generate feedback.
6. **Review:** Users review their feedback and interview history to identify areas for improvement.

## Project Structure

```text
├── app/
│   ├── (auth)/
│   ├── (root)/
│   ├── api/
│   └── ...
├── components/
├── constants/
├── firebase/
├── lib/
├── public/
├── types/
├── .env.local
└── README.md
```

## Getting Started

### Prerequisites

- Node.js
- npm
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

Navigate to the project directory:

```bash
cd YOUR_REPOSITORY
```

Install dependencies:

```bash
npm install
```

### Environment Configuration

Create a `.env.local` file in the root directory and configure the following environment variables:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

Configure the required Firebase, Vapi, and Google Gemini credentials before running the application.

### Run Locally

Start the development server:

```bash
npm run dev
```

Open the application in your browser:

```text
http://localhost:3000
```

## Future Enhancements

- Interview performance analytics and progress tracking
- Improved feedback categorization across technical and behavioral interviews
- Difficulty-based interview configurations
- Additional interview domains and job-specific question sets
- Enhanced interview history and performance comparison

## License

This project is intended for learning, development, and personal portfolio purposes.
