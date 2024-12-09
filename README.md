# Favorite Cars Web App

## Purpose
The Favorite Cars Web App allows users to:
- Browse car categories on the home page.
- Add favorite cars with details like name, category, and specifications.
- View and manage a list of saved favorite cars.

## Features
- Uses jQuery and jQuery UI for a responsive interface.
- Styled with ThemeRoller for a modern and sleek look.
- Utilizes Web Storage to persist user data across sessions.

## Website Structure
### Pages:
1. **Home Page (`index.html`)**:
   - Displays a grid of car categories with buttons linking to the favorites page.
2. **Add Favorite Page (`form.html`)**:
   - Provides a form to save favorite cars with details.
3. **Favorites Page (`list.html`)**:
   - Lists saved favorite cars and their details.

### Navigation:
- A navigation bar is present on all pages to switch between "Home," "Add Favorite Car," and "View Favorites."

## Buttons and Actions
### Home Page:
- **Navigation Bar**:
  - "Home" - Redirects to the home page.
  - "Add Favorite Car" - Navigates to the form page.
  - "View Favorites" - Navigates to the favorites page.
- **Category Buttons**:
  - "Coupe," "Sedan," etc. - Navigate to the favorites list.

### Add Favorite Page:
- **"Add to Favorites" Button**:
  - Saves the entered car data to Web Storage.
  - Displays a confirmation alert.

### Favorites Page:
- Displays all saved cars with their name, category, and specifications.

## Site Map
Home Page (index.html) │ ├── Add Favorite Page (form.html) │ └── Form with fields for car name, category, and specs. │ └── Favorites Page (list.html) └── Displays saved favorite cars from Web Storage.

## URL
The app is hosted on GitHub Pages at: [Favorite Cars Web App]([https://4dollarorphan.github.io/MAD-Final-Project/])
