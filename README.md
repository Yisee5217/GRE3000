# GRE Daily(Chinese version中文版)

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

## Notes

- The first successful load requires internet access to fetch the vocabulary data.
- After that, the vocabulary cache and learning progress are stored in that browser.
- Progress does not automatically sync across different devices or browsers.
- Clearing site data/local storage will erase the local learning progress.
