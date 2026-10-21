# Our Little World 🌍 — setup (free, ~10 minutes, no Claude account needed)

## 1. Put the website on GitHub Pages
1. Make a free account at github.com, then click **New repository**. Name it `our-world`, set it to **Public**, tick "Add a README", and create it.
2. **Add file → Upload files**, drag in `index.html`, then **Commit changes**.
3. Go to **Settings → Pages**. Under "Branch" pick `main` and `/ (root)`, then **Save**.
4. After about a minute your site is live at `https://YOURNAME.github.io/our-world/`. Open it on your phone and use **Add to Home Screen**.

The site is public, but it contains only code. Your photos never go in this repo.

## 2. Make a private repo for your photos (free cloud storage)
1. **New repository**, name it `travel-photos`, set it to **Private**, tick "Add a README", and create it.
2. Go to **Settings (your profile) → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
3. Set the repository access to **Only select repositories → travel-photos**, and under Permissions set **Contents: Read and write**. Generate and copy the token.
4. Open your site, tap **☁️ Sync**, enter `YOURNAME/travel-photos` and the token, then tap **Save & sync**.

The token is stored only in that browser. Repeat step 4 on each device and your photos will appear everywhere.

## Good to know
- Photos are shrunk to 1600px, so a GitHub repo holds thousands for free (stay under about 1 GB).
- Deleting a photo removes it from the map, but the file stays in the private repo.
- Without Sync, photos stay only in that browser.
- iPhone: in the photo picker tap **Options** and turn on **Location**, or iOS strips the GPS.
