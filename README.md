# MedScript — Doctor Prescription Management System

A fully standalone, offline-capable doctor prescription system.  
All data is stored in the browser's localStorage, scoped per doctor account.

## Deploy to Vercel

### Option 1: Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 2: Vercel Dashboard
1. Zip this folder and upload at vercel.com/new
2. Or push to GitHub and import the repo

### Option 3: Drag & Drop
Drag the `public/` folder directly onto vercel.com/new → "Deploy"

## Demo Login
- Email: demo@medscript.in  
- Password: demo1234

## Features
- Doctor auth (multi-account, isolated data)
- Patient management + prescription history
- Prescription pad (vitals, medicines, precautions, advice)
- Medicine database with auto-prefill
- Reusable templates, precautions & advice
- Print-ready professional prescription layout
- Doctor settings with logo & signature upload
