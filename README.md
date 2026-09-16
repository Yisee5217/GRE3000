# GRE Daily

A single-page GRE vocabulary review site designed for GitHub Pages.

## Features

- Daily new-word quota is configurable.
- Changing the quota takes effect immediately and remains the default for future days.
- Shows an estimate of how many days remain to finish the first pass of new words.
- Review scheduling is handled automatically in the browser.
- "Known" is on the left; "Unknown" is on the right.
- Unknown words are reinserted later in the same day's queue.
- Words can be moved directly to the trash without a confirmation dialog.
- Progress is stored locally in the browser with `localStorage`.
- No backend/database is required.

## Deploy to GitHub Pages

1. Create a new GitHub repository, for example `gre-daily`.
2. Upload all files from this folder to the repository root.
3. Commit the files.
4. Open the repository on GitHub.
5. Go to **Settings → Pages**.
6. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
7. Click **Save**.
8. After GitHub finishes publishing, your site will be available at:

   `https://YOUR_GITHUB_USERNAME.github.io/gre-daily/`

## Notes

- The first successful load requires internet access to fetch the vocabulary data.
- After that, the vocabulary cache and learning progress are stored in that browser.
- Progress does not automatically sync across different devices or browsers.
- Clearing site data/local storage will erase the local learning progress.
