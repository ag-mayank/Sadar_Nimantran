# Anjali & Ankur Wedding Invitation Website

## Files
- `index.html` — the complete website code (HTML, CSS and JavaScript).
- `assets/wedding-photo-1.jpg` — first uploaded wedding photo.
- `assets/wedding-photo-2.jpg` — second uploaded wedding photo.
- `assets/wedding-photo-3.jpg` — third uploaded wedding photo.
- `navrai_majhi.mp3` — music played when guests open the invitation.

## Run locally
1. Extract this ZIP.
2. Open `index.html` in Chrome, or open the folder in VS Code and use Live Server.
3. Keep the `assets` folder and `navrai_majhi.mp3` beside `index.html`; the gallery and music use these relative paths.

## Customize
Open `index.html` in a text editor or VS Code.

Find `const wedding = {` near the bottom of the file and edit:
- `bride`, `groom`
- `date` (format: `YYYY-MM-DDTHH:mm:ss`, local time)
- `dateLabel`, `coverDate`, `time`
- `venue`, `mapUrl`, `hashtag`

You can change the text and styling in the `<style>` section.
To replace a gallery photo, overwrite the matching JPG in `assets` while keeping its filename.
To use a different song, replace `navrai_majhi.mp3` with your MP3 and keep the same filename.

## Note
The website does not currently include an RSVP form.
