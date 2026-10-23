# Item Tracker (物品記錄)

A single-file HTML app for keeping track of personal belongings, with photos.

🔗 **Live:** https://kaojia.github.io/item-tracker/

## How it works

- Everything lives in `index.html` (no build step, no backend).
- Items and photos are stored in the browser (IndexedDB).
- Optional two-way sync to the private repo `kaojia/item-tracker-data` (`data.json`) through the GitHub Contents API, using a fine-grained token pasted once on each device. The token is stored only in that browser.
