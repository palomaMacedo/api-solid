# 🏋️ GymPass Style App

A gym and check-in management application inspired by the GymPass model.

---

## 📋 FRs — Functional Requirements

- [ ] 📝 It must be possible to sign up
- [ ] 🔐 It must be possible to sign in
- [ ] 👤 It must be possible to retrieve the profile of a logged-in user
- [ ] 📜 It must be possible to retrieve a user's check-in history
- [ ] 🔍 It must be possible for a user to search for gyms by name
- [ ] ✅ It must be possible for a user to check in at a gym
- [ ] 🛡️ It must be possible to validate a user's check-in
- [ ] 🏢 It must be possible to register a gym

---

## ⚖️ BRs — Business Rules

- [ ] 🚫 A user must not be able to sign up with a duplicate email
- [ ] 📅 A user cannot check in more than once on the same day
- [ ] 📍 A user cannot check in unless they are within 100m of the gym
- [ ] ⏱️ A check-in can only be validated within 20 minutes of being created
- [ ] 🔑 Check-ins can only be validated by administrators
- [ ] 🏛️ Gyms can only be registered by administrators

---

## 🔧 NFRs — Non-Functional Requirements

- [ ] 🔒 User passwords must be encrypted
- [ ] 🐘 Application data must be persisted in a PostgreSQL database
- [ ] 📄 All data lists must be paginated with 20 items per page
- [ ] 🪙 Users must be identified via a JWT (JSON Web Token)

---
