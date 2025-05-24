 Dark Mode Toggle

This project implements a simple and elegant **Dark Mode Toggle** switch using HTML, CSS, and JavaScript. It allows users to switch between light and dark themes with a smooth sliding toggle button. The user's preference is saved in localStorage, so the mode persists even after refreshing or reopening the page.

---

## Features

- Animated toggle switch with sliding circle effect  
- Switches between light (white background) and dark (black background) modes  
- Saves user preference in `localStorage` for persistence  
- Smooth background color transition  
- Clean and minimal UI design  

---

## How It Works

- The toggle is implemented as a hidden checkbox input styled with a label and a moving circle (`div.circle`).  
- When the checkbox is toggled, CSS animations slide the circle left or right and change the toggle background color.  
- JavaScript listens for input changes, updates the page background color accordingly, and saves the toggle state in localStorage.  
- On page load, the toggle initializes based on the saved preference.

---

## Files

- `index.html` — Contains the toggle input and label structure  
- `style.css` — Handles all styling and animations  
- `index.js` — JavaScript logic to update background color and manage localStorage  

---

## How to Use

1. Clone or download the repository.  
2. Open `index.html` in your browser.  
3. Click the toggle switch to change between dark and light mode.  
4. Your preference will be saved automatically and applied on subsequent visits.

---

## Technologies Used

- HTML  
- CSS  
- JavaScript  

---
