Qur'an Companion v3
====================
A Way2Quran-inspired original interface, not a copy of Way2Quran branding/code.

Run:
1. Extract the ZIP.
2. For the most reliable experience, serve the folder with a local web server:
   - Windows PowerShell: py -m http.server 8000
   - Then open: http://localhost:8000
3. Internet is required for live Quran text, reciter directory, radio directory, and audio.

Why a local server?
The HTML itself works when opened directly, but browsers restrict some PWA/service-worker features on file://. A local server avoids those restrictions.

Data:
- Quran text/translation: AlQuran.cloud API.
- Reciter and radio directories: MP3Quran public API.
- Audio: MP3Quran servers.
- Bookmarks, theme, last surah and Hifz marks are stored in localStorage.

The app has fallback reciters so the reader still has working audio choices if the reciter directory API is temporarily unavailable.
