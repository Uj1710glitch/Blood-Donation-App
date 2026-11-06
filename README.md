A responsive blood donation web app. People can search for donors by blood group and pincode, register as a donor in four steps, and find blood banks and hospitals near their location.

Live demo: https://uj1710glitch.github.io/Blood-Donation-App/

Features
Emergency header: a helpline strip and a sticky navbar that collapses into a menu on phones.
Hero section: two main actions, "Find Blood" and "Become a Donor", with a panel of example urgent requests.
Live stat counter: registered donors, donations, lives impacted and donors available now, updating every few seconds.
Blood search: filter by blood group (A+, A-, B+, B-, AB+, AB-, O+, O-) and pincode. Results are cards with donor name, blood group badge, distance, availability tag and a "Contact Donor" button.
Nearby hospitals: enter an area, city or pincode to open live Google Maps results for blood banks, hospitals with a blood bank, and donation centres.
Donor registration: a step-by-step form (personal details, blood group and pincode, last donation date, review) with validation on every step.
Eligibility checklist: a modal that checks age 18 or above, weight 45 kg or above, and no illness in the last 14 days before registration is confirmed.
Design: crimson red and soft pink theme, dark grey text, automatic light and dark mode, full-screen animated GIF background, and reduced-motion support.
Tech stack
HTML, CSS and vanilla JavaScript in a single index.html file
Google Fonts (Bricolage Grotesque and DM Sans)
No build step and no dependencies
Run locally
Download or clone this repository.
Open index.html in any modern browser.
Deploy with GitHub Pages
Push index.html to the main branch.
Go to Settings > Pages.
Under Build and deployment, choose Deploy from a branch, select main and / (root), then save.
Your site will be live at https://uj1710glitch.github.io/Blood-Donation-App/ in a minute or two.
Important notes
Donor names, phone numbers, distances, live counters and the emergency helpline number (1800-000-0000) are sample data. Replace them before using the site for real requests.
Registration does not save anything yet. Connect it to a backend or database to store real donors.
Always confirm blood availability with the hospital or blood bank directly.
Roadmap
Real donor database and API
Mobile number verification (OTP) for donors
Use my current location for nearby search
Hindi and other regional language support
Donor reminders after the 3-month donation gap
License
