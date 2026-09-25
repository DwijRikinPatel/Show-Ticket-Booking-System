# BookMyShow-like Platform — Sprint 1 Feature Scaffold

This directory is a **starting structure only** for Sprint 1.

The purpose is to let each teammate create a separate Git branch and work on
one feature independently. The files intentionally contain placeholders and
TODOs rather than complete implementation code.

## Suggested branch naming

- `feature/authentication`
- `feature/manager-show-listing`
- `feature/browse-nearby-shows`
- `feature/seat-selection`
- `feature/payment`
- `feature/ticket-generation`

## Sprint 1 features

1. Successful Logins
2. Managers Can List Shows
3. Browse Nearby Shows (no search)
4. Select Seats
5. Payment Gateway
6. Ticket Generation

## Technology context

Frontend:
- Next.js / React
- Tailwind CSS

Backend:
- FastAPI (Python)

Database:
- PostgreSQL / Supabase

Authentication:
- Firebase Auth

Payment:
- Razorpay Sandbox

Storage:
- Cloudinary

Hosting:
- Vercel (frontend)
- Railway (backend)

## Important

Keep feature-specific implementation inside the corresponding feature folder.
Shared code such as database models, common UI components, API clients, and
configuration should be agreed upon by the team before multiple branches modify
the same files.
