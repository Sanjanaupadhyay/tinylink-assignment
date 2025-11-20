# TinyLink – Frontend URL Shortener (Assignment)

TinyLink is a lightweight frontend-only URL shortener built using HTML, CSS, and JavaScript.  
It does not require any backend server or database. All data is stored inside the browser using localStorage.

This project was created as part of the Full Stack Developer take-home assignment.

---

##  Live Demo (GitHub Pages)

 *Public URL:*  
https://sanjanaupadhyay.github.io/tinylink-assignment/

---

##  Features

- Shorten any long URL instantly
- Auto-generated short IDs like tny-ab12cd
- Copy-to-clipboard button for the short link
- Table showing all previously created TinyLinks
- Click tracking (counts how many times a short link is opened)
- Delete TinyLink entries
- Fully responsive UI
- Data stored in localStorage (persists even after refresh)

---

## Tech Stack

- *HTML5*
- *CSS3*
- *JavaScript (Vanilla JS)*
- *localStorage* for persistent storage

---

##  How It Works

1. User enters a long URL.
2. A short ID is generated using a random string.
3. A TinyLink (fake shortened link) is created.
4. The data is saved to localStorage.
5. The table updates automatically to show:
   - Short link
   - Original URL
   - Click count
   - Actions (Open / Delete)
6. All data remains even after page reload.


