

✨ Features
🎨 10 Dynamic Themes: Change the vibe instantly. Choose from lush gradient mixes (Sunset, Ocean, Forest, Midnight, Cyberpunk) or clean solid colors (Slate, Mint, Lilac, Peach).
💾 Persistent Local Storage: Your stories are yours. Everything is saved directly to your browser's localStorage. No databases, no servers, zero privacy concerns.
⚡ Zero Dependencies: Completely standalone. No Tailwind, no React, no NPM installs. Just open the file and start writing.
🕰️ Precision Time-Sync: Automatically pulls and logs your exact local time with the click of a button when drafting a new story.
📝 Full CRUD Operations: Effortlessly draft, edit, update, and delete your chronicles.
🔄 Chronological Sorting: Organize your thoughts on the fly with Newest-first or Oldest-first sorting algorithms.
🚀 Quick Start
Because StoryLog requires no external libraries, servers, or APIs, getting started is instant:
Download the index.html file.
Double-click the file to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
Start writing!
Note: Since it uses localStorage, your entries will be saved even if you close the tab or refresh the page, as long as you open it in the same browser.
💻 How to Use
Drafting a Story: Click the + Add Story button. The exact local date and time will auto-fill. Type your thoughts and hit "Save / Commit".
Editing: Made a typo? Click ✏️ Edit on any existing story card to bring it back into the draft modal.
Changing Themes: Use the dropdown menu in the top left to instantly transition the background aesthetics.
Sorting: Use the secondary dropdown to flip between chronological and reverse-chronological views.
🛠️ Under the Hood
Architecture: Single-file web application (HTML/CSS/JS).
Styling Engine: Pure CSS utilizing CSS Variables (:root), Flexbox, CSS Grid, and Glassmorphism techniques (backdrop-filter: blur()).
State Management: Vanilla JavaScript DOM manipulation utilizing ES6 array methods (.filter(), .map(), .sort()).
Data Storage: Local browser cache via JSON.stringify() and JSON.parse() on localStorage.
📜 Credits
Designed and Engineered by Turbocat 🐾
Built with 💜 and pure Vanilla JS.
