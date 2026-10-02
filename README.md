# Liv2care prototype

Clickable prototype of **Liv2care**, a closed-loop care-coordination platform for liver-risk assessment in people with type 2 diabetes. Built for Health-a-thon 2026 (Team LIVACARE).

It follows the pathway from enrolment to lab tests, platform clinician review, the treating doctor's decision, FibroScan, and follow-up, with a view for each role: treating doctor, patient, lab and centre, platform clinician, and operations.

## Run it

Open `index.html` in a browser. There is no build step and no server. It works on phones.

## What to know

- All patients, labs and messages are invented. Nothing leaves the browser; state is kept in local storage. **Reset demo** restores the starting data.
- Messages and the booking helper are simulated. The helper never sees lab values.
- The app does not diagnose, calculate scores or recommend treatment. The FIB-4 value and the clinical summary are typed by the platform clinician.
- Open **How to use this demo** at the top for a step-by-step path through all five roles.

## Planned stack

Next.js and TypeScript, Tailwind, Supabase, SMS and WhatsApp links, Gemini API and Sarvam AI for logistics only.
