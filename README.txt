# D&D Inventory Manager - Prototype 0.1

This is a first working prototype for Android/desktop browsers.

## Included
- Multiple character profiles and campaign names
- Separate inventory per character
- Starter item library with search and category filter
- Add items with one tap; quantity controls
- Equipped and attuned flags
- PP, GP, EP, SP, CP currency tracking
- Custom item creation
- JSON backup and restore
- Browser-local storage

## Important
This first build has a small starter item list, not the complete D&D 2024 catalogue.
The next build can add the complete publicly reusable SRD 5.2.1 equipment and magic-item
content, with the required attribution. Items from books outside the SRD can be entered
as custom items.

## Use
Open `index.html` in a modern browser. Data is saved in that browser on that device.
Use Backup > Export backup regularly. Clearing browser data can erase locally saved data.

For reliable offline home-screen installation on Android, the next step is to package this
as a hosted/PWA app or serve it locally with Termux. A plain local HTML file is the prototype.
