# Familiarise — Consulting Web App

**Type:** Full-stack side project
**Timeline:** 2023 -- Present
**Status:** Active development
**PRs:** 237 pull requests

---

## Summary

A consulting platform connecting consultants with clients. Built as a web app with Next.js and a mobile app with Flutter, backed by Prisma ORM, Supabase (PostgreSQL + Auth), and Redis caching.

---

## Architecture

### Frontend (Web)
- **Next.js** — React-based web framework
- Role-based dashboards for consultants and clients
- Search debouncing with React memoization

### Frontend (Mobile)
- **Flutter** — cross-platform mobile client

### Backend
- **Prisma ORM** — database access layer
- **Supabase** — PostgreSQL database + authentication
- **Redis** — caching layer

---

## Features

### Payments
- Integrated **Razorpay** payment processing
- Consultant earnings tracking with revenue sharing

### Video & Communication
- **Stream**-based video recording for webinars
- **Novu** notification services (email, in-app, push)

### Booking System
- Booking algorithms with availability conflict resolution
- Referral system with revenue sharing logic

### Authentication
- Migrated from NextAuth v4 to **BetterAuth**

---

## Technologies

- Next.js, React, Flutter, Dart
- Prisma ORM, Supabase (PostgreSQL), Redis
- Razorpay, Stream, Novu
- BetterAuth (formerly NextAuth v4)

---

## Resume Appearance

| Resume Version | Bullets | Detail Level |
|---------------|---------|-------------|
| 2025 software-dev | 3 bullets | Most detailed (booking algos, referral system, memoization) |
| 2025 ai | 1 bullet | Condensed |
| 2025 combined | 2 bullets | Medium |
| 2026-02 software-dev | 2 bullets | Medium (payments, video, notifications, auth migration) |
| 2026-02 ai | 1 bullet | Condensed |
| 2026-02 combined | 2 bullets | Medium |
