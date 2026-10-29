Memo — Notes App
Memo is a small, clean notes app for keeping school notes, personal notes, and random thoughts in one place.
Features
- Create, edit, and delete notes
- Organize notes into School, Personal, and Random Stuff
- Pin important notes to keep them near the top
- Search note titles and contents
- Sort notes by recently edited, date created, or title
- Responsive layout for desktop and mobile screens
- Saves notes automatically in the browser using localStorage
- Works offline after the HTML file has been saved
- No installation, dependencies, account, or server required
Run Memo
1. Download or copy the memo_notes.html file.
2. Open it in a modern web browser such as Chrome, Firefox, Edge, or Safari.
3. Select New note to create a note.
4. Choose a category, enter a title and note content, and select Save note.
5. Select a note card to edit it. Use the pin icon to pin or unpin it.
You can rename memo_notes.html to index.html if you prefer. The file can also be opened directly from your computer; a development server is not required.
Storage and privacy
Memo stores notes in the browser's local storage on the current browser and device. Notes are not uploaded to a server and do not automatically sync across browsers or devices.

Important: clearing the browser's site data or local storage may delete your notes. Before clearing browser data or moving to another device, make a separate backup of any notes you need to keep. This version does not include a built-in export or import feature.
Technology
- HTML for the app structure
- CSS for layout and styling
- Vanilla JavaScript for note management and interactions
- Browser localStorage for persistence
No package manager or build step is needed.
Project structure
memo/
└── memo_notes.html   # Complete app: HTML, CSS, and JavaScript
If you rename the file to index.html, the structure can instead be:
memo/
└── index.html
Troubleshooting
- My notes are missing: Check that you are using the same browser and browser profile where you created them. Private/incognito sessions may not keep data after the session ends.
- Notes do not save: Ensure your browser allows local storage and has available storage space.
- The app looks different on my phone: The layout adjusts to smaller screens, but the exact appearance depends on your browser and device.
