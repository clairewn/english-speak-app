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
# english-speak-app