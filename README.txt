SINIA ♡ SANTANU — THE LITTLE LOVE SCRAPBOOK

HOW TO OPEN
1. Extract this ZIP completely.
2. Keep index.html, photos/, audio/, flower-memory.jpg, and the GIF files together.
3. Open index.html in a browser. Tap a song's Play button to start music.
4. If Android cannot open the file correctly, use a local server in Termux:
       cd /path/to/sinia_santanu_love_scrapbook
       python -m http.server 8000
   Then open http://127.0.0.1:8000 in your browser.

WHAT'S INCLUDED
- Romantic scrapbook with animated welcome, memories, timeline, letters, and love templates
- Three local photos plus a pressed-flower memory photo
- Two animated GIF keepsakes, with still-frame fallbacks when reduced motion is enabled
- Seven local MP3 tracks, with a shared song selector and volume control
- 100 reasons I adore you, a surprise gift box, memory garden, and two mini-games
- Accessible photo viewer, replayable welcome screen, and a lightweight local starfield
- Reduced-motion support and keyboard-friendly controls

MUSIC
Music does not autoplay. Choose a track to jump to its player, then press Play.
If a track cannot load, check that the ZIP was extracted fully and the audio/ folder
is still beside index.html. Playing one song pauses the others.

GITHUB PAGES
Upload the contents of the sinia_santanu_love_scrapbook folder to your repository
(or upload the ZIP and extract it before publishing). Ensure index.html is at the
published folder's root. All media paths are relative, so the website does not need
a database, API key, or external JavaScript library.

NOTES
The relationship counter uses calendar months from April 2023 because no exact
first-meeting day was specified. The website has been source-checked, but final
playback and visual behavior should still be tested in a real Android browser.


NEW IN THE BOUQUET DECORATION UPGRADE
- A flower-shop section with three interactive bouquet cards: blush roses, sunshine wildflowers, and a lavender dream.
- Each bouquet opens a personalized note from Santanu to Sinia.
- Added subtle floral corner decorations and a shortcut link to the bouquet section.
- Bouquet cards adapt to mobile screens and respect reduced-motion preferences.
- All existing photos, GIFs, and seven MP3 files are retained.

Open index.html in a modern browser to explore the bouquet garden. The bouquet notes work locally and do not require an internet connection.


REAL-TIME CHAT
See CHAT_SETUP.txt for Firebase setup, authorized accounts, Firestore rules, and hosting steps. The chat remains disabled until configured.
