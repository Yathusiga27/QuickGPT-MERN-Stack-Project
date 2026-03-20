# QuickGPT Client

Frontend for the QuickGPT AI assistant app, built with React, Vite, React Router, and Tailwind CSS.

## Current Progress

The client currently includes:

- Chat layout with sidebar navigation and a main chat panel
- Conversation search in the sidebar
- Recent chats list powered by local dummy data
- Community Images page with published image cards
- Credit Plans page with pricing cards and aligned purchase buttons
- Dark mode toggle with theme persistence in `localStorage`
- Mobile sidebar open and close behavior
- Loading screen route

## Current Routes

- `/` - main chat screen
- `/community` - community image gallery
- `/credits` - credit plans page
- `/loading` - loading screen

## Current Data State

This frontend is still using placeholder data from local assets and context:

- user data is mocked
- chat history is mocked
- credit plans are mocked
- community images are mocked

The chat submit flow and backend API integration are not connected yet.

## Tech Stack

- React 19
- Vite
- React Router
- Tailwind CSS 4
- Moment.js
- Prism.js
- React Markdown

## Run Locally

```bash
npm install
npm run dev
```

## Notes

- Theme preference is saved in the browser.
- The current focus is frontend structure and UI progress.
- The next major step is wiring the UI to real authentication, chat, image generation, and payment flows.
