# IEM-event-management
IGNITE ’26 — IEM × UEM Campus Event Portal

A single-file editorial campus event portal (index.html) built for the Institute of Engineering and Management (IEM) and University of Engineering and Management (UEM) ecosystem across IEM Gurukul, IEM Management House, and UEM New Town.

Key Features

Editorial Hero & Featured Spotlight: Split-showcase hero with an IEM campus background that merges and fades smoothly into the Semester Lineup, paired with a live ticking countdown, seat availability progress bar, and spotlight switcher.

Semester Lineup & Filtering: Live search by title, venue, or description, multi-campus filter pills (ALL CAMPUSES, IEM Gurukul, IEM Management House, UEM New Town), and category/status filter pills (AI & ML, LIVE NOW, UP NEXT, HACKATHON, CONFERENCE, POSTER, WORKSHOP, ROBOTICS, CULTURAL, SPORTS).

One-Step Registration & Instant QR Pass: Inline registration studio supporting Individual and Team (2–4) modes, automatic seat decrement, deterministic SVG QR code generation, and instant pass issuance (IGN-26-XXXX).

Dedicated AI & ML Showcase (#aiml-track): Highlighted section for IEM CSBS & CSE (AI & ML) events, symposiums, workshops, and hackathons.

On-Page Personal Passes (#my-registered-events): Displays all passes generated in the browser with Pass ID, QR code, check-in status, agenda drawer trigger, and pass cancellation.

Sequential Order of Events (#order-of-events): Run-of-show sequence ordered by event number with quick jump-to-registration actions.

Event Detail Slide-Over Drawer: Full event brief, session agenda, prize/honours details, and seat counts.

Organizer Hub Modal: Publish new events directly into the lineup and run-of-show, view live student registrations, export a CSV roster (IEM_SYNAPSE26_Registrations.csv), and validate gate check-ins by Pass ID.

Local Storage Persistence

Events and registrations persist in browser localStorage under:

ignite26_iem_events_v3

ignite26_iem_regs_v3

Running Locally

No build step or server is required. Open index.html directly in any modern web browser.

LIVE DEMO LINK - 
