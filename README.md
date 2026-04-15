# SarthCloudX

A modern Next.js web application for cloud service management with authentication, admin and user dashboards, contact support, and polished UI components.

## Features

- Next.js 14 application with client and server routes
- Authentication pages for login and registration
- Admin and user dashboards under `/dashboard`
- Contact and terms pages
- Tailwind CSS for styling
- Reusable UI components using Radix UI and custom components
- MongoDB integration and AWS/GCP SDK support

## Tech stack

- Next.js 14.2.16
- React 18
- TypeScript
- Tailwind CSS
- Radix UI
- MongoDB
- React Hook Form
- Zod validation

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or pnpm available

### Install dependencies

```bash
npm install
```

### Run locally

```bash
npm run dev
```

Open `http://localhost:3000` in your browser.

### Build for production

```bash
npm run build
npm run start
```

## Project structure

- `app/` - Next.js app routes and pages
- `components/` - shared UI components and theme provider
- `lib/` - database, utility, and data helpers
- `public/` - static assets
- `styles/` - global styles

## Routes

- `/` - landing page
- `/auth/login` - login page
- `/auth/register` - registration page
- `/contact` - contact page
- `/terms` - terms and policies page
- `/dashboard/admin` - admin dashboard
- `/dashboard/user` - user dashboard

## Notes

- `next.config.mjs` disables image optimization and ignores ESLint/TypeScript build errors for development convenience.
- Update environment variables for MongoDB and any cloud provider credentials before running production builds.
