# Approval-Workflow-Management-System

A full-stack web application built with **React + Vite** to manage approval workflows for inter-block outpass requests at **KLH (Deemed to be University), Hyderabad**.  
The system supports **Students, Faculty, Admins (HODs), and VO Officers** with **OTP-based approval and verification**.

---

## Features
- Raise and track outpass requests (Students & Faculty)
- Approve or reject requests (Admins/HODs)
- OTP-based ticket verification at gate (VO Officers)
- Role-based authentication
- Supabase-backed database

---

## Tech Stack
**Frontend:** React 19, Vite, React Router  
**Backend:** Express.js, Supabase (PostgreSQL)  
**Styling:** CSS, Inter Font  
**Tools:** ESLint, dotenv, CORS

---

## Setup
git clone https://github.com/btaashish/Approval-Workflow-Management-System.git

cd Approval-Workflow-Management-System
npm install

Create .env:
SUPABASE_URL=your_supabase_url
SUPABASE_SERVICE_KEY=your_service_key

Run:
npm run dev

Usage:
Students/Faculty raise requests → Admin approves/rejects → VO verifies using OTP.
