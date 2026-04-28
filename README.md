Readme · MD
# 🏋️ GymPass Style App
 
A gym and check-in management application inspired by the GymPass model.
 
---
 
## 🛠️ Stack
 
![TypeScript](https://img.shields.io/badge/TypeScript-FFC107?style=flat-square&logo=typescript&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-FFC107?style=flat-square&logo=fastify&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-FFC107?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-FFC107?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-FFC107?style=flat-square&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-FFC107?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-FFC107?style=flat-square&logo=vitest&logoColor=white)
 
---
 
## 📋 FRs — Functional Requirements
 
- [ ] 🖊️ It must be possible to sign up
- [ ] 🔑 It must be possible to sign in
- [ ] 👤 It must be possible to retrieve the profile of a logged-in user
- [ ] 📋 It must be possible to retrieve a user's check-in history
- [ ] 🔍 It must be possible for a user to search for gyms by name
- [ ] 🏢 It must be possible for a user to check in at a gym
- [ ] ✅ It must be possible to validate a user's check-in
- [ ] 🏛️ It must be possible to register a gym
---
 
## ⚖️ BRs — Business Rules
 
- [ ] 🚫 A user must not be able to sign up with a duplicate email
- [ ] 📅 A user cannot check in more than once on the same day
- [ ] 📍 A user cannot check in unless they are within 100m of the gym
- [ ] ⏰ A check-in can only be validated within 20 minutes of being created
- [ ] 🔑 Check-ins can only be validated by administrators
- [ ] 🏛️ Gyms can only be registered by administrators
---
 
## 🔧 NFRs — Non-Functional Requirements
 
- [ ] 🔒 User passwords must be encrypted
- [ ] 🗃️ Application data must be persisted in a PostgreSQL database
- [ ] 📄 All data lists must be paginated with 20 items per page
- [ ] 🪙 Users must be identified via a JWT (JSON Web Token)
---
 
## 🚀 Getting Started
 
```bash
# Clone the repository
git clone https://github.com/palomaMacedo/api-solid.git
cd api-solid
 
# Install dependencies
npm install
 
# Start the database
docker-compose up -d
 
# Run migrations
npx prisma migrate dev
 
# Start the server
npm run dev
```
 
---
 
## 🌱 Environment Variables
 
Copy `.env.example` to `.env` and fill in the values:
 
```env
DATABASE_URL="postgresql://user:password@localhost:5432/apisolid"
JWT_SECRET="your-secret-key"
```
 
---
 
 
<div align="center">
 💜 Built by Paloma Macedo (http://palomamacedo.dev)
 
</div>
 
