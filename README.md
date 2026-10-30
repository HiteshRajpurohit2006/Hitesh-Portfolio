# Hitesh | Personal Portfolio

A minimal, responsive personal portfolio with project search/filter, light/dark mode and an AI chatbot.

🌐 **Live website:** https://hitesh-portfolio-wine.vercel.app/

## Technologies
HTML, CSS, JavaScript, Vercel Serverless Function (Node.js), Groq API, Git, GitHub, Cursor AI

## Features
- Sections: Home, About Me, Skills, Projects, Contact Information, AI Chatbot
- Five project cards with GitHub and live links
- Project search by name or technology, plus tag filters
- Light / dark mode toggle
- Responsive layout with mobile menu
- AI chatbot grounded in portfolio data, with an error message if the API fails
- API key stored in Vercel environment variables (never in the repo)

## Projects
| # | Project | GitHub | Live |
|---|---------|--------|------|
| 1 | Python Programs Collection | [python-code-25bcon2685](https://github.com/HiteshRajpurohit2006/python-code-25bcon2685) | - |
| 2 | Messy Python Code Improvement | [messy-code](https://github.com/HiteshRajpurohit2006/messy-code) | - |
| 3 | Bug Fixing Using Cursor AI | [bug-fixing](https://github.com/HiteshRajpurohit2006/bug-fixing) | - |
| 4 | Interactive Quiz Application | [quiz-app](https://github.com/HiteshRajpurohit2006/quiz-app) | [Open](https://quiz-app-alpha-ten-56.vercel.app/) |
| 5 | Book Reading List Application | [reading-list](https://github.com/HiteshRajpurohit2006/reading-list) | [Open](https://reading-list-mu-rust.vercel.app/) |

## Project Structure
```
├── index.html     # Website
├── api/chat.js    # Serverless function calling the Groq API
├── package.json
└── README.md
```

## Setup
1. Clone the repo and open the folder.
2. Get a free API key from console.groq.com.
3. Run locally: `npm i -g vercel`, create `.env.local` with `GROQ_API_KEY=your_key`, then `vercel dev`.
4. Deploy: import the repo in Vercel, add `GROQ_API_KEY` under Settings → Environment Variables, and deploy.

## Contact
- Email: hiteshrazz1981@gmail.com
- GitHub: https://github.com/HiteshRajpurohit2006
