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

## Editing

The `source` zip has the game split into readable files. Run `python3 build.py` to rebuild `dist/index.html`. The solution and hints live in `build.py`, so only open it if you want spoilers.

All art, music and story are original and drawn or generated in code. Fonts come from Google Fonts.
