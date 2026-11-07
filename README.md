# Press

Open-source gym logging platform built for precision, data, and a premium user experience.

| Badge | |
|---|---|
| License | [ISC](https://opensource.org/licenses/ISC) |
| Status | Active |

## Features

- **Anatomical Mapping**: Visualize muscle engagement with integrated 3D/anatomical models.
- **Progression Engine**: Track lifts with granular detail and rolling performance metrics.
- **Privacy First**: Fully open-source and self-hostable.
- **Developer Centric**: Monorepo architecture with AI-optimized documentation.

## Tech Stack

- **Core Architecture**: TurboRepo (Monorepo)
- **Frontend**: Next.js + React + TypeScript
- **Visuals**: Three.js + React Three Fiber + Framer Motion
- **Styling**: Tailwind CSS v4
- **State Management**: Zustand
- **Backend**: Node.js + Express 5
- **Database**: PostgreSQL + Knex.js
- **Validation**: Zod

## Project Structure

```text
press/
├── apps/
│   ├── frontend/      # Next.js web application
│   └── backend/       # Express API server
├── packages/
│   └── data/          # Shared data definitions and constants
└── docs/              # AI-Optimized Documentation
```

## AI-Ready Documentation

This project is designed to be highly compatible with AI coding assistants.

| Doc | Path |
|---|---|
| Architecture | `docs/architecture.md` |
| Data Schema | `docs/data-schema.md` |
| Design System | `docs/design.md` |
| Security | `docs/security.md` |
| Environment | `docs/env.md` |

## Getting Started

### Prerequisites

- Node.js (Latest LTS)
- PostgreSQL
- npm (v11+)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/JoshRiang/press.git
   cd press
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   Follow `docs/env.md` to set up `.env` files in both `apps/frontend` and `apps/backend`.

4. **Run in development mode**:

   ```bash
   npm run dev
   ```

## Contributing

Press is an open-source project. We welcome contributions of all kinds! Please check the issues or submit a pull request.

## License

This project is licensed under the [ISC License](LICENSE).

### Made With Love By

Joshua Richardo Riangkamang