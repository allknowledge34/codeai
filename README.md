# 💼 CodeAi – Smart Career & Resume Coach Platform

An AI-powered full stack web application that helps users improve resumes, analyze job roles, and receive personalized career guidance.

---

![Demo App](/public/maxresdefault-10.jpg)

---

## 🚀 Overview

CodeAi acts as a personal career mentor by combining large language models with real-time web technologies.

Users can chat with an AI coach, upload resumes for instant feedback, generate professional summaries, and get job recommendations tailored to their skills.

Designed as a production-ready AI SaaS platform.

---

## ✨ Core Features

🤖 AI Career Coach (text + voice conversations)  
📄 Resume upload & instant AI feedback  
📊 Job description analysis & suggestions  
🧠 AI-generated resume summaries  
🔐 Secure authentication with Clerk  
⚡ Real-time data handling with Convex  
🎨 Clean responsive UI with Tailwind & Shadcn UI  
🚀 Fast Next.js performance  

---

## 🏗 Tech Stack

### Frontend
- Next.js  
- React  
- Tailwind CSS  
- Shadcn UI  

### AI & Voice
- Gemini AI  
- Vapi Voice API  

### Backend & Database
- Convex Realtime Database  

### Authentication
- Clerk  

---

## Setup .env file

```js
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

## Getting Started

1. Clone the repository
2. Install dependencies:

```shell
npm install
```

3. Set up your environment variables as shown above
4. Run the development server:

```shell
npm run dev
```

---

## 🎯 Use Cases
✔ Resume projects
✔ Hackathons
✔ AI demos
✔ Full stack practice
✔ Startup MVP

---
## 🤝 Contributing
Contributions are welcome.

---
## ⭐ Support
If you found this project useful, give it a star ⭐
