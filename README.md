# QuickAI 🚀

QuickAI is a full-stack AI SaaS application built with the **PERN stack** (PostgreSQL, Express, React, Node.js), offering subscription-based access to a suite of AI-powered tools. The project demonstrates end-to-end **full-stack development, AI integration, and subscription billing**.

---

## Key Highlights

- **Full-Stack Development:** Built with PERN stack, serverless PostgreSQL (Neon), and secure authentication using Clerk.  
- **Subscription-Based AI Tools:** Implemented premium features for article, blog, and image generation.  
- **AI Integrations:** Integrated resume analysis, background removal, and object removal in images.  
- **Deployment & Scalability:** Deployed a production-ready web app with seamless front-end/back-end integration.

---

## Features

### User Management
- Secure sign-up, sign-in, and profile management via **Clerk**

### Subscription Billing
- Premium subscriptions to access advanced AI features  

### AI Tools
- **Article Generator:** Generate articles from title & length  
- **Blog Title Generator:** Generate blog titles from keyword & category  
- **Image Generator:** Generate AI images from prompts  
- **Background Remover:** Upload an image and get transparent background  
- **Image Object Remover:** Remove specific objects from images  
- **Resume Analyzer:** Upload resume and get detailed AI analysis  

---

## Tech Stack
- **Frontend:** React, Tailwind CSS  
- **Backend:** Node.js, Express  
- **Database:** Serverless PostgreSQL (Neon)  
- **Authentication:** Clerk  
- **AI Integration:** OpenAI API (or other AI APIs)  

---

## Getting Started

### Prerequisites
- Node.js & npm
- PostgreSQL database (Neon recommended)
- Clerk account for authentication
- AI API key (OpenAI)

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/QuickAI.git
cd QuickAI

# Install dependencies
npm install

# Start backend server
npm run server

# Start frontend
npm run client
