# SkyCast 2.0

A static, responsive weather dashboard for GitHub Pages.

## Included
- Location search and live forecast from Open-Meteo
- Current conditions, 24-hour forecast and 7-day outlook
- Local-time greeting and automatic day/night theme
- Interactive OpenStreetMap map with RainViewer radar overlay (when available)
- Saved locations stored in this browser
- Celsius/Fahrenheit, contrast, larger-text and share controls
- Official weather-warning and weather-information links

## Important limitations
- Weather warnings are linked to official authorities; this first static release does not aggregate verified live warnings worldwide.
- Saved places stay on this device. Real optional accounts and cloud sync require a secure authentication/database service; GitHub Pages alone cannot provide this.
- The news section links to official weather organisations rather than pretending to be a live news feed.
- External data services and map tiles require an internet connection and may have usage limits or outages.

## Publish
1. Create a **public** GitHub repository named `skycast` under your account.
2. Upload `index.html` to the top level of the repository (not inside another folder).
3. Commit the file.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then Save.
7. Wait for deployment. The project URL will be `https://alvinswitch456-droid.github.io/skycast/`.

GitHub Pages sites are public. Do not put passwords, private keys, API secrets, or personal data in this repository.
