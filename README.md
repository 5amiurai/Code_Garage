# Code_Garage – Mechanic Shop Management Platform

Code_Garage is a full-stack web application for managing customer bookings, employee shifts, and service history for an auto repair shop.  
It was built as a capstone project with a focus on data management, system integration, and operational visibility.

---

## Tech Stack

- **Frontend:** Next.js (React), TypeScript
- **Backend:** Next.js API Routes / Node.js
- **Database:** MySQL (or whatever you actually use)
- **Auth:** (NextAuth / custom / JWT – update this)
- **Other:** Tailwind CSS, Prisma, etc. (add tools you actually use)

---

## Features

- Customer booking and appointment management  
- Employee shift scheduling and availability tracking  
- Service history and job details per customer/vehicle  
- Admin dashboard showing upcoming work and workload  
- Basic authentication and role-based views (if implemented)  
- Activity logs / audit trail for key operations (if applicable)

---

## Architecture & Data Model

The application is structured as a typical full-stack web system:

- **Frontend (Next.js):**
  - Pages and components for customers, employees, and admins
  - Form validation and user feedback
- **Backend (API routes):**
  - REST-style endpoints for customers, bookings, shifts, and services
  - Centralized business logic for validation and conflict checks
- **Database (MySQL):**
  - Tables for users, employees, customers, services, appointments, shifts
  - Relationships enforce referential integrity and consistent data

(You can add a diagram image here later, e.g. `/docs/architecture.png`.)

---

## How to Run Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/5amiurai/Code_Garage.git
   cd Code_Garage
Install dependencies:

bash:
npm install
# or
yarn install

Environment variables:

Create a .env.local file in the project root and add your own values:

env:

DATABASE_URL=your_mysql_connection_string
NEXTAUTH_SECRET=your_generated_secret
NEXTAUTH_URL=http://localhost:3000

# Google OAuth
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

# Google Maps
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your_google_maps_key

# Database (local setup)
DB_HOST=localhost
DB_PORT=3307
DB_USER=garage_user
DB_PASSWORD=your_db_password
DB_NAME=code_garage_db

bash:
npm run dev
# or
yarn dev
Open http://localhost:3000 in your browser.

---

My Contributions:

1.This was a collaborative project. My main responsibilities included:

2.Designing and implementing the backend scheduling and booking logic

3.Creating and refining the database schema and relationships

4.Building key UI components for the shifts / schedule view and dashboards

5.Handling incident debugging, bug fixes, and performance issues

6.Writing documentation and helping teammates with setup / environment issues

---

Future Improvements:

1.Role-based permissions for mechanics, admins, and reception

2.More detailed analytics and reporting (revenue, load, repeat customers)

3.Integration with email/SMS notifications

4.Support for multiple shop locations



---

Code Garage Team