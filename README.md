# Crafter

Crafter is a Vite + React + TypeScript web app for helping small businesses create and manage their online presence. It combines AI-assisted website generation with practical marketing tools such as email content creation, business insights, chatbot support, analytics, and community features.

The goal of the project is to give founders and small teams a simple dashboard where they can describe their business, generate useful content, and launch faster without needing to design or code everything from scratch.

## Tech Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- Firebase
- Gemini API

## Features

- AI website generation from a business description
- Email marketing content generation
- Business insight and competitor analysis tools
- Dashboard for tracking activity and progress
- Firebase authentication and user onboarding
- Responsive UI built with Tailwind CSS and shadcn/ui

## Project Structure

- `src/pages` contains route-level screens such as landing, auth, onboarding, and dashboard pages.
- `src/components` contains reusable layout, dashboard, and UI components.
- `src/lib` contains Firebase, authentication, database, and AI service logic.
- `src/hooks` contains shared React hooks.

## Getting Started

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Run lint checks:

```bash
npm run lint
```

## Environment

Create a `.env` file for local API keys and Firebase configuration. At minimum, Gemini-powered features expect:

```bash
VITE_GEMINI_API_KEY=your_api_key_here
```
