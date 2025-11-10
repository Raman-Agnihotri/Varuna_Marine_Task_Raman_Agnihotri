# Fuel EU Frontend

Frontend React application for Fuel EU Maritime compliance platform.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

The frontend will be available at `http://localhost:3000`

## Testing

```bash
npm test
```

## Architecture

This frontend follows hexagonal architecture:
- `core/domain` - Domain entities
- `core/application` - Use cases
- `core/ports` - Interfaces
- `adapters/ui` - React components
- `adapters/infrastructure` - API clients

## Features

- **Routes Tab**: View and manage routes, set baseline
- **Compare Tab**: Compare routes with baseline, view compliance status
- **Banking Tab**: Bank surplus and apply banked amounts
- **Pooling Tab**: Create pools and manage compliance balance transfers

