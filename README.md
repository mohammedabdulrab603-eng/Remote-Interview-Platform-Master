<div align="center">

# Remote Interview Platform

### A real-time, collaborative platform for modern technical interviews.

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)](https://clerk.com/)
[![Convex](https://img.shields.io/badge/Convex-EE342F?style=for-the-badge)](https://www.convex.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)

</div>

## Overview

A full-stack remote technical interview platform built to create a seamless experience for interviewers and candidates. It combines secure authentication, real-time data synchronization, and a browser-based coding environment in one workspace.

## Features

- Secure user authentication with Clerk
- Real-time application data powered by Convex
- Monaco Editor integration for professional in-browser coding
- Built with Next.js and TypeScript
- Node.js-powered full-stack development
- Responsive, modern interface for remote interviews

## Tech Stack

| Technology | Purpose |
| --- | --- |
| Next.js | Frontend and full-stack framework |
| TypeScript | Type-safe application development |
| Clerk | Authentication and user management |
| Convex | Real-time backend and database |
| Monaco Editor | In-browser code editor |
| Node.js | Server-side runtime |

## Getting Started

### Prerequisites

- Node.js 18 or newer
- npm, pnpm, or yarn
- Clerk account
- Convex account

### Installation

```bash
git clone https://github.com/mohammedabdulrab603-eng/Remote-Interview-Platform-Master.git
cd Remote-Interview-Platform-Master
npm install
```

### Environment Variables

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CONVEX_URL=your_convex_deployment_url
```

> Keep your environment variables private. Do not commit `.env.local` to GitHub.

### Run the Project

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Roadmap

- [ ] Interview scheduling
- [ ] Interviewer and candidate dashboards
- [ ] Multi-language coding support
- [ ] Code execution and test cases
- [ ] Feedback and evaluation workflow
- [ ] Interview history and analytics

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a pull request.

## Repository

[github.com/mohammedabdulrab603-eng/Remote-Interview-Platform-Master](https://github.com/mohammedabdulrab603-eng/Remote-Interview-Platform-Master)

## License

This project is licensed under the MIT License.

---

<div align="center">

Built by <a href="https://github.com/mohammedabdulrab603-eng">Mohammed Abdul Rab</a> · Give the project a star if you find it useful. ⭐

</div>
