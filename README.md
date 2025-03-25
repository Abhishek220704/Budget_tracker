# Ocular - Budget Tracking Application

## Overview

Ocular is a simplistic, straight-forward budgeting tool designed to help users manage their finances effectively. The application provides an intuitive interface for tracking expenses, analyzing financial data, and gaining insights into personal spending habits.

## Features

- User Authentication (Firebase)
- Responsive Design
- Glassmorphic UI
- Mobile-Friendly
- Secure Login/Signup

## Technologies Used

- Vue.js 3
- TypeScript
- Firebase Authentication
- Vite
- Vue Router
- Vue I18n
- ECharts
- SASS

## Prerequisites

- Node.js (v22+)
- pnpm (Package Manager)

## Getting Started

### Installation

1. Clone the repository
```bash
git clone https://github.com/Abhishek220704/Budget_tracker.git
cd Budget_tracker
```

2. Install dependencies
```bash
pnpm install
```

### Development

Run the development server:
```bash
pnpm dev:frontend
```

### Building

To build the project:
```bash
pnpm build
```

### Linting

To lint the project:
```bash
pnpm lint
```

### Testing

To run tests:
```bash
pnpm test
```

## Project Structure

- `src/`: Source code directory
- `public/`: Static assets
- `index.html`: Main HTML entry point
- `package.json`: Project configuration and scripts
- `vite.config.ts`: Vite configuration

## Authentication

The application uses Firebase Authentication with email/password registration and login.

## Deployment

The project is set up to be deployed at `https://ocular.reinisch.io/`
