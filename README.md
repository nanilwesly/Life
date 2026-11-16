# Babu Smart Life

Fresh-start personal life management PWA.

## Included
- Daily activities and tasks with categories, priorities and completion status
- Photo attachments (camera/gallery) and multiple document attachments for each activity
- Food Management: breakfast, lunch, dinner, snacks, meal notes, photos and expenses
- Monthly food expense summary
- Export records to a JSON file (no in-app restore/import)
- PWA manifest, service worker and app icons

## Publish on GitHub Pages
Upload the contents of this folder (not the folder itself) to the root of your repository's `main` branch. In GitHub, open Settings → Pages and set Deploy from a branch, `main`, `/ (root)`. Wait for deployment, then open the HTTPS Pages URL in Chrome.

## Important data note
Records and attachments are stored in IndexedDB in the browser on the device. They are not cloud-synchronised. Export records periodically. Do not clear Chrome site data if you want to retain app records. The app starts empty; it does not import the old app's records.
