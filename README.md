# csg-open

A one-page helper for the CSG Contractor Directory (a claude.ai page). Claude pages can't open the phone's dialer,
Messages or Mail, so the directory's Call / Text / Email buttons open this page in a new tab and it opens the app.

Everything is in the link's `#` part, which browsers never send to a server: `#tel:+1...`, `#sms:+1...?body=...`,
`#mailto:name@example.com?subject=...&body=...`. Only phone numbers and email addresses are accepted. No data is stored.
