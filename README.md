# Death at the Velvet Crown

A murder mystery game for two detectives, in a single HTML file. Plays in about 90 to 120 minutes.

## Play it

Open `index.html` in any modern browser (Chrome, Firefox, Safari or Edge). No install and no server needed. Progress saves automatically in that browser, so you can pause and come back.

## Put it on GitHub Pages

1. Create a new repository on GitHub, for example `velvet-crown`.
2. Click **Add file > Upload files**, drop in `index.html`, and commit.
3. Go to **Settings > Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the game is live at `https://<your-username>.github.io/velvet-crown/`.

## Before the evening

- Open it once on the device you'll play on to check that it loads and the music plays, but don't open any documents, or you'll spoil clues for yourself.
- A laptop or tablet you can both see works best. Phones work too.
- The music and sound buttons are in the bottom-right corner.
- The solution inside the file is encoded, so a glance at the page source won't give it away.

## The printed case file

The `print` folder has four A4 PDFs. Everything on paper is also in the game, so you can mix both.

- `0-Detective-worksheets.pdf`: case board, timeline and accusation form. Print one set to share, or one each.
- `1-Envelope-A.pdf`: the opening evidence. Open from the start.
- `2-Envelope-B-sealed.pdf` and `3-Envelope-C-sealed.pdf`: seal these without reading them.

To print the sealed envelopes without spoiling the case for yourself:

1. Open the PDF and print straight away. The first page is a cover sheet, so that's all you'll see on screen.
2. Pick up the printed pages without reading them, slide them into an envelope with the cover on top, and seal it.
3. Colour looks best; black and white works too.
4. Print at 100% ("Actual size") so the cut-out card comes out at real playing-card size.

Optional crafting: the envelope A label, the suspect cards, the dealer's shorthand card (cut out the front and back and glue them together) and the newspaper clippings all have dashed cut lines.

For the evening: pens (two colours make it easy to tell whose notes are whose), scissors if you want to cut things out, and a magnifying glass if you have one. The game tells you when to open each envelope.

## Editing

The `source` zip has the game split into readable files. Run `python3 build.py` to rebuild `dist/index.html`, and `python3 print/make_pdfs.py` (needs Playwright) to rebuild the PDFs. The solution and hints live in `build.py`, so only open it if you want spoilers.

All art, music and story are original and drawn or generated in code. Fonts come from Google Fonts.
