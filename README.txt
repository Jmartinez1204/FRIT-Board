Five Rivers IT iPad Dashboard v3

This version recreates the approved dashboard layout as an actual HTML/PWA-style iPad dashboard.

LIVE DATA
- Outlook Calendar: Microsoft Graph delegated Calendars.Read + User.Read
- Weather: Open-Meteo
- Wind speed, direction and gusts: Open-Meteo
- Tech news: Hacker News public API

OUTLOOK SETUP
1. Host this folder on an HTTPS website.
2. Create an Entra App Registration.
3. Authentication > Add platform > Single-page application (SPA).
4. Add the exact HTTPS URL used to open index.html.
5. API permissions > Microsoft Graph > Delegated:
   - User.Read
   - Calendars.Read
6. Open the dashboard and press the gear icon.
7. Add Client ID, Tenant ID and the exact Redirect URI.
8. Save and sign in when prompted.

WEATHER
Use the gear icon and either:
- Enter a city, or
- Press Use iPad Location.

IPAD
Open the hosted URL in Safari > Share > Add to Home Screen.
For a kiosk/desk display, set Auto-Lock to Never while in use.
