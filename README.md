# english-speak-app

Simple web page with clickable phrase boxes that speak aloud using the Web Speech API.

How to use

- Open [index.html](index.html) in a modern browser (Chrome, Edge, Safari).
- Click any box (or focus and press Enter/Space) to hear the phrase spoken aloud.
- Use the Rate slider to adjust speaking speed. Click Stop to cancel speech.

If you want to serve locally (recommended for some browsers):

```bash
# from this project folder
python3 -m http.server 8000
# then open http://localhost:8000/
```

Notes

- Speech voices may vary by browser/OS. Ensure audio is enabled and not muted.
- This app uses the browser `speechSynthesis` API; no server dependencies.

Translations

- The translations shown under each English phrase are Simplified Chinese (简体中文).
- The app only speaks the English phrases; the Chinese text is for display only.

Purpose

- This small app is intended to help a Chinese grandmother (简体中文使用者) communicate in an English-only nursing home. The visible Simplified Chinese text provides quick reading while the app speaks the English phrase aloud to staff.
# english-speak-app