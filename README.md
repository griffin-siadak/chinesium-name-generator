# Chinesium Name Generator

Generates brand names for products of mysterious origin, like MalsiPree, VAVOFO and SAMSARIC. It can optionally add a fake Amazon-style listing title to each name.

Everything is in one file, `index.html`, with no build step and no dependencies. To try it, open the file in a browser.

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `chinesium-name-generator`.
2. Push this folder to it:

   ```bash
   git init
   git add .
   git commit -m "Chinesium name generator"
   git branch -M main
   git remote add origin https://github.com/<your-username>/chinesium-name-generator.git
   git push -u origin main
   ```

3. On GitHub, open the repo's **Settings → Pages**. Under "Build and deployment", set the source to **Deploy from a branch**, then choose branch `main` and folder `/ (root)`, and click Save.
4. After a minute or so the site is live at `https://<your-username>.github.io/chinesium-name-generator/`.

## How names are made

- **Syllable mash** (MalsiPree): 2–3 random syllables, often with a catchy ending like -ee, -ix or -ko.
- **Rhyming repeats** (VAVOFO): a repeated consonant with matching vowels.
- **Disguised words** (Greenzech): a real word with a made-up ending.
- **Keyboard smash** (QWZNDZGR): mostly consonants, always in capitals.

Capitalization is ALL CAPS, MidCaps or Normal. A small blocklist keeps rude words out.

Favorites are saved in the browser's local storage, so each visitor only sees their own.
