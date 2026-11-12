NURUTAJIKA BRIDGE CONNECT — STARTER WEBSITE PACKAGE

Files included:
- Public website pages: Home, Global Opportunities, For Companies, Advertise, About, Contact, Privacy
- Membership information page
- Admin-control planning page
- Shared stylesheet and small script

IMPORTANT CURRENT LIMITATIONS
1. This is a static starter website. It does not yet connect to Supabase.
2. The admin page is NOT a working or secure admin dashboard yet.
3. Membership application/payment checks are manual; the page directs applicants to WhatsApp.
4. Do not add secret keys or service-role keys to website files.
5. The exact 25 additional rules were not available in the retrieved project notes, so they have not been invented or silently added.

CONFIRMED DETAILS
Brand: NuruTajika Bridge Connect
Membership fee: KSh 50
M-Pesa payment number: 0705064644
WhatsApp/contact: 0705064644
Email: wawerushiku5@gmail.com
Owner personally checks payments and makes final approve/reject decisions.

GITHUB / NETLIFY
Upload the CONTENTS of this folder to the existing GitHub repository named:
nurutajika-bridge-connect
Do not upload the ZIP as the website itself. Extract it first, then upload the files and folders inside.
Netlify should deploy the existing site from this repository after the repository is connected.

NEXT DEVELOPMENT STEP
Connect Supabase securely:
- configure authentication
- create membership and opportunity tables
- add row-level security
- create a single owner/admin role
- implement approve/reject controls
Never expose the Supabase service-role key in browser code.
