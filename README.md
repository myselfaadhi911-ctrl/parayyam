# Parayaam — Healthcare & Therapist Booking Platform

A responsive React/Vite implementation inspired by the uploaded Parayaam source. It includes patient, practitioner and administrator workspaces, therapist discovery, a guided therapist matching flow, appointment booking, messaging placeholder, profile views, and admin/practitioner dashboard screens.

## Run locally

```bash
npm install
npm run dev
```

## Demo behaviour

- Use **View as** in the top-right to switch between Patient, Doctor and Admin workspaces.
- Patient flow: Find a therapist → view details → book a session. Bookings update the local demo appointment list.
- The AI therapist match is a guided three-question UI. Recommendations are demo behaviour, not clinical advice or diagnosis.
- Demo profile names and appointment records are sample data.

## Before production

Connect secure authentication and roles, database/API services, live scheduling, payment gateway, secure messaging/video, practitioner credential verification, consent, retention/deletion policies, incident response and applicable Indian privacy/healthcare requirements. This bundle is a front-end prototype; backend services, production authentication, payments, live schedules and actual AI matching are not integrated. Do not accept patient data or payments until these are implemented and reviewed.
