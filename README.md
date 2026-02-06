# Tuition Paper Checking & Marks Automation System

## What this app does
- Import students from a Google Sheet (CSV publish link)
- Create a test (JEE/NEET) and enter answer key:
  - Q1–Q20 MCQ (A/B/C/D)
  - Q21–Q25 Numerical (decimals/integers/negative allowed)
- Select student with autocomplete
- Enter answers on an OMR-like screen (all 25 at once)
- Click **Save** at the end to compute:
  - Physics / Chemistry / Maths marks (after negative marking)
  - Wrong count + wrong question numbers per subject
  - Total out of 300
- Save results to database and export CSV

## Quick start (local)
1) Install Node.js LTS
2) Create a Supabase project and run the SQL in `supabase/schema.sql`
3) Copy `.env.example` to `.env.local` and fill values
4) Install & run:
```bash
npm install
npm run dev
```
Open http://localhost:3000
