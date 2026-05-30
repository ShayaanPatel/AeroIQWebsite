# AeroIQ

AeroIQ is an AI-powered flight search assistant that helps users discover flights through natural language. Instead of filling long forms and filters, users can simply describe where they want to go, when they want to travel, and what kind of option they prefer.

The project includes a premium landing page for the AeroIQ-Flight-AI-Agent, a custom full-screen chat interface, Telegram bot access, and live webhook integration for AeroIQ responses.

## Overview

AeroIQ is designed to make flight search feel fast, conversational, and modern. Users can ask questions like:

- “Cheapest Mumbai to Dubai, 20 May, 1 adult”
- “Fastest Delhi to Singapore, 15 May, 2 adults”
- “Best value London to Tokyo, 10 June, 1 adult”
- “Mumbai to Goa round trip, 30 May return 2 June”

The app then sends the user’s message to an AI workflow and displays the response in a clean chat interface.

## Features

- AI-powered natural language flight search
- Premium landing page with modern dark UI
- Custom full-screen chat experience
- Direct webhook integration for AI responses
- Telegram bot call-to-action
- Saved chat session using local storage
- Conversation history sidebar
- Responsive design for desktop and mobile
- Smooth animations with Framer Motion
- Vercel-ready deployment configuration

## Tech Stack

- React
- Vite
- Tailwind CSS
- Framer Motion
- Lucide React
- Vercel

## Project Structure

```txt
AeroIQ/
├── src/
│   ├── App.jsx
│   ├── ChatPage.jsx
│   ├── GlobeScene.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── vite.config.js
├── vercel.json
└── .env.example
