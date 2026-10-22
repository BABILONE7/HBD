# Birthday surprise

This is a small Python-served birthday game with four stages. It uses only the
Python standard library.

## Run locally

On Windows, open a terminal in this folder and run:

```powershell
py app.py
```

Then open <http://127.0.0.1:8000> in a browser. If `py` is unavailable, install
Python 3 and run `python app.py` instead.

At the letter stage, choose exactly four image files to preview them in the
slideshow. The selected photos stay in the current browser tab and are not
uploaded to the server.

The birthday music attempts to autoplay on YouTube. Browser autoplay settings
may block playback; use the YouTube link on the letter page as a fallback.
