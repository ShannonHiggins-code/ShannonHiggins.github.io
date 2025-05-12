Programmed by Shannon Higgins ShannonHiggins@outlook.com

Description
DSU SOAPBOX is a Chrome extension designed to help users define lists of names within different groups and identify them with color-coded checkboxes. The UI is injected into the current webpage and persists until explicitly hidden by the user, providing a convenient way to manage and track named individuals speaking in a Agile Daily Standup ceremony.

Features
Group Management:
Create multiple named groups to organize different sets of names.
Switch between active groups using a dropdown menu.
Remove groups that are no longer needed.
Name Management (within each group):
Add names to the currently active group.
Each name is assigned a unique, vivid color swatch for easy identification.
Checkboxes next to each name to track status.
Animated "explosion" effect when a checkbox is marked as checked.
Ability to delete individual names from a group.
"Clear Checked" button to quickly uncheck all names in the current group.
Persistent UI:
The extension panel is injected into the webpage and remains visible until the user clicks the "Hide" (✕) button.
The panel can be toggled on/off by clicking the extension's toolbar icon.
Oval-shaped, semi-transparent design for the main panel and input elements.
Customizable Appearance:
Vivid color palette for name swatches.
"Impact" font for the main title.
Compact UI elements to maximize space for the name list.
Dynamic Sizing:
The list of names dynamically resizes to show a set number of items before an internal scrollbar appears.
The overall panel height adjusts to its content.
Data Persistence:
All groups, names, and their states are saved using chrome.storage.sync, allowing data to persist across browser sessions and sync between devices (if Chrome sync is enabled).
How to Install/Load the Extension (Development)
Download or Clone: Ensure all extension files (manifest.json, popup.html, popup.css, popup.js, content.js, content_iframe.css, background.js, and the images folder) are in a single directory on your computer.
Open Chrome Extensions Page:
Open Google Chrome.
Type chrome://extensions in the address bar and press Enter.
Enable Developer Mode:
In the top right corner of the Extensions page, toggle the "Developer mode" switch to the on position.
Load Unpacked Extension:
Click the "Load unpacked" button that appears on the left side.
Navigate to the directory where you saved the extension files and select this folder.
Click "Select Folder".
The "DSU SOAPBOX" extension should now appear in your list of extensions and its icon in the Chrome toolbar.
How to Use
Toggle UI: Click the "DSU SOAPBOX" extension icon in your Chrome toolbar to show or hide the main panel on the current webpage.
Create a Group:
Type a name for your new group in the "New group name" input field.
Click the "Add Group" button.
Select Active Group: Use the "Active Group" dropdown menu to choose which group you want to work with.
Add Names:
Ensure a group is active.
Type a name in the "Enter name for this group" input field.
Click the "Add Name" button. The name will appear in the list with a color swatch and a checkbox.
Manage Names:
Check/Uncheck: Click the checkbox next to a name to toggle its state. Checking a box will trigger a small animation.
Delete Name: Click the "✕" button next to a name to remove it from the current group.
Clear Checked: Click the "Clear Checked" button to unmark all checked names in the currently active group.
Remove a Group:
Select the group you wish to remove from the "Active Group" dropdown.
Click the "Remove" button next to the dropdown.
Hide Panel: Click the "✕" (Hide) button at the top right of the DSU SOAPBOX panel to close it.
Files
manifest.json: Defines the extension's structure, permissions, and core files.
popup.html: The HTML structure for the UI panel.
popup.css: Styles for the UI panel's content.
popup.js: Handles all logic within the UI panel (group/name management, animations, communication).
content.js: Injected into web pages to manage the iframe that hosts the UI.
content_iframe.css: Styles the iframe element itself.
background.js: Service worker that listens for the toolbar icon click to toggle the UI.
images/: Folder for extension icons.
Credits
Programmed by: Shannon Higgins ShannonHiggins@outlook.com

[Privacy Policy](https://shannonhiggins.github.io/privacy_policy.html)
