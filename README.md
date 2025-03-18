# FOCUSFLOW CHROME EXTENSION

**Author:** Rihards  
**Version:** 1.0.0  
**Last Updated:** March 18, 2025  
**Description:** FocusFlow is a modern, user-friendly Google Chrome extension designed to boost productivity, minimize distractions, and promote healthy internet browsing habits. It operates locally without reliance on third-party services, offering personalized time management and focus-enhancing features.

---

## FEATURES
- **Smart Focus Mode:** Block or limit distracting websites (e.g., social media, news portals) during set time periods.
- **Productivity Timer:** Built-in Pomodoro timer with customizable work and break phases (25 min, 1 hour, 4 hours, 1 day).
- **Statistics and Analysis:** Visualized data on browsing habits (e.g., time spent on different sites).
- **Motivational Notifications:** Personalized reminders and inspiring quotes to maintain focus.
- **Local Data Storage:** All data is stored locally on the user's device, ensuring privacy and independence from third parties.
- **Dark/Light Theme:** Customizable user interface to suit individual preferences.
- **Predefined Site Blocking:** Easily block popular social platforms with a dropdown menu.
- **Multilingual Support:** Available in English, Latvian, Lithuanian, and Estonian with proper diacritic support.

---

## INSTALLATION

1. **Clone or Download the Repository:**
   - Download the ZIP file from the repository or clone it using:
     ```bash
     git clone https://github.com/yourusername/focusflow-extension.git
2. Load the Extension in Chrome:
     Open Google Chrome.
     Go to chrome://extensions/.
     Enable "Developer mode" in the top right corner.
     Click "Load unpacked" and select the focusflow-extension folder.
     The FocusFlow icon should appear in your Chrome toolbar.
3. Verify Installation:
     Click the FocusFlow icon to open the popup and start using the extension.	 
	 
	 USAGE
       Set Timer: Choose a time interval (25 minutes, 1 hour, 4 hours, or 1 day) and click "Start" to begin the focus session. A warning will confirm the blocking list activation.
       Block Sites: Select from predefined social platforms (e.g., Facebook, X, YouTube) or add custom sites. Sites can only be removed after the timer ends.
       View Stats: Check your daily time spent on various activities in the stats section.
       Customize: Switch between dark and light themes or change the language via the dropdown menus.
       Support the Developer: Click the "Buy Me a Coffee" button to support Rihards!
	   
	 DEVELOPMENT
       Tech Stack
       Frontend: HTML, CSS, JavaScript
       APIs: Chrome Extensions API (chrome.storage, chrome.tabs, chrome.notifications)
       Local Storage: All data is stored using chrome.storage.local.
	   
	 PROJECT STRUCTURE  
	   focusflow-extension/
       ├── manifest.json         # Extension manifest
       ├── popup.html            # Popup user interface
       ├── popup.js              # Popup logic
       ├── background.js         # Background scripts
       ├── content.js            # Content script for webpage interaction
       ├── /styles
       │   ├── main.css          # Styles for popup
       │   ├── content.css       # Styles for content script
       ├── /assets
       │   ├── icon16.png        # 16x16 icon
       │   ├── icon48.png        # 48x48 icon
       │   ├── icon128.png       # 128x128 icon
       ├── README.md             # This file
	   
	 CONTRIBUTING
       Feel free to fork this repository, submit issues, or create pull requests to improve FocusFlow. Contributions are welcome!
	   
     CONTACT
       For questions or support, please reach out to the author via the "Buy Me a Coffee" link or leave a message in the repository (if hosted). 
	   
	   Happy focusing with FocusFlow! 🎯
	   Created with ❤️ by Rihards