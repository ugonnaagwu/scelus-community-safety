# Scelus — Community Safety Platform

Scelus is a portfolio-ready rebuild of a community safety app originally developed during the Girls Who Code Leadership Academy. The product concept combines community safety reports, missing-person information, a safety map, emergency/crisis resources, and moderated user reporting.

## What is real in this version

- Production-style React + Vite application
- Responsive mobile-first interface
- Supabase authentication and PostgreSQL schema
- Row Level Security policies
- Moderated incident-report workflow
- Active missing-person data model
- Interactive OpenStreetMap/Leaflet map
- Persistent user alert-area preference
- Emergency and crisis support resources
- Supplied Scelus logo asset (PNG)
- GitHub-ready structure and `.env.example`

## Demo mode

The app intentionally works without credentials using clearly labeled sample data. This makes it easy to preview the UI before connecting a backend.

## Turn on the live backend

1. Create a Supabase project.
2. Open Supabase SQL Editor.
3. Run `supabase/schema.sql`.
4. Copy the project URL and anonymous key.
5. Copy `.env.example` to `.env`.
6. Fill in:
   - `VITE_SUPABASE_URL`
   - `VITE_SUPABASE_ANON_KEY`
7. Install dependencies:
   `npm install`
8. Start:
   `npm run dev`
9. Production build:
   `npm run build`

## Important production work before claiming public safety data is "live"

The MVP has a real database/reporting architecture, but it does **not** pretend that sample records are official crime or missing-person data. Before public launch, connect verified government/agency feeds or an approved data provider, add an admin moderation dashboard, establish data-retention/privacy policies, add abuse/spam protection, and test accessibility/security.

For missing-person information, use only authorized/verified sources and obtain appropriate permissions for images and personal information.

## Portfolio description

**Scelus — Community Safety Platform**
Rebuilt a safety-focused community platform using React, Vite, Supabase, PostgreSQL, and Leaflet/OpenStreetMap. Implemented moderated community reporting, missing-person records, interactive safety mapping, authentication, row-level security, and crisis/emergency resources with a mobile-first interface.

## Suggested GitHub topics

`react` `vite` `supabase` `postgresql` `leaflet` `openstreetmap` `community-safety` `public-safety` `social-good` `girls-who-code`


## Brand asset
The UI uses the supplied Scelus logo as the primary brand asset, preserving the navy/coral/white visual system and the “SAFE TODAY. SECURE TOMORROW.” tagline.
