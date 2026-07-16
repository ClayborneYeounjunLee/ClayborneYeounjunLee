# Hi, I'm Clayborne 👋

### Software developer · B.S. CS @ Stony Brook University (Dec 2027) · Melbourne from September 2026

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

U.S. and Korea dual citizen, relocating to Melbourne on a Working Holiday visa (subclass 462). I build full-stack web apps and host them myself on AWS: one EC2 instance with Route 53 DNS and a Docker Caddy reverse proxy, currently serving 12 live apps at [clayborne.dev](https://clayborne.dev). My main stack is Python and FastAPI on the backend, with Next.js, React, and TypeScript on the front.

Reach me at **yeounjun77@gmail.com** or on [LinkedIn](https://www.linkedin.com/in/clayborne77). Always up for talking about backend work or startup ideas.

## Featured projects

| Project | What it is | Stack | Live |
|---|---|---|---|
| **[Globird](https://github.com/ClayborneYeounjunLee/globird)** | AI travel planner. Claude returns day-by-day itineraries as schema-validated JSON, and the map picks its provider by region (Kakao in Korea, Leaflet elsewhere, Amap for China). Rebuilt solo from a university team project | React 18 · Vite · Express 5 · node:sqlite · Claude API | [Live](https://globird.clayborne.dev) |
| **[Melbourne Commute](https://github.com/ClayborneYeounjunLee/tonggeun-mel)** | "How far can I get?" transit isochrone map. Builds its graph from GTFS data (1,842 stops), runs Dijkstra over station-line nodes, draws contours on canvas, and refines times against live timetables. Also has a [Seoul port](https://github.com/ClayborneYeounjunLee/tonggeun) | JS · GTFS · Leaflet · graph algorithms | [Live](https://tonggeun-mel.clayborne.dev) |
| **[FSO](https://github.com/ClayborneYeounjunLee/fso)** | Fake StackOverflow, a full-stack Q&A app. I migrated it from a course MongoDB project to SQLite and gave it a daily seed reset on a systemd timer | Node.js · Express · better-sqlite3 | [Live](https://fso.clayborne.dev) |
| **[Kanade](https://github.com/ClayborneYeounjunLee/kanade)** | Japanese kana trainer: flashcards, quizzes, TTS, an activity heatmap, and Google sign-in cloud sync. One of three apps on a shared engine with [Kazu](https://github.com/ClayborneYeounjunLee/kazu) and [Baybayin](https://github.com/ClayborneYeounjunLee/baybayin) | JS · Firebase Auth/Firestore | [Live](https://kanade.clayborne.dev) |
| **[Heartline](https://github.com/ClayborneYeounjunLee/heartline)** | Personal running dashboard. Draws my Strava runs on a map, colored by heart-rate zone | JS · Strava API · Firebase | [Live](https://heartline.clayborne.dev) |
| **[Korea Rescue](https://github.com/ClayborneYeounjunLee/korea-rescue)** | "Your first day in Korea, sorted": an offline-first survival guide in four languages (EN/KO/JA/ZH) | Vanilla JS · i18n · data-driven rendering | [Live](https://korea.clayborne.dev) |

Everything in one place: [clayborne.dev](https://clayborne.dev)

## Building next

All on the same clayborne.dev infrastructure.

| Project | Stack | Status |
|---|---|---|
| E-commerce app | Next.js · FastAPI · PostgreSQL · Stripe | in progress |
| AI / computer-vision web app | FastAPI · React · HuggingFace/OpenAI | planned |
| Serverless API | AWS Lambda · API Gateway · DynamoDB · CI/CD | planned |

## Tech stack

**Languages:** Python, JavaScript/TypeScript, C++, SQL
**Frameworks:** FastAPI, React, Next.js, Node.js, Express, Tailwind CSS
**Data and cloud:** PostgreSQL, MongoDB, SQLite, Firebase/Firestore, AWS, Git/GitHub
