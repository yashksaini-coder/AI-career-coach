## AI Career Coach

AI Career Coach is a Next.js application that helps you build your career. It is built with Next.js, Shadcn UI, Clerk, Lucid, and Vercel. Allows you to generate cover letters, resumes, and practice interviews. For now, it is in beta and only supports a limited set of features.

### Features

- [X] Cover Letter Generator
- [X] Resume Builder
- [X] Job Search
- [X] Interview Preparation

### Tech Stack

- Next.js
- Shadcn UI
- Clerk
- Lucid
- Vercel
- Google Gemini API

### Setup

```bash
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```

### Run Locally

```bash
npm run dev
```

### Deploy

```bash
npm run build
npm run start
```

### Contributing

```bash
git clone https://github.com/yashksaini-coder/ai-career-coach.git
cd ai-career-coach
npm install
npm run dev
```
