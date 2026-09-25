# Team Collaboration Guide

## Before starting

```bash
git checkout main
git pull origin main
git checkout -b feature/<your-feature>
```

## Work only inside your feature folder initially

Avoid changing unrelated feature folders.

## Before opening a PR

```bash
git status
git add .
git commit -m "Add Sprint 1 <feature> scaffold"
git push -u origin feature/<your-feature>
```

Then open a Pull Request into `main`.

## Shared files

If a feature requires changing a shared file, discuss it with the team first.
Typical shared areas include:

- database schema
- environment/configuration
- common API client
- common UI components
- authentication state
- booking data model

Do not commit real API keys, Firebase secrets, Razorpay secrets, or database
passwords. Use `.env.example` files for variable names only.
