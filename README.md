# Mission Pawssible CRM

A responsive React/Vite starter for grooming, training, retail/POS, inventory, clients, employees, expenses, reporting and a WhatsApp hub.

## Run locally

```bash
npm install
npm run dev
```

## Publish with GitHub Pages

1. Create a GitHub repository named `mission-pawssible-crm`.
2. Upload these files or push them with Git.
3. In **Settings → Pages**, choose **GitHub Actions** as the source.
4. Push to `main`. The included workflow builds and publishes the app.

```bash
git init
git add .
git commit -m "Initial Mission Pawssible CRM"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/mission-pawssible-crm.git
git push -u origin main
```

## Important production note

This repository is a frontend starter with sample data. Real logins, records, payments, file uploads, PostgreSQL and WhatsApp require a secure backend. Never expose WhatsApp tokens or database passwords in frontend code or GitHub commits.

## Suggested next backend

Use `/api` on a Node/NestJS service, PostgreSQL with Prisma, object storage for pet photos/receipts, and Meta WhatsApp webhooks. Configure secrets only in the hosting provider or GitHub repository secrets.
