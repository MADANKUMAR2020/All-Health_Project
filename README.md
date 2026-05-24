# Allo Inventory Reservation System

## Tech Stack

- Next.js 14
- TypeScript
- Prisma
- Supabase PostgreSQL

---

## Features

- Product listing
- Warehouse inventory
- Reservation system
- Countdown timer
- Reservation confirmation
- Reservation cancellation
- Auto expiry cleanup design

---

## How to Run

```bash
npm install
npm run dev
```

Open:

```txt
http://localhost:3001
```

---

## Database

Hosted on Supabase PostgreSQL.

---

## Expiry Mechanism

Reservations expire automatically after timeout.
Cleanup logic can run using Vercel Cron Jobs.

---

## Tradeoffs

Focused mainly on correctness and reservation flow.
UI improvements and authentication can be added later.