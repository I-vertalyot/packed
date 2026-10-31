# Sbaleno · Packed

A travel packing app. Keep an inventory of the things you usually take, plan what you need for each day of a trip, then tick items off while you pack.

- **Inventory:** items grouped into categories, each with its own colour
- **Trips:** a list for each day plus "Whole trip" for documents, chargers and so on; copy a day or use it for every day
- **Packing:** one combined checklist with quantities added up
- **PDF export:** download a printable packing list for any trip
- **Czech / English:** switch with CS / EN (the English version is called *Packed*)
- **Works offline** and can be added to your phone's home screen

Your data is stored on your own device (in the browser's local storage). Use **Inventory → Backup** to download it as a file or move it to another device.

## Publish on GitHub Pages

1. Upload all files in this folder to a GitHub repository (in the main folder, not a subfolder).
2. In the repository go to **Settings → Pages**, set *Source* to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
3. After a minute the app is live at `https://<your-username>.github.io/<repository-name>/`.

## Install on your phone

Open that address on your phone. In Safari tap **Share → Add to Home Screen**; in Chrome tap **⋮ → Add to Home screen** (or **Install app**).

## App stores

Everything for Google Play and the App Store is in the [`store`](store) folder:

- [`store/store-listing.md`](store/store-listing.md) – names, descriptions, keywords and privacy answers in English and Czech
- icons, the Google Play feature graphic and phone screenshots for both stores
- [`store/github-user-site`](store/github-user-site) – files for a separate repository named `I-vertalyot.github.io`, needed so the Android app opens without a browser bar

App ID: `com.ivertalyot.packed` · Privacy policy: https://i-vertalyot.github.io/packed/privacy.html
