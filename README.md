# Wedding Invitation

A single-page wedding invitation. No backend, no build step — just static
HTML/CSS/JS that runs anywhere, including GitHub Pages (free).

## Preview locally
Double-click `index.html` to open it in your browser. That's it.

## Edit your content
Open `index.html` and scroll to the **CONFIG** block near the bottom of the
file. Everything you'd change — names, date, venue, schedule, story
milestones, photos, WhatsApp/Call number, dress code, hashtag — lives in that
one block, with plain-English comments. You never touch the design code.

Two things to set once:
- **Photos:** add your images to the `images/` folder (see `images/README.txt`
  for the exact filenames).
- **Map link:** paste your venue's Google Maps link into `venue.mapsUrl`.

## Deploy to GitHub Pages (no command line)
1. Create a new **public** repo on github.com.
2. Click **Add file -> Upload files**, then drag in `index.html` and the
   `images` folder together. Commit.
3. Go to **Settings -> Pages**.
4. Source: **Deploy from a branch** -> Branch: **main** -> Folder: **/ (root)**
   -> Save.
5. Wait about a minute, refresh. Your live link appears at the top:
   `https://YOURNAME.github.io/YOUR-REPO/`

## Custom domain (optional)
Add a file named `CNAME` (no extension) at the root containing just your
domain, e.g. `aaravanddiya.com`, then point your domain's DNS at GitHub Pages.

## Social share preview
For a nice WhatsApp/Instagram link card, add a cover photo and set the
`og:image` URL in the `<head>` of `index.html` once the site is live.
