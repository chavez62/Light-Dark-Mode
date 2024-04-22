# Theme Switcher

## Project Overview
This project implements a dynamic theme switcher that allows users to toggle between dark and light visual themes on a web interface. Utilizing modern web technologies, this functionality enhances user experience by providing visual comfort under various lighting conditions.

### Features
+ Theme Toggle: Users can switch between a light and dark theme using a toggle switch.
+ Persistent State: The theme preference is saved to local storage, allowing the theme to persist across browser sessions.
+ Dynamic Content Updates: When switching themes, not only does the UI's color scheme change, but also the images adapt to match the selected theme.

### Technologies Used
+ HTML/CSS: Structured and styled the webpage.
+ JavaScript: Managed theme switching logic and local storage interactions.

### Core Functions
+ darkMode(): Applies the dark theme styles to elements, switches icons, and updates images for a darker aesthetic.
+ lightMode(): Applies the light theme styles, switches icons back, and updates images for a lighter look.
+ imageMode(color): Updates the source paths of images to reflect the current theme.
+ switchTheme(event): Toggles the theme based on the toggle switch's state and updates the local storage.
+ localStorage: Checks for a saved theme when the page loads and applies it if available.

### Setup and Usage
+ Toggle Switch: A checkbox input is used for toggling between themes. Changes trigger the theme switch function.
+ Local Storage: Stores the user's theme preference to ensure the preferred visual style is used on subsequent visits to the page.
