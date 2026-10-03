# FoodFlow

A full-stack canteen ordering and crowd-management application rebuilt from scratch.

## Features
- QR-first customer ordering flow
- Menu, cart, wallet and order tracking
- Admin dashboard with analytics, inventory and user management
- JWT authentication with demo mode when MongoDB is not configured
- Razorpay integration hooks with safe demo fallback
- Printable order receipts
- Responsive desktop/mobile UI

## Run locally

Requirements: Node.js 20+

```bash
npm install
npm run install:all
npm run dev
```

Client: http://localhost:5173
Server: http://localhost:4000

Copy `server/.env.example` to `server/.env` for MongoDB/JWT/Razorpay configuration.
"# FoodFlow2" 
